# Educación IT - Docker y Node.js

Aplicación sencilla en Node.js dockerizada. Se toma como base este [ejemplo](https://nodejs.org/es/docs/guides/nodejs-docker-webapp).

## Prueba de código Node.js

- Instalar paquetes requeridos: `npm install`
- Levantar aplicación: `node server.js`
- Ingresar a http://localhost:8080

## Dockerizar

- Crear imágen de contenedor: `docker build . -t my-app:1.0`
- Correr contenedor: `docker run -d -p 3000:8080 my-app:1.0`
- Ingresar a http://localhost:3000
