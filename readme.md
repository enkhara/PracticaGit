# Ejercicio 1

### - ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Para deshacer el último commit, perdiendo los cambios realizados en el working copy he utilizado el comando `git reset --hard HEAD~1` (equivale a hacer **git reset + git restore** )para deshacer el último commit, **HEAD~1** mueve una posición el puntero HEAD, y lo que había en el working copy de manera que todo quede como estaba antes. Nuestra staging área se queda vacía. 
### - ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Para rehacer el último commit he usado el comando `git reflog` para saber que identificador tiene el commit anterios para saber dónde hay que mover el puntero HEAD y `git reset --hard <identificadorCommit>` para mover el puntero. 
### - El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
Como estamos en la *branch style* utilizamos el comando ` git merge master `
No ha habido ningún conflicto ya que no hay modificaciones en los mismos archivos y las mismas líneas.
### - El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Este *merge* sí que causo conflicto, ya que había modificaciones en dos ramas diferentes (style y htmlify) y el mismo archivo (git-nuestro.md)
### - El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No hubo ningún conflicto en este merge, ya que no se ha modificado el mismo archivo desde estas dos ramas
### - ¿Qué comando o comandos utilizaste en el paso 25?
`git log --graph --pretty=oneline`
### - El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si que podría serlo, tan sólo haría falta mover el puntero de master y head donde apunta title, ya que title y master están en la misma rama.
### - ¿Qué comando o comandos utilizaste en el paso 27?
`git reset HEAD~1`
### - ¿Qué comando o comandos utilizaste en el paso 28?
`git restore git-nuestro.md`
### - ¿Qué comando o comandos utilizaste en el paso 29?
`git branch -D title`
### - ¿Qué comando o comandos utilizaste en el paso 30?
`git reset --hard 44ea13a`
### - ¿Qué comando o comandos usaste en el paso 32?
`git reflog`
`git reset --hard c7cb93d`
### - ¿Qué comando o comandos usaste en el punto 33?
`git reflog`
`git reset --hard 537e749`
