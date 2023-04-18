Describe que hacen los siguientes comandos de git, escribe su descripcion al frente en una sola linea.

git status: Este comando se usa para obtener el estado actual del repositorio

git clone: clona un repositorio utilizando un enlace

git pull: sube los cambios al repositorio

git checkout:cambia entre ramas del repositorio

git log:muestra los cambios que se han realizado en el repositorio

git branch:crea una rama nueva en el repositorio

git add:guarda los cambios realizados en la rama del repositorio en la que se esta trabajando

git commit: confirma los cambios realizados en la rama del repositorio

git push: sube los cambios confirmados del repositorio local al main

git merge: mezcla los cambios realizados en entre ramas

git status: muestra el estado del repositorio, si hay cambios pendientes por addicionar o comentar

(nota personal) se me presento un error que casi no puedo resolver, como clone un repositorio, al momento de subirlo a mi propio repositorio en github me saltaba un error que decia que ya estaba conectado a otro repositorio, para esto tuve que utilizar --verbose para comprobarlo y en lugar de 
usar "git remote add origin https://github.com/hnryart/ENTREGABLE-ADA.git" 
tuve que
usar "git remote set-url origin https://github.com/hnryart/ENTREGABLE-ADA.git"
fin