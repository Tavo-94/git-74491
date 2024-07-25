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

