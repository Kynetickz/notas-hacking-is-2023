# Level X

## Objetivo
The password for the next level is stored in a file called **-** located in the home directory
## Datos de Acceso

ssh bandit1@bandit.labs.overthewire.org -p 2220
NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL


## Solucion
```Shell
bandit1@bandit:~$ ls - 
bandit1@bandit:~$ cat - ^C 
bandit1@bandit:~$ cat ./- rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi 
bandit1@bandit:~$ pwd /home/bandit1 
bandit1@bandit:~$ cat /home/bandit1/- rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi 
bandit1@bandit:~$
```


## Notas Adicionales

## Referencias