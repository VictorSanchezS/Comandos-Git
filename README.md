# _SUBIR PROYECTO A GITHUB_
```
git init inicializamos el repositorio
git add -A agregamos los archivos a subir
git commit -m "Primera subida" agregamos un commit
git branch -M main creamos una rama(en este caso main)
git remote add origin <tu-url> conectamos con el repositorio
git push origin main(rama) subimos cambios(en este caso en la rama main)
```
# _SUBIR CAMBIOS_
```
git add -A
git commit -m "Segunda subida"
git push origin main
```
# _RENOMBRAR COMMIT_
```
git commit --amend -m "rename commit"
git push --force origin <nombre-de-tu-rama> (en caso hayas subido cambios)
```
