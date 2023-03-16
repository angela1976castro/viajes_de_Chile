

# Proyecto Viajes de Chile 
https://angela1976castro.github.io/viajes_de_Chile/
 

# comandos mas usados de git 
para iniciar en git 
```bash 
git init
```
para agregar todos los cambios 
```bash 
git add .
```
```bash 
git add --all
```
para agregar estado normal del ultimo commit 
```bash 
git reset --hard
```
para crear nuestra version 
usamos el commit
```bash 
git commit -m "titulo del commit"
```
commit solo para archivos existentes
```bash 
git commit -am "titulo del commit"
```

para reconstruir todos los archivos y modificaciones sobre el ultimo commit
```bash 
git checkout --.
```

para verficar cuantos commit tengo 
```bash 
git log"
```
para cambiar nombre del ultimo commit(considerar presionar la letra w seguido de la letra a para guardar presionar "esc"
luego ":wq! y luego enter)
```bash 
git commit --amend
```

para crear ramas 
```bash 
git branch nombre_rama
```

para ubicarnos hacia una rama especifica
```bash 
git checkout nombre de la rama
```
para crear y dirigirme rapidamente a una nueva rama
```bash 
git checkout -b nueva rama
```

para ver el listado de ramas
```bash 
git branch
```
para eliminar una rama especifica
```bash 
git branch -d rama_a_eliminar

```

# GITHUB
para crear el repositorio remoto de github
(recomnedacion copiar todo el link cuando creamos nuevo repositorio)
```bash 
git remote ruta_del_github
```

para subir a github
```bash 
git push -u origin nombre_de_la_rama 
```
para saber si hay actualizaciones en el 
repositorio de github
```bash 
git fetch
```

para desacrgar todas las actualizaciones 
pero especificamente de una rama que deseas
(recomendacion, ubicarse en la rama que deseas descargar los cambios) 
```bash 
git pull
```

para ver la version de git 
```bash 
git --version
```
para configurar nombre
```bash 
git config --global user.name "angela castro
```

para configurar correo(recomendacioón, usar la misma cuenta de github)
```bash 
git config --global user.email "correo@gmail.com"
```



