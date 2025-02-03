# Respuesta read 07

## ¿Qué es el control de versiones? ##
El control de versiones es un sistema que registra los cambios realizados en un archivo o conjunto de archivos a lo largo del tiempo, permitiendo recuperar versiones anteriores y colaborar eficientemente en proyectos de software.

## ¿Qué es “clone” en Git? ##
En Git, clone es un comando que se usa para crear una copia exacta de un repositorio remoto en tu máquina local. Esto permite trabajar con el código sin afectar el repositorio original hasta que se realicen cambios y se suban nuevamente.

## ¿Cuál es el comando para agregar los archivos modificados a la zona de preparación?
El comando para agregar los archivos modificados a la zona de preparación es:
git add <archivo>
o para agregar todos los archivos modificados en el directorio actual: 
git add .

## ¿Cuál es el comando para enviar la captura de los archivos modificados a Github? ##
Primero, se debe confirmar los cambios con:
git commit -m "Mensaje del commit"
Luego, se envían los cambios al repositorio remoto con:
git push origin <rama>

[Inicio](https://github.com/Br4nd04/reading-notes.git)