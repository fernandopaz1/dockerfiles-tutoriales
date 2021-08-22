# aca estoy usando ubuntu latest como base para crear mi image
FROM ubuntu

# estas lineas me permiten correr comandos al crear el contenedor
RUN mkdir app
RUN cd  /app & touch data.txt

# para generar la imagen a partir del Dockerfile hay que correr el siguiente
# comando en el mismo directorio que se encuentra el Dockerfile
# solo se permite un Dockerfile por directori
#
# # para generar la imagen a partir del Dockerfile hay que correr el siguiente
# comando en el mismo directorio que se encuentra el Dockerfile
# solo se permite un Dockerfile por directorio
#
# docker image build -t ubuntuImage .
#
# El flag -t indica que le vamos a pasar un nombre a la imagen a crear
# El punto es si ejecutamos el comando en el mismo directorio del Dockerfile
# si nos ecnontramos en otro directorio hay que poner el path completo
