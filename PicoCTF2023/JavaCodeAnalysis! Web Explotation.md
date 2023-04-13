# Objetivo

BookShelf Pico, my premium online book-reading service. I believe that my website is super secure. I challenge you to prove me wrong by reading the ‘Flag’ book! Here are the credentials to get you started:

-   Username: “user”
-   Password: “user”

# Solucion

Iniciamos sesion con el nombre y usuario que nos dieron
-Una vez dentro Inspeccionamos la pagina y nos vamos a almacenamiento y analizamos que dentro tenemos un "auth-token" y un "token-password"
-Nos vamos a https://jwt.io/ y una vez dentro modificamos el role de user a Admin y el valor de UserId de 1 a 0, esto para decirle a el token que somos el administrador
```Shell
eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJyb2xlIjoiQWRtaW4iLCJpc3MiOiJib29rc2hlbGYiLCJleHAiOjE2Nzk2ODA1OTcsImlhdCI6MTY3OTA3NTc5NywiVXNlcklkIjowLCJlbWFpbCI6InVzZXIifQ.VR-6eeOj_S_EXhCspSHOjwZB5NpnricZuegP7RDOKFU
```
-Nos vamos a la pagina y pegamos el "auth-token" modificado, y tambien modificamos el "token-password" en role ponemos "Admin" y en UserId colocamos "0" guardamos y recargamos la pagina
-Una vez esto se nos desbloqueara una ventana de Administrador, ingresamos y al momento de acceder veremos nuestro rol de user, lo modificamos y le cambiamos los permisos de "user" a "Admin" 
-una vez echo esto cerramos sesion y volvemos a acceder con "user" y "user"
-vamos a la pelicula donde dice flag y nos dara la bandera


# Notas adicionales

Me costo un fin de semana hacer este, ya que si no cambiaba bien un campo como el de user o id la pagina se bugeaba y pensaba que mi conexion se caia, y despues de que por fin pude solucionar eso me metia por la bandera y no me aparecia por lo que pensaba que me faltaba algo, no me hubiera dado cuenta de no ser por que cerre sesion por error y ahi fue cuando me funciono
PD: este reto lo senti bugeadisimo por que debia hacer todo perfecto si no se bugeaba y pensaba que era mi internet jajaj

# Referencias

