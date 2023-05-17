# Objetivo

We found this [packet capture](https://jupiter.challenges.picoctf.org/static/fbf98e695555a2a48fe42c9a245de376/capture.pcap) and [key](https://jupiter.challenges.picoctf.org/static/fbf98e695555a2a48fe42c9a245de376/picopico.key). Recover the flag.

# Solucion

descargamos los archivos y abrimos el capture con wireshark
una vez dentro de wireshar vamos a la opcion de edit>preferencias>protocols>tls y agregamos la key pico
una vez agregada damos click derecho follow en la imagen del protocolo  le damos follow en tls y buscamos la bandera contenida en la imagen

picoCTF{honey.roasted.peanuts}


# Notas adicionales

# Referencias