# creating-a-blog
Este repo, intenta volcar el paso a paso para la creación de un BLOG con Codeingniter 4, pensado para la materia Aplicaciones WEB, de la carrera TECNICATURA EN PROGRAMACION DE COMPUTADORES de la UNLZ

Instalacion de Codeigniter


composer create-project codeigniter4/appstarter blog

Para correr el proyecto

Por consola ubicados dentro de la carpeta del proyecto:

php spak serve

Configurando las variables de entorno en la carpeta blog, encontrarán el archivo env

Cambiar:
# CI_ENVIRONMENT = production 
por
CI_ENVIRONMENT = development --> importante para poder ver errores de manera local

# app.baseURL = ''
por
app.baseURL = 'http://hocalhost:8080', esto es en este caso, si configuran de otra manera la ruta del servidor, esa es la que debe ir en este punto.

Renombrar el archivo y colocar un . (punto) adelante -->.env