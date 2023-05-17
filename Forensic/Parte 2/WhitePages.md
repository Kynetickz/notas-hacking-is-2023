# Objetivo

I stopped using YellowPages and moved onto WhitePages... but [the page they gave me](https://jupiter.challenges.picoctf.org/static/95be9526e162185c741259a75dffa0ab/whitepages.txt) is all blank!

# Solucion
descargamos el archivo y lo abrimos con un hex editor

Tenemos el espacio estándar (0x20) y el Unicode EM SPACE (0xE2 0x80 0x83). Como solo tenemos dos opciones, intentaremos tratarlas como binarias.

corremos el siguiente script [https://github.com/HHousen/PicoCTF-2019/tree/24b0981c72638c12f9a8572f81e1abbcf8de306d/Forensics/WhitePages/script.py]
y nos dara la bandera

# Notas adicionales

# Referencias