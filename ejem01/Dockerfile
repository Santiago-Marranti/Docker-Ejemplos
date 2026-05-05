# Imagen a usar
FROM php:8.2-apache

# Ejecutamos estos comandos para instalar el editor de texto Vim en el Linux del contenedor
RUN apt-get update && apt-get install -y vim

# copiamos todos los ficheros en el directorio en cuestion
COPY src/ /var/www/html

# Exponemos el puerto 80
EXPOSE 80

# Quien lo ha realizado
MAINTAINER JL Gonzalez “jlgs@cifpvirgendegracia.com”
