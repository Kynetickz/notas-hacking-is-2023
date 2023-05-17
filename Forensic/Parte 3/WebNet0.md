# Objetivo

We found this [packet capture](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/capture.pcap) and [key](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/picopico.key). Recover the flag.

# Solucion

descargamos los archivos y abrimos el capture con wireshark
una vez dentro de wireshar vamos a la opcion de edit>preferencias>protocols>tls y agregamos la key pico
una vez agregada damos click derecho follow en cualquier tls le damos follow y buscamos la bandera

picoCTF{nongshim.shrimp.crackers}

# Notas adicionales

# Referencias