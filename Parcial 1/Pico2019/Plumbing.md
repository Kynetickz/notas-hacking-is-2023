# Objetivo

Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `jupiter.challenges.picoctf.org 4427`.

# Solucion
nos tendremos que conectar al servidor con el puerto que nos dieron, pero usaremos el "grep"
para que nos de la bandera mas facilmente
```Shell
nc jupiter.challenges.picoctf.org 4427 | grep "pico"
picoCTF{digital_plumb3r_5ea1fbd7}
```

nos dara la bandera: picoCTF{digital_plumb3r_5ea1fbd7}
# Notas adicionales

# Referencias