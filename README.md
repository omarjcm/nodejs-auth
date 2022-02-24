# Proyecto en Node.js

## Instalacion de paquetes

npm i express bcryptjs cors dotenv jsonwebtoken mongoose morgan helmet

npm i @babel/core @babel/cli @babel/node @babel/preset-env nodemon -D

En el caso de existir errores al cambiar a nodemon se debe instalar babel de otra manera:
npm i -g @babel/node

Luego de esto se procede a la ejecucion del programa de la siguiente manera:
npm start

Ahora, para habilitar el ambiente de trabajo de desarrollo, se debe realizar lo siguiente (esto antes de realizar los cambios en package.json):

npm run build

npm run dev

npm start

Luego, se crean los siguientes directorios en el directorio principal del proyecto:

cd src
mkdir controllers libs middlewares models routes

Luego, crear los siguientes archivos en el directorio src:
- app.js
- config.js
- database.js

