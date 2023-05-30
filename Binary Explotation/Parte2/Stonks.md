# Objetivo

I decided to try something noone else has before. I made a bot to automatically trade stonks for me using AI and machine learning. I wouldn't believe you if you told me it's unsecure! [vuln.c](https://mercury.picoctf.net/static/e4d297ce964e4f54225786fe7b153b4b/vuln.c) `nc mercury.picoctf.net 20195`

# Solucion

nos conectamos al servidor, colocamos la opcion 1 y cuando nos pida nuestra api  colocamos la cadena %x_ unas 20 veces para que nos de el formato hexadecimal, una vez que nos lo de la llevamos a cyberche y le damos las opciones de From Hex y Swap Endiannes, una vez que nos lo traduzca si no nos da la bandera borramos caracteres hasta que nos de la bandera correcta



picoCTF{I_l05t_4ll_my_m0n3y_6045d60d}

# Notas adicionales

# Referencias