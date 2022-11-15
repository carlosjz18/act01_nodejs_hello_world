## Crear container desde una images definida
FROM node:16

## Crear directorio
WORKDIR /usr/src/app

## Copiar archivo en directorio actual
COPY package*.json ./

## Copiar archivo app.js
COPY app.js ./

## Correr comandos en el container
RUN npm install

RUN npm start

EXPOSE 8080

## Generar build
##RUN npm build

##COPY . .