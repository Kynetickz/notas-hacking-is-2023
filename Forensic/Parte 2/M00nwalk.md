# Objetivo

Decode this [message](https://jupiter.challenges.picoctf.org/static/fc1edf07742e98a480c6aff7d2546107/message.wav) from the moon.

# Solucion
descargamos el archivo
vamos a la consola y descargamos qsstv
usamos pactl load-module module-null-sink sink_name=virtual-cable y revisamos que diga Outpu null
abrimos el archivo y usamos el siguiente comando $ pactl list short modules | grep null
25      module-null-sink        sink_name=virtual-cable
$ pactl unload-module 25

y nos dara la bandera

picoCTF{beep_boop_im_in_space}
# Notas adicionales

# Referencias