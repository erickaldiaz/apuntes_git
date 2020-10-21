# Mis apuntes de git

 - **git clone:** clona un repositorio remoto a nuestra
computadora.
 - **git status:** me dice si tengo cambios para subir.
 - **git add:** agrega mis cambios para que luego
subirlos a nuestro repositorio remoto
 - **git commit:** genera una nueva versión con
nuestro código actualizado
 - **git push:** sube los cambios desde nuestro
repositorio local al repositorio remoto
 - **git pull:** me trae los cambios del repositorio remoto.
 - **git rm --cached <nombre del archivo>:** sirve para sacar un add del stage.
 - **git rm f <nombre del archivo>:** para borrarlo del stage y DE TODOS LADOS.
 - **git commit --amend:** para andexar un commit a otro.
 - **git log:** muestra una lista con los commit que se hicieron.
 - **git diff:** compara estados. Puedo comparar commit A con commit B y si pongo un solo parametro, lo compara con el último commit( tirar git log para copiar el N° de commit que quiero comparar)Tener en cuenta el orden en el que se ponen los commit ej git diff <version1> vs <version2>
 - **git reset --soft:** si voy a git log, tomo el ante ultimo, pongo git soft y borra el ultimo commit.
 - **git reset --mixed:** quita un commit del stage los deja listos para add y commitear.
 - **git reset --hard:** borra absolutamente todo
  
 - **git branch -l:** hace una lista de las branchs
 - **git branch -d:** x borra la branch si no tiene nada para pushear
 - **git branch -D:** x borra la branch aunque tengas cosas para commitear o pushear.

