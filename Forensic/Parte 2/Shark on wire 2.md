
# Objetivo

We found this [packet capture](https://jupiter.challenges.picoctf.org/static/b506393b6f9d53b94011df000c534759/capture.pcap). Recover the flag that was pilfered from the network.

# Solucion

descargamos el archivo y lo abrimos con wireshark
nos vamos al 
udp.port == 22 
veremos que nos da un hexadecimal, lo metemos a cyberchef y nos dara la bandera

`picoCTF{p1LLf3r3d_data_v1a_st3g0}`

# Notas adicionales

# Referencias