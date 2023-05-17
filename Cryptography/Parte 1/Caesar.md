# Objetivo

Decrypt this [message](https://jupiter.challenges.picoctf.org/static/7d707a443e95054dc4cf30b1d9522ef0/ciphertext).

# Solucion

descargamos el archivo y lo abrimos, nos daremos cuenta que la bandera esta revuelta, asi que con el siguiente scrypt la corregiremos

```shell


picoCTF{gvswwmrkxlivyfmgsrhnrisegl} 

import string
import re

abc=string.ascii_letters
encriptado = open ('ciphertext','r').read()
encriptado = re.findall('\{(.*?\}',encriptado)[0]

rot = 25
salida = ''
for car in encriptado:
	salida += abc [ (abc.find(car) + rot) % 26 ]
print(salida)
```


# Notas adicionales

# Referencias