# Objetivo

Help us test the form by submiting the username as `test` and password as `test!`

# Solucion

-Accedemos a la pagina 
-Encendemos el BurpSuite e interceptamos el trafico de la pagina despues de acceder con el usuario "test" y pass "test!"
-Cuando interceptemos el trafico nos daremos cuenta de que interceptamos 3 paginas antes de la pagina que visualizamos normalmente
-En las primeras 2 paginas nos daremos cuenta de que la pagina solicita un metodo GET con un id
-Si decodificamos el id nos daremos cuenta de que esta en Base64 y al decofificarlo nos dara la mitad de la bandera, hacemos lo mismo con las 2 paginas y nos dara la bandera

# Notas adicionales
Esto me costo demasiado ya que yo pense que tenia que redirigir la pagina por que la pista decia "Alguna redireccion" en vez de decir que la interceptara :)

# Referencias