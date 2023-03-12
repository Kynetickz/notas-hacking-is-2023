# Bandit Level 14 → Level 15

## Objetivo
The password for the next level can be retrieved by submitting the password of the current level to **port 30000 on localhost**.

## Datos de Acceso
ssh bandit14@bandit.labs.overthewire.org -p 2220
fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq

## Solucion
```Shell
bandit14@bandit:~$ 
bandit14@bandit:~$ nc localhost 30000 fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq Correct! jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt ^C bandit14@bandit:~$
```

## Notas Adicionales

## Referencias