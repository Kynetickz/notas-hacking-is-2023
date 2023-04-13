# Objetivo

Can you crack the password to get the flag? Download the password checker [here](https://artifacts.picoctf.net/c/16/level3.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/16/level3.flag.txt.enc) and the [hash](https://artifacts.picoctf.net/c/16/level3.hash.bin) in the same directory too. There are 7 potential passwords with 1 being correct. You can find these by examining the password checker script.

# Solucion

Descargamos los 3 archivos y analizamos el file3.py una vez dentro vemos que tenemos 7 posibles contraseñas asi que probamos con una hasta encontrar la indicada y nos de la bandera en mi caso fue 865e, corremos el codigo, la introducimos y listo
```Shell
$ python3 level3.py
Please enter correct password for flag: 865e
Welcome back... your flag, user:
picoCTF{m45h_fl1ng1ng_2b072a90}
```

# Notas adicionales

# Referencias