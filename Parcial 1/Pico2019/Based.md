# Objetivo
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with `nc jupiter.challenges.picoctf.org 29956`.

# Solucion
nos conectamos al servidor con el nombre y el puerto que nos dieron, una vez dentro tendremos que darle al servidor 3 respuestas pero vienen codificadas, tendremos que descrifrarlas para obtener la respuesta
```Shell
nc jupiter.challenges.picoctf.org 29956
Let us see how data is stored
socket
Please give the 01110011 01101111 01100011 01101011 01100101 01110100 as a word.
...
you have 45 seconds.....

Input:
socket
Please give me the  143 157 154 157 162 141 144 157 as a word.
Input:
colorado
Please give me the 636f6e7461696e6572 as a word.
Input:
container
You've beaten the challenge
Flag: picoCTF{learning_about_converting_values_b375bb16}
                                                                                                          
```
en mi caso fueron estas pero son aleatorias la bandera es: picoCTF{learning_about_converting_values_b375bb16}
# Notas adicionales

# Referencias