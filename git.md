# GIT

## Comandos Generales Terminal

- ls
- cd
- cd ..
- pwd
- mkdir "crear carpeta"
- touch


## Configuraciones Iniciales

- git --version
- git --help

> lo indispensable nombre y mail

- git config --global user.name "tanto"
- git config --global user.email "tanto@tanto.tanto"

## Primeros Pasos

- git init

```bash

# GIT

## Comandos Generales Terminal

- ls
- cd
- cd ..
- pwd
- mkdir "crear carpeta"
- touch


## Configuraciones Iniciales

- git --version
- git --help

> lo indispensable nombre y mail

- git config --global user.name "tanto"
- git config --global user.email "tanto@tanto.tanto"

## Primeros Pasos

> conceptos de ramas

- git init
- git status
- git add "archivo"
- git add .
  > PREPARAR PARA GUARDAR . CON EL PUNTO GUARDA TODO
- git commit -m "este es un mensaje para no abrir el editor"
  > GUARDA EL ESTADO EN UN COMMIT
- git log
- git checkout
  >volver al estado anterior, donde quedo el commit
- git reset
- git alias
- git config --global alias.algo "log -- tanto -- tanto"
  > te ahorra todo lo que pongas "aca " y solo tenes que poner git log tanto que es lo que se ahorro, 
- git ignore
  > ruta expresiones archivos que no queremos tener encuenta .txt 
  Patrón	Significado
# comentario	Comentario
archivo.txt	Ignora ese archivo
*.txt	Ignora todos los .txt
/archivo.txt	Ignora solo en la raíz
carpeta/	Ignora carpeta
**/carpeta/	Ignora carpeta en cualquier nivel
**/*.txt	Ignora todos los .txt en todas las carpetas
!archivo.txt	No ignorar este archivo

- git diff
  > ver los cambios antes de hacer la foto

- desplazamiento entre los commits
- con git checkout nos desplazamos por los commits
  - por commmit
  - por id
  - por tag
  - por rama
- conceptos de cabeza y main de las ramas
- donde estas situado en el arbol
- el main donde estamos trabajando
- y la cabeza es lo que vemos donde estamos parados

```

## HOLA GIT
```bash
echo "# hello-git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:...
git push -u origin main
```

```bash
…or create a new repository on the command line
echo "# GIT2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:zim-31/GIT2.git
git push -u origin main
```

```bash
…or push an existing repository from the command line
git remote add origin git@github.com:zim-31/GIT2.git
git branch -M main
git push -u origin main

```

- Descargar cambios 
```bash
git fetch
```
> descarga los cambios en las ramas
```bash
git merge origin main
```
> trae todos los cambios archivos carpetas etc.
