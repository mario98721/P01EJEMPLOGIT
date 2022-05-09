# GIT Básico 


## Instalación

Instalación desde el asistente de GIT

## Comandos para credenciales en nuestro equipo 

``` 
git config -- global user.name "nombreusuario"
git config -- global user.email "correousuario"
``` 

## Crear un repositorio git

```
git init
```

## Comprobar el estado de git

Ver la situación en la que están los cambios desde el último commit

```
git init
```

## Añadir archivos al staging area
Añade todos los cambios pendientes

```
git add -A
```

## Crear un commit 
Para guardar un conjunto de cambios y crear un punto de control
usamos los commit

```
git commit -m "mensaje de commit"
```

## Deshacer cambios a partir de los commit 

2 Opciones

```
git reset --soft <código-commit>
git reset --hard <código-commit>

```
Con --soft podemos volver a un commit anterior sin deshacer cambios 
Con --hard todos los cambios pendientes anteriores del índice del entorno de ensayo y
   del directorio de trabajo se restablecen para reflejar el estado del árbol de confirmaciones. 