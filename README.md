# Apunte sobre Git 

## Comandos básicos

```bash

git init #"iniciar Git en la carpeta"
git add (archivo) #"añadir el archivo de la carpeta, o '.' para añadir todo"
git status #"comprobar el estado de los archivos dentro de la carpeta"
git commit -m #"añadir comentario al archivo que se va a subir con 'git add'"
git commit --ammend #"cambiar el comentario del ultimo commit dejandote ver los anteriores commits"
git log #"iniciar sesion para subirlo al repositorio"
git config #"iniciar sesion para subir al repositorio, 'user.email' para poner el mail y 'user.name' para poner el nombre"
git push #"subir el archivo al repositorio"
git clone #"sirve para enviar el repositorio a la carpeta seleccionada, usando el mismo link"
git pull #"actualiza la carpeta que se esta usando"

```
## .gitignore
Es un archivo que sirve para ...
Ejemplo, dentro del archivo .gitignore

```
passwords.txt
build/
*.jpg

```
