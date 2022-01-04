# Clase 01- GIT

## Archivos Markdown

## Saber si tengo git instalado

**nota:** ` = backtick => ALT + 96

```sh
git --version 
```

## comando de consola

### Listar archvos en consola

```sh
ls -ls
```

### Crear un git

```sh
git init 
```
## Agregar un usuario
 
```sh
git config user.name "Jose"
```

## Ingreso a un directorio

```sh
cd <directorio>
```

### Retroceder 

```sh
cd .. 
```

### Paso del working directory al index

```sh
git add <nombreArchivo>
```
### Pasar de WD al index mas de un archivo

```sh
git add .
```

### Para ver lo que estamos pasando

```sh
git status
```

### Para pasar del index al repositorio local 

```sh
git commit -m <mensaje>
```
ej:

```sh
git commit -m<agrego info cobre commit>
```
 ### Pasos para subir mi repo local al remoto

 1-. git init
 2-. git add readme.md
 3-. git commit -m "my first repo"
 4-. git remote add origin https://github.com/Iscolso/git-repo-it.git
 5-. git push origin -u origin main 

