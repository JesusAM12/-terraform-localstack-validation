# REBASE.md


### 1. Realización de commits con mensajes poco claros

Para empezar, realicé varios commits con mensajes poco descriptivos y agrupé cambios menores en commits separados. Algunos de estos commits fueron:

- "Añado nueva linea que tambien se complementa con la segunda"
- "Añado otra linea que complementa a la primera"

### 2. Ejecución de `git rebase -i HEAD~N`

Utilicé el comando `git rebase -i HEAD~3` para reescribir

### 3. Elección de las acciones para los commits

En el editor interactivo de rebase, cambié el prefijo `pick` por `squash` en los commits que quería combinar. Tambien usé reword

### 4. Confirmación y finalización del rebase

Una vez que terminé de editar el mensaje del commit, utilicé `git rebase --continue` para finalizar el proceso de rebase.

### 5. Realización de un `git push --force`

Para subir los cambios al repositorio, utilicé el comando `git push --force`.


