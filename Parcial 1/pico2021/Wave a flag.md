# Objetivo

Can you invoke help flags for a tool or binary? [This program](https://mercury.picoctf.net/static/fc1d77192c544314efece5dd309092e3/warm) has extraordinarily helpful information...

# Solucion
tenemos que abrir el archivo pero a la vez tenemos que darnos permiso para abrirlo
```Shell
──(kali㉿kali)-[~/Downloads]
└─$ chmod +x warm  
                                                                                                                                                                                                                                           
┌──(kali㉿kali)-[~/Downloads]
└─$ ./warm -h      
Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_6635aa47}
                                       
```
y nos dara la bandera la cual es:
# Notas adicionales

# Referencias