#Comando de git.

**git --version**
*Verificamos la version del git.*

**git help**
*Visualizar la ayuda de comandos*

**git config --global user.name "Jaime"**
*Registrar tu nombre en la configuracion global y git sepa para quien esta trabajando y cuando haga un commit va saber quien esta haciendo el commit*

**git config --global user.email "jaimeantonioadd@gmail.com"**
*Para saber el correo de la persona en la cual iso el commit*

**git config --global -e**
**

**ls**
*Para saber en que carpeta estamos*

**ls -al**
*Para saber todos los documento que se estan trabajando*

**git init**
*Para inicializar un repositorio o un proyecto*

**cd 'ruta'**
*Nos sirve para cambiarnos de ruta*

**git status**
*Ver el estado de nuestros documentos*

**git add .**
*Es para que git prepare todos los documentos para hacer el siguiente paso q es el commit*

**git add -- .**
*Es para que git prepare todos los documentos al stage*

**git commit -m 'mensaje'**
*Nos permite sacarle una foto a como esta el hasta hora el repositorio o proyecto en este momento.*

**git config core.autocrlf true**
*corregir posibles errores*

**git log**
*Nos permite ver los commit que hemos hecho en el respositorio parte del mas reciente al mas antiguo*

**git add nombre**
*Especificar un archivo individualmente*

**git add *.png**
*Seleccionar todos los archivos que termine con extension png*

**git add nombre/**
*Selecciona todo lo que esta dentro de esa carpeta*.

**git reset *.xml**
*retroce del stage *

**git log --oneline**
*Para visualizar de una manera diferente los commit que hemos realizado*

**git log --oneline --decorate --all --graph**
*Darle decoracion a la vista de los commit realizado*

**git status -s**
*Ver el estado que esta nuestra rama*

**git status -s -b**
*Ver el estado de nuestro documento y la rama o branch en cual nos encontramos*

**git config --global alias.lg 'log --oneline --decorate --all --graph**
*No sirve para acortar un comando en la consola*

**git diff**
*Podemos ver lo que hicimos anteriormente.*

**git diff --stage**
*Podemos ver todos los estado de lo archivo cuando esten en el escenario*


**git commit -am -m ' mensaje '**
*Se salta el stage y el commmit automaticamente*

**git commit -amend -m 'Mensaje nuevo'**
*Cambia el nombre del ultimo commit*

**git reset --soft HEAD**
*Se retrocede al ultimo commit*

**git reset --soft HEAD^**
*Nos retrocedemos al commit anterior de el ultimo y el commit se cambia con el nuevo commit  que le asignmaos.*


**git reset HEAD nombre**
*Te retroce al estado no rastreado*

**git reset --mixed codigo**


**git reset --hard codigo**
*Retrocedemos en el tiempo *

**git reflog**
*Ve el historial de todos los cambios que haz hechos desde el inicio hasta el final*

**git mv nombreactual nuevoNombre**
*Le cambia el nombre a un archivo o documento que se esta utilizando en el repositorio.*

**git rm nombredelarchivo**
*Eliminaos el archivo o documento que estemos trabajando en el repositorio.*

**git add -u**
*Actualizamos Todo*

**.gitignore**
*Ignora todos los archivos o documento que no queramos que se vallan al repositorio*

**git branch**
*Nos dice el nombre de las ramas*

**git branch nombrederama**
*Creamos una nueva rama*

**git checkout nombrerama**
*Nos cambiamos a la rama*

**git diff nombrerama nombresegundarama**
*Compara lo hicimos*

**git merge nombre**
*Unimos la rama con el master*

**git branch -d nombreRama**
*Eliminamos una rama*

**git checkout -b nombreRama**
*Creamos una nueva rama, y nos ubicamos en la rama que creamos*

**git tag nombre**
*Creamos un tag*

**git tag**
*Nos muestra el nombre del tag*

**git tag -d nombre**
*Se elimina el tag*

**git tag -a nombre -m mensaje**
*Creamos el tag y le ponemos un nombres*

**git tag -a v0.1.0 345d7de -m 'Version alfa'**
*Poner tags por codigo*

**git show nombredeltag**
*Nos muestra la informacion*

**git stash**
*Deja un stambay a lo que ha realizado en ese entonces y no se borra*

**git stash list**
*verificamos todos los stach*

**git stash pop**
*extrae el stash*

**git stash drop**
*Elimina el stash*

**git rebase master**
**

**git rebase squash**
*Une dos commit*

**git rebase -i HEAD~4**
*Ve lo 4 ultimos commit*

**git rebase Reword**
*Le cambia el nombre al commit*

**git push --tags**
*Sube todos los tags al repositorio*

**git clone nombre**
*Clona el respositorio*

**git push**
*Sube los cambios al repositorio*

**git pull**
*Baja los cambios del respositorio*

**git fetch**
**