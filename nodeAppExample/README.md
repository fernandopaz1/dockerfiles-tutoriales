# Ejemplo deply nodejs con Docker

Para construir la imagen correr el comando
`docker image build -t nodejs-ejemplo .`

Para instanciar un contenedo correr el comando
` docker container run -itd -p 3000:3000 --name nodejs-ejemplo nodejs-ejemplo`

El mensaje deberia verse en la url
`localhost:3000`
