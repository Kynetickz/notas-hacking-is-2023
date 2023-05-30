# Objetivo

Can you figure out what is in the `eax` register? Put your answer in the picoCTF flag format: `picoCTF{n}` where `n` is the contents of the `eax` register in the decimal number base. If the answer was `0x11` your flag would be `picoCTF{17}`. Download the assembly dump [here](https://artifacts.picoctf.net/c/530/disassembler-dump0_c.txt).

# Solucion
descargamos el archivo y lo abrimos con cat
```Shell
┌──(kali㉿kali)-[~/Downloads]
└─$ cat disassembler-dump0_c.txt
<+0>:     endbr64 
<+4>:     push   rbp
<+5>:     mov    rbp,rsp
<+8>:     mov    DWORD PTR [rbp-0x14],edi
<+11>:    mov    QWORD PTR [rbp-0x20],rsi
<+15>:    mov    DWORD PTR [rbp-0xc],0x9fe1a
<+22>:    mov    DWORD PTR [rbp-0x8],0x4
<+29>:    mov    eax,DWORD PTR [rbp-0xc]
<+32>:    imul   eax,DWORD PTR [rbp-0x8]
<+36>:    add    eax,0x1f5
<+41>:    mov    DWORD PTR [rbp-0x4],eax
<+44>:    mov    eax,DWORD PTR [rbp-0x4]
<+47>:    pop    rbp
<+48>:    ret
                                                                                                        
┌──(kali㉿kali)-[~/Downloads]
└─$ echo $((0x9fe1a))           
654874
                                                                                                        
┌──(kali㉿kali)-[~/Downloads]
└─$ echo $((0x1f5))  
501
                                                                                                        
┌──(kali㉿kali)-[~/Downloads]
└─$ echo $((0x4))  
4

```
bandera = (654874 x 4) + 501
bandera = picoCTF{2619997}
# Notas adicionales

# Referencias