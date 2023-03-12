# Bandit Level 16 → Level 17

## Objetivo
The credentials for the next level can be retrieved by submitting the password of the current level to **a port on localhost in the range 31000 to 32000**. First find out which of these ports have a server listening on them. Then find out which of those speak SSL and which don’t. There is only 1 server that will give the next credentials, the others will simply send back to you whatever you send to it.
## Datos de Acceso
ssh bandit16@bandit.labs.overthewire.org -p 2220
JQttfApK4SeyHwDlI9SXGR50qclOAil1

## Solucion
```Shell
bandit16@bandit:~$ nmap -p 31000-32000 localhost
bandit16@bandit:~$ exit
bandit17@bandit:~$ cat /etc/bandit_pass/bandit17 VwOSWtCA7lRKkTfbr2IDh6awj9RNZM5e bandit17@bandit:~$ exit
```

## Notas Adicionales

## Referencias