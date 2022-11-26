## Practica Git

**¿Qué comando usaste en el paso 11? ¿Por qué?**
- `git reset --hard HEAD~1`. Porque queremos perder los cambios hechos en 
el working copy.
**¿Qué comando usaste en el paso 12? ¿Por qué?**
* El comando `git reflog` para buscar el hash del commit que queremos 
rehacer, `git reset --hard <hash>` para mover el puntero a donde había 
hecho dicho commit recuperando así el working copy, `git add <file_name>` 
para volver a mover los cambios al staging area y por último, `git commit 
-m "message"` para volver a hacer el commit.
**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
* No, ya que `styled` es hijo de `main`, y además no hubo cambios en este 
último.
**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
* Sí, porque hubo cambios en las mismas líneas, en el mismo archivo, en 
ambas ramas.
**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
* No, ya que en el `main` no hay ningun cambio.
**Que comando o comandos utilizaste en el paso 25?**
* `git log --graph`
**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
* Sí, podría haber sido *fast forward*, ya que seguiría teniendo acceso a 
todos los commits.
**Qué comando o comandos utilizaste en el paso 27?**
* `git reset HEAD~1`
**Qué comando o comandos utilizaste en el paso 28?**
* `git restore <file_name>`
**Qué comando o comandos utilizaste en el paso 29?**
* `git branch -D <branch>`
**Qué comando o comandos utilizaste en el paso 30?**
* `git reflog` para buscar el hash del commit cuando se hizo el merge. Y 
`git reset --hard <hash>`para volver a él.
**Qué comando o comandos utilizaste en el paso 32?**
* `git reflog`para buscar el primer commit. `git reset <hash>`para volver 
a él.
**Qué comando o comandos utilizaste en el punto 33?**
* `git reflog` para buscar el commit en el que añadíamos el título. `git 
reset <hash>` para volver a él.
