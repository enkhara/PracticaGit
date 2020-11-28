# Ejercicio 1

### - ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Para deshacer el último commit, perdiendo los cambios realizados en el working copy he utilizado el comando `git reset --hard HEAD~1` (equivale a hacer **git reset + git restore** )para deshacer el último commit, **HEAD~1** mueve una posición el puntero HEAD, y lo que había en el working copy de manera que todo quede como estaba antes. Nuestra staging área se queda vacía. 
### - ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Para rehacer el último commit he usado el comando `git reflog` para saber que identificador tiene el commit anterios para saber dónde hay que mover el puntero HEAD y `git reset --hard <identificadorCommit>` para mover el puntero. 
### - El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

### - El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

### - El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

### - ¿Qué comando o comandos utilizaste en el paso 25?

### - El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

### - ¿Qué comando o comandos utilizaste en el paso 27?

### - ¿Qué comando o comandos utilizaste en el paso 28?

### - ¿Qué comando o comandos utilizaste en el paso 29?

### - ¿Qué comando o comandos utilizaste en el paso 30?

### - ¿Qué comando o comandos usaste en el paso 32?

### - ¿Qué comando o comandos usaste en el punto 33?
