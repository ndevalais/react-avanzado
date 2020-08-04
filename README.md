# curso-platzi-react-avanzado ⚛️

¡Sígueme en Youtube! https://www.youtube.com/midudev

Repositorio con el código del [Curso Avanzado de React de Platzi](https://platzi.com/cursos/react-avanzado/)


# Paso 1: Vamos a clonar el repositorio desde github.com/midudev/curso-platzi-react-avanzado usando git clone URL_DEL_REPO en nuestra consola.
# Paso 2: Vamos a instalar webpack y webpack-cli como dependencias de desarrollo con: 

npm i webpack wepack-cli --save-dev.
# Paso 3: Crearemos una carpeta llama src y dentro de ella un archivo index.js en el cual colocaremos solo un 

console.log('Empezamos el curso!').

# Paso 4: Crearemos en el root de nuestro proyecto un archivo webpack.config.js el cual tendrá toda la configuración de webpack


./node_modules/.bin/webpack src/index.js

Ejecutamos el index con 

node dist/main.js



Compilo con webpack el INDEX



# Paso 5: Instalaremos html-webpack-plugin con: 
npm i html-webpack-plugin --save-dev

# Paso 6: Instalaremos webpack-dev-server con: 

npm i webpack-dev-server --save-dev.


# Paso 7: Añadiremos un nuevo script llamado dev: "dev": "webpack-dev-server".


 npm i webpack wepack-cli --save-dev

# Instalación de React y Babel
# En esta clase vamos a configurar React instalando las dependencias 
npm i react react-dom 

# Babel para poder transpilar código jsx a JavaScript Vanilla con: 
npm i @babel/core @babel/preset-env babel-loader @babel/preset-react --save-dev 
