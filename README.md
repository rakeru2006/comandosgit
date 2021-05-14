# Comandos con git

git init <- iniciar el directorio en modo github
git remote <- donde esta el repositorio de gihub en la nube
git pull <- syncroiza descargando ultimos cambios en github a tu maquina
git push >- syncroniza subiendo ultimos commits de tu maquina a github
git commit -> tag para version y cambios en tu maquina
git clone -> descarga un repositorio completo (incluido la configuracion del remote)
git add -> agrega el archivo a "stagged" mode desde el "unstagged" mode


Nacimiento de un repositorio

SI LO HACES LOCAL para SUBIRLO a github/gitlab (Generalmente UNA VEZ NADAMAS)
git init
git remote

SI YA ESTA EN GITHUB lo BAJAS! UNA VEZ NADAMAS ya tiene la configuracion del remote
git clone <URL_REPOSITORIO>

Por primera ves se usa 

git init <nombre_del_proyecto> Inicia un repositorio local con el nombre.

Para salvar nuestros cambios en el repositorio 

git branch : Validamos que estemos en master o main dependiendo configuracion  
git status : Hace un listado de los archivos modificados 
git add <nombre de archivo> : Añade el archivo modificado o git add . : Añade TODOS los archivos modificados 
git commit -m "Comentario para seguimiento " : Agrega un comentario y guarda los cambios 
git push origin master :suve la informacion a repositorio 

vida de tu repositorio

Resumen modificas MAQUINA archivos 
git add .
git commit -m "Tu Comentario"
git push origin master


modificas en la nube o alguien mas modifico y quieres los cambios en tu maquina
git pull : para actualizar los ultmos cambios en la nuve 


Trabajando con branches en un equipo con diferentes usuarios 

git branch  : se visualiza los branches que has creado 
git branch <nombre_de_branch> : Crea una rama a partir de donde estamos, pero no lo guarda en el repositorio en la nube.
git checkout <nombre_de_branch>: Permite el acceso al branch creado y se puede iniciar nuevos caios para dejar el repo original como estaba 
git push origin -u <nombre-branch>: Guarda la informacion creada en el  branch en repositoio en la nuve 


Muerte o borrado de tu repositorio
git init otra vez
git remote otra vez
git clone otra vez
rm -r .git
rm -r folder

Para generar una nieva llave en MAC 

Ahora, para generar la llave agregá lo siguiente

$ ssh-keygen -t rsa
