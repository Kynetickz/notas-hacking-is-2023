## Objetivo

This vault uses some complicated arrays! I hope you can make sense of it, special agent. The source code for this vault is here: [VaultDoor1.java](https://jupiter.challenges.picoctf.org/static/87e103a8db01087de9ccf5a7a022ddf8/VaultDoor1.java)

## Datos de Acceso

## Solucion
revisamos el codigo y veremos que la contraseña esta en un tipo sort dentro del codigo, asi que en la consola agarramos el codigo y lo sorteamos con el siguiente comando 
cat bandera | sort | awk "{print($3)}" tr -d "''" | tr -d "\n"

## Notas Adicionales

## Referencias