# Bandit Level 9 → Level 10

## Objetivo
The password for the next level is stored in the file **data.txt** in one of the few human-readable strings, preceded by several ‘=’ characters.

## Datos de Acceso
ssh bandit9@bandit.labs.overthewire.org -p 2220
EN632PlfYiZbn3PhVK3XOGSlNInNE00t
## Solucion
```Shell
bandit9@bandit:~$ ls data.txt 
bandit9@bandit:~$ file data.txt data.txt: data 
bandit9@bandit:~$ strings data.txt | grep == c========== the h;========== password ========== isT n.E========== G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s 
bandit9@bandit:~$
```

## Notas Adicionales

## Referencias