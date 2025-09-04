#Clase 1

#Descargamos Git en nuestro computador

#Despues creamos nuestra cuenta en GitHub con el correo de Sofka

#Volvemos a nuestro Git y agregamos nuestro usuario con el comando git config --global user.name "usuario"

#Tambien agregamos nuestro correo con el comando git config --global user.email correo

#Debemos crear una carpeta en nuestro explorador de archivo con cualquier nombre

#En esa carpeta creamos un archivo de texto con el nombre README.md y lo ubicamos en nuestro Git con cd

#Luego creamos un repositorio remoto en Git hub con cualquier nombre 
 
#Al crearla nos dará dos opciones para poder conectar nuestro repositorio remoto con el local y escogeremos la segunda

#Copiamos y pegamos esa opción en nuestro Git

#Nos pedirá iniciar sesión y cuando lo hagamos ya tendremos nuestra conexión exitosa

#Para subir nuestros commits agregamos el git add (el nombre de nuetro txt o md) después el git commit -m " " y por ultimo el git push para enviarlo a GitHub



#Clase 2


# En la clase vimos lo que eran ramas, commits y varios comandos, se explico el como se podía generar varias ramas dentro de un mismo proyecto y el porque son útiles, además de el orden de cada una de ellas y para que sirve cada una de ellas, con los commits nos explicaron como realizarlos en base a lo que se va haciendo, por si haces una nueva funcionalidad o un arreglo de algún bug con su respectivo alcance que es la zona para cual se realiza este commit y algunos comandos que nos servirán para este tema y lo que veremos y afrontaremos en el futuro.


#Para crear un rama debemos utilizar el git checkout -b + "nombre de la rama" o el git switch -c + "nombre de la rama"
#Para devolvernos a la rama anterior (por si tienes otra) se utiliza git switch - y te devolverá a la anterior
#Se debe generar un commit o un stash para poder cambiar de rama ya que si no se genera un conflicto 
#El stash nos dejara confirmar un cambio de manera temporal por si aun necesitas implementar algo más.
#El conflicto se soluciona en el mismo Readme y terminando con un commit, a la hora de que te aparezca un conflicto el readme te documentara el error y tu lo puedes corregir dejando el cambio que necesites o combinándolos y finalizas con un commit.
#Para implementar los cambios que tuviste en una de tus ramas para otra de ellas o para main ocupas el comando merge.


#Veremos los distintos comandos que nos enseñaron
#git checkout -b o git switch -c (Crear ramas)
#git switch - (Devolvernos a otra rama)
#git branch -d (Eliminar ramas)
#git Branch - (Listar ramas existentes)
#git merge - (unión entre ramas)
#git stash - (Cambios temporales)
#git stash list - (lista de los cambios temporales)
#git stash pop - (Permite editar tu cambio)
