# clase 03 - git desarrollo colaborativo

## Repaso

### Estrategia de ramas basica
![estructuras-ramas](_ref/estrategiaBranches.webp)

## creando una rama

```sh
git branch <nombre-rama>
```

### creando una rama y moverse a la misma

```sh
git branch -c <nombre-rama>
git branch -c feature/footer
```
## listar ramas

```sh
git branch
```

## cambiar de ramas

```sh
git switch <nombre-rama>
```

## toogle entre las 2 ultimas ramas visitadas

```sh
git switch -
```
## borrado de ramas

```sh
git banch -d <nombre-rama>
```
Forzando el borrado con -D
```sh
git banch -D <nombre-rama>
```