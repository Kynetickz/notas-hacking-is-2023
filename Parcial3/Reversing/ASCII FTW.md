# Objetivo

This program has constructed the flag using hex ascii values. Identify the flag text by disassembling the program. You can download the file from [here](https://artifacts.picoctf.net/c/506/asciiftw).

# Solucion
descargamos el archivo y lo abrimos con gdb, nos daremos cuenta que nos dara una cadena 0x tipo hex en mi caso fue la siguiente
`70 69 63 6f 43 54 46 7b 41 53 43 49 49 5f 49 53 5f 45 41 53 59 5f 33 43 46 34 42 46 41 44 7d 30` la metemos a cyberchef en From hex y nos dara la bandera

picoCTF{ASCII_IS_EASY_3CF4BFAD}

# Notas adicionales

# Referencias