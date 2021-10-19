# Instrucciones

## Creación de imagen
docker build -t regresion: v0.1 .

## Creación del contenedor

docker run -it -p 8080:8080 -v "$PWD"/code/:/home/code/ --name gitpod_rl1 -h rl1 regresion:v0.1

