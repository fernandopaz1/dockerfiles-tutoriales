FROM nginx:latest
COPY ./index.html /usr/share/nginx/html/index.html
COPY ./src/ /usr/share/nginx/html/src/

# nginx es un servidor que en su forma mas basica responde peticiones http con el contenido de la carpeta /usr/share/nginx/html/
# aca creamos nuestro servidor pasandole index.html dentro de ese directrio

## Para crear la imagen de docker usamos el comando (nginx-static es el tag de esta imagen)
# docker image build -t nginx-static .

## Para correr la imagen en el puerto 80 de nuestra pc hacemos
# docker container run -itd -p 80:80 --name nginx-ejemplo-static nginx-static