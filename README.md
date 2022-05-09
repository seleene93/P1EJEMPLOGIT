# GIT Básico

## Instalación
Instalación desde el asistente de Git

## Comandos para credenciales en nuestro equipo
``` 
git config --global user.name ¨nombreusuario¨
git config --global user.email ¨email¨
``` 




## Crear un repositorio git
```
git init
```

## comprobar el estado de git

Ver la situación eb ka qye están los cambios desde el último comit


```
git status
```
## Añadir archivos al staging area

``` añade todos los cambios pendientes

``` 
git add -A
```

## Crear un commit

Para guardar un conjunto de cambios y crear un punto de control usamos los commit

```
git commit -m ¨mensaje del commit¨
```

## Deshacer cambios a partir de los commit


2 opciones

```
git reset --soft <código-commit>
```
Con --soft podemos volver a un commit anterior sin deshacer cambios





