**TERMINAL!!!!**

Comandos vistos:

ls --> lista todos los elementos de esa carpeta
cd <nombre del carpeta> --> me lleva a esa carpeta
cd ..  --> me lleva al archivo anterior
mkdir --> me crea una nueva carpeta
get-help --> me muestra ayudas del comando que le pase
clear --> me limpia la terminal.
ctrl + c --> cortan la ejecucion de la consola


**EJERCICIO INSTALAR Y CONFIGURAR GIT**
**GIT**
Para saber si lo tengo instalado tengo que hacer 
git --version
si lo tengo instalado tengo que poner git config --global -e (esto me dirá mis datos).
si no lo tengo instalado tengo que descargarlo https://git-scm.com/downloads

luego configurarlo
 git config --global user.name "su nombre"
 git config --global user.email correo@gmail.com
 luego chequear que este bien 
 git config --global -e


 Luego hacer en la consola, en la ruta correspondiente 
 git init -->empezar el proyecto
 git status -->nos dice los archivos que se modificaron o craron y no estan subidos
 git add index.html --> sube solo el archivo index.html
 git add . --> sube todos los archivos (NO ES UNA BUENA PRACTICA)
 git commit -m"nombre del commit" (MUY IMPORTANTE QUE EL COMMIT DIGA LO QUE HACE LO QUE SE SUBIO)


 