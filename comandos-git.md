# Comandos de git  
git add- git commit- 5git push-3 git branch- 4git checkout-git log -git status-git revert-git pull- 6git merge- git restore- git reset-7 git diff- 8 git fetch
1. comando para inicializar el proyecto en git.
```
git init
```
2. este comando me permite verificar la conexión de mi reposiorio local con mi repositorio remoto.
```
git remote -v
```
3. Es un apuntador móvil que apunta a cada una de nuestras confirmaciones (branches-ramas)
```
git branch
```
4. podemos cambiar de rama. osea pasar de la actual a la proxima que necesitamos acceder.
```
git checkout <nombre-rama>
```

5. podemos subir nuestros cambios guardados en rama local al repositorio remoto.
```
git push
```
6. pasa tus cambios guardados y pusheados de rama creada  a la rama master actualizando y volviendo a la linea de tiempo inicial.
```
git merge <nombre-rama>
```
7. permite comparar cambios en archivos, ramas y commit.
```
git diff
```
8. es un comando principal que se usa para descargar contenidos desde un repositorio remoto. 
> buena practica para revisar cambios en participantes del equipo, recibirlos y luego subir tus cambios para no entrar en conflictos de codigo.
```
git fetch
```