# Objetivo

Can you crack the password to get the flag? Download the password checker [here](https://artifacts.picoctf.net/c/15/level2.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/15/level2.flag.txt.enc) in the same directory too.

# Solucion

Descargaremos ambos archivos, una vez descargados analizamos el codigo del archivo .py y nos daremos cuenta de que hay una cadena de texto que podemos correr en python para que una vez que corramos el codigo le demos eso como contraseña y nos de la bandera en mi caso fue chr(0x33) + chr(0x39) + chr(0x63) + chr(0x65) que es igual a 39ce 
```Shell
$ python3 level2.py
Please enter correct password for flag: 39ce                                         
Welcome back... your flag, user:
picoCTF{tr45h_51ng1ng_502ec42e}

```

# Notas adicionales

# Referencias