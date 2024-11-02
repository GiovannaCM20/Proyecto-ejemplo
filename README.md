# Introduccion a Git

## Descripcion

El programa **HolaMundo.py** lo que hace con la ultima actualizacion es imprimir un Hola Git

El objetivo de esta practica es aprender a usar Git desde la creacion de un repositorio local y conectandolo con uno remoto.La idea es familiarizarse con los comandos y configurar un archivo **.gitignore** para evitar subir archivos innecesarios. Al final, poder entender el flujo de trabajo para organizar proyectos de manera mas eficiente.

## Instrucciones de uso

Primero, necesitas clonar este repositorio. Para hacerlo, abre una terminal en tu ordenador y escribe el siguiente comando `git clone URL`. Para obtener la URL del repositorio, haz clic en el boton **Code** en GitHub y selecciona la opcion **HTTPS**.Copia esa URL y reemplaza URL en el comando con la direccion copiada.

Una vez ejecutado el comando, se creara una carpeta en tu equipo que contendra el contenido del repositorio. A continuacion, abre Visual Studio Code, selecciona la carpeta que acabas de descargar, y podras ver todos los archivos del proyecto. Para ejecutar el programa, haz clic en el icono de **play** en la esquina superior derecha de Visual Studio Code.

## Comandos utilizados

* git config --global user.name "Nombre_usuario"
* git config --global user.mail "miemail@mail.com"
* git init
* git remote ALIAS URL_repositorio
* git add -A
* git commit -m "mensaje"
* git push ALIAS master
* touch .gitignore
* git status

## Archivo .gitignore

Este archivo fue creado para ignorar todos los archivos inncesarios del proyecto. En este caso, ignorara especificamente los archivos con la extension **.log**.

Al ejecutar el programa, debe mostrarse el mensaje **Hola Git**. Para asegurarnos de que el archivo **debug.log** no se haya subido al repositorio, utilizaremos el comando `git status`; si el archivo ha sido ignorado correctamente, no aparecera en la lista de archivos no rastreados.

