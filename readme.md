# COMANDOS GIT

|Comando |Para qué sirve? | Cuando utilizarlo? | Variantes  |
|:------ |:--------- |:--------:| -----------:|
|`git config`| Para configurar el usuario y el email dentro de git | Se utiliza solo cuando se acaba de instalar el programa Git | `git config --global user.name` para actualizar el nombre/`git config --global user.email` para actualizar el email.  |
|`git init`| Para añadir el control de versiones a un directorio de manera local | Cuando quieres crear un repositorio local antes que el remoto | `git init` si está en el WD/ `git init repo` para crear la carpeta y directorio a la vez.  |
|`git status`| Para ver en que área de trabajo se encuentran los ficheros | Cuando quieras saber esa información |   |
|`git add`| Para añadir ficheros del WD a la staging area | Cuando quieras preparar un commit | `git add .`para añadir todos los ficheros/ `git add fichero` para añadir un fichero solo  |
|`git commit -m "Mensaje del commit"`| Para añadir los ficheros del staging area al repositorio local | Cuando quieras guardar el progreso actual al repositorio local |  |
|`git rm --cached`| Para quitar los ficheros del staging area al WD | Cuando quieras quitar un fichero que antes querías hacer commit | `git rm --cached fichero` para quitar solo un fichero/ `git rm --cached -r .` para quitar todos los ficheros   |
|`git log`| Para visualizar los commits realizados | Cuando te interese ver los commits o para saber si está sincronizado con el repositorio remoto |  |
|`git push`| Para subir el commit al repositorio remoto | Cuando quieras compartir los commits realizados a la nube | `git push -f`para forzar el push   |
|`git log`| aligned | centered | aligned  |