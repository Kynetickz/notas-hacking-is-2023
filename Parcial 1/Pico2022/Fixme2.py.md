# Objetivo

Fix the syntax error in the Python script to print the flag. [Download Python script](https://artifacts.picoctf.net/c/4/fixme2.py)

# Solucion
descargamos el codigo y lo corremos, pero nos dara un error
```Shell
$ python3 fixme2.py
  File "/home/kali/Downloads/fixme2.py", line 22
    if flag = "":
       ^^^^^^^^^
SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?


```
el error nos dice que el operador deberia ser == en vez de "=" asi que lo modificamos y nos dara la bandera
```Shell
$ python3 fixme2.py
That is correct! Here's your flag: picoCTF{3qu4l1ty_n0t_4551gnm3nt_e8814d03}

```

# Notas adicionales

# Referencias