# Testeando Git
## Git esta re copado

### se cambio el index para testear

### listar una cantidad especifica de commits en el log

git log --oneline - <cantidad>

### git ignore

El archivo .gitignore se crea en la carpeta raiz del repo

### gitkeep
Se crea un archivo vacio .gitkeep para poder agregar al commit una carpeta vacia, en caso de ser necesario. Esto porque git no trackea carpetas, solo archivos


### git commit --amend
Sirve para agregar cambios al ultimo commit
Testeando se agrego esta linea al ultimo commit



## Ramas o branches
Nos permiten trabajar en el proyecto de manera auxiliar

### Crear una rama

git branch <nombre-rama>
git branch feature/navbar
git branch feature/footer


### listar ramas
git branch

### visualizacion de ramas en vsc
* mhutche.git-graph

### apps para la gestion de repos git

* git hub desktop



## Moverme entre ramas

``
git switch <nombre-rama>
git switch feature/rama

``
## Moverme y crear rama

``sh

git switch -c <nombre-rama>
git switch -c feature/navbar

``

### ver todas las ramas del repositorio en el log

```sh
git log --oneline --all --graph --decorate

```

### ver detalle de las ramas y su ultimo commit

git branch -v

### borrar una rama

git branch -d <nombre-rama>
git branch -d feature/navbar

### borrar rama de forma forzada

se fuerza si los cambios de esta rama no estan guardados en ningun otro lado


git branch -D <nombre-rama>
git branch -D feature/navbar


# Fusiones (merge) de ramas (branches)

## comparando contenido de las diferentes ramas

git diff <nombre-rama-a-comparar>

git dif <nombre-rama-1> ... <nombre-rama-n>