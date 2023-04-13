# Objetivo

Our flag printing service has started glitching! `$ nc saturn.picoctf.net 53638`

# Solucion
Entramos al servidor `nc saturn.picoctf.net 53638`, nos dara un codigo de python con el que podremos obtener la bandera, lo corremos y nos dara la bandera
```Shell
$ nc saturn.picoctf.net 53638
'picoCTF{gl17ch_m3_n07_' + chr(0x62) + chr(0x64) + chr(0x61) + chr(0x36) + chr(0x38) + chr(0x66) + chr(0x37) + chr(0x35) + '}'
                                                                                                                                                                                                                                           
┌──(kali㉿kali)-[~/Downloads]
└─$ python3          
Python 3.10.8 (main, Nov  4 2022, 09:21:25) [GCC 12.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print('picoCTF{gl17ch_m3_n07_' + chr(0x62) + chr(0x64) + chr(0x61) + chr(0x36) + chr(0x38) + chr(0x66) + chr(0x37) + chr(0x35) + '}')
picoCTF{gl17ch_m3_n07_bda68f75}
>>> 

```

# Notas adicionales

# Referencias