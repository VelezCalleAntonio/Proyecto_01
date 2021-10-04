Antonio Vélez Calle.
Gestión de Bases de Datos.
1º ASIR.

** COMANDOS PARA CREAR UN NUEVO REPOSITORIO CON GIT. **

* git init: creará un nuevo repositorio local GIT.sólo se usa en el momento inicial de la creación de un nuevo repositorio.

* git clone: se usa para copiar un repositorio. (git clone nombredeusuario@host:/path/to/repository).

* git add: se usa para agregar archivos al área de preparación. (git add <temp.txt>).

* git commit: creará una instantánea de los cambios y la guardará en el directorio git. (git commit –m “El mensaje que acompaña al commit va aquí”).

* git config: puede ser usado para establecer una configuración específica de usuario, como el email, nombre de usuario y tipo de formato, etc. (git config --global user.email tuemail@ejemplo.com).

* git status: muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser preparados o confirmados.

* git push: se usa para enviar confirmaciones locales a la rama maestra del repositorio remoto. (git push  origin <master>).
 
* git checkout: crea ramas y te ayuda a navegar entre ellas. (command git checkout -b <branch-name>).

* git remote: te permite ver todos los repositorios remotos. (git remote -v).

* git branch: se usa para listar, crear o borrar ramas.

* git pull: fusiona todos los cambios que se han hecho en el repositorio remoto con el directorio de trabajo local.

* git reset: sirve para resetear el index y el directorio de trabajo al último estado de confirmación. (git reset - -hard HEAD).

* git show: se usa para mostrar información sobre cualquier objeto git.

* git rm: se puede usar para remover archivos del index y del directorio de trabajo. (git rm filename.txt).