# CURSO DE GIT Y GITFLOW

Comandos de Git basicos o frecuentes

Comandos:
git init: Crear un nuevo git

git add: Agregar archivos al area de preparacion

git status: Estado del repositorio

git: commit -m pasar archivos del area de rpeparacion al repositorio local

git log: ver las versiones de archivos del repositorio

git clone: clonar un repositorio remoto

git push: modificar el repositorio remoto, con su nueva actualizacion

git pull: actualizar tu repositorio local con la ultima version del remoto

git add . sirve para agregar todos los archivos modificados al area de preparacion

------------------- Git flow ---------------------

INSTALAR EN LINUX GIT FLOW----------


sudo apt-get update

sudo apt-get install git-flow


INICIALIZAR-------------------------

git flow init


COMENZAR UNA CARACTERISTICA---------


git flow feature start MYFEATURE


FINALIZAR UNA CARACTERISTICA--------

git flow feature finish MYFEACTURE Finaliza el desarrollo de una cacteristica.

OBTENIENDO CARACTERISTICAS PUBLICADAS

git flow feature pull origin MYFEATURE Obten una caracteristica publicada por otro.

git flow feature track MYFEACTURE Puedes mantener un seguimiento de tus cambios.


PUBLICAR UNA VERSION-----------------

git flow release start 1.0

git flow release publish 1.0

git flow release finish 1.0

git push oirigin --all --follow-tags

---------------HOTFIX----------------

git checkout develop

git pull

git checkout master

git pull

git flow hotfix star (Nombre)


make changes

git status (verifique el archivo de color rojo)

git add . (agregar archivos)

git commit -m 'Escribe un comentario'

git flow hotfix finish (name)

)Recuerda poner una etiqueta de versión fija 1.2.x por ejemplo 1.2.2
estabas en el maestro, y luego debes estar en la rama de desarrollo


git push origin --all --follow-tags


