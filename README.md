###### Paso 11:
Usé el reset --hard HEAD~1, porque el --hard descarta los cambios 
al staging area.

###### Paso 12:
Con el comando git reflog busqué el commit anterior al descarte.

###### Paso 13:
No se puede jalar un branch a lo fast-forward de commits anteriores
contenidos en el branch en el que estoy. Tendría que hacerlo desde master,
no desde styled.

###### Paso 19:
Causó conflicto porque estaban modificadas las mismas líneas del 
git-nuestro.md. Lo resolví borrando las modificaciones de htmlfy manualmente.

###### Paso 21:
No. Es un merge fast forward.

###### Paso 25:
Usé el comando git garph, habiendo hecho antes el alias.graph que contiene 
el --graph, --decorate y el --pretty=oneline.

###### Paso 26:
Podría porque los commits están en lista, consecutivos.

###### Paso 27:
git reset HEAD~1

###### Paso 28:
git checkout -- <file>

###### Paso 29:
git branch -D title

###### Paso 30:
`git reflog` para ubicar el commit y `git reset --hard <ref>` para 
recuperarlo.

###### Paso 32:
`git graph` para encontrar la referencia y luego `git reset --hard <ref>`.

###### Paso 33:
`git reflog` para encontrar el commit y luego `git reset --hard <ref>`.


