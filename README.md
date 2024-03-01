# README
Este repositorio ofrece dos opciones para dockerizar una aplicación de votación realizada en la Tecnicatura en Programación de la UTN:

Opción 1:
En el directorio appGit, encontrarás un Dockerfile que te permite levantar un contenedor de Docker con NGINX. Este contenedor clona el repositorio directamente dentro del contenedor. La imagen correspondiente ya está creada y disponible en Docker Hub.

Para ejecutar la imagen, simplemente utiliza el siguiente comando de bash:
docker run -d -p 3000:80 marcelocepeda/vote_app_git

Este comando lanzará la aplicación web en el puerto 3000 del host.

Opción 2:
En el directorio appLocal, encontrarás otro Dockerfile diseñado para levantar la misma aplicación web, junto con el directorio que contiene los archivos de la web.

Ambas opciones ofrecen formas alternativas de dockerizar la misma aplicación de votación. 
