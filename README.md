# curso-platzi-react-avanzado ⚛️

¡Sígueme en Youtube! https://www.youtube.com/midudev

Repositorio con el código del [Curso Avanzado de React de Platzi]
(https://platzi.com/cursos/react-avanzado/)


* Paso 1: Vamos a clonar el repositorio desde github.com/midudev/curso-platzi-react-avanzado usando git clone URL_DEL_REPO en nuestra consola.
* Paso 2: Vamos a instalar webpack y webpack-cli como dependencias de desarrollo con: 

npm i webpack wepack-cli --save-dev.
* Paso 3: Crearemos una carpeta llama src y dentro de ella un archivo index.js en el cual colocaremos solo un 

console.log('Empezamos el curso!').

* Paso 4: Crearemos en el root de nuestro proyecto un archivo webpack.config.js el cual tendrá toda la configuración de webpack

./node_modules/.bin/webpack src/index.js

Ejecutamos el index con 

node dist/main.js

Compilo con webpack el INDEX

* Paso 5: Instalaremos html-webpack-plugin con: 
npm i html-webpack-plugin --save-dev

* Paso 6: Instalaremos webpack-dev-server con: 
npm i webpack-dev-server --save-dev.

* Paso 7: Añadiremos un nuevo script llamado dev: "dev": "webpack-dev-server".
npm i webpack wepack-cli --save-dev

* Instalación de React y Babel
* En esta clase vamos a configurar React instalando las dependencias 
npm i react react-dom 

* Babel para poder transpilar código jsx a JavaScript Vanilla con: 
npm i @babel/core @babel/preset-env babel-loader @babel/preset-react --save-dev 

*******************************************************

### Clase 6

Linter, extensiones y deploy con Now
En esta clase haremos que el desarrollo sea más ágil y correcto siguiendo los siguientes pasos:

Vamos a instalar StandardJS como dependencia de desarrollo con: 

npm i standard --save-dev. 

StandardJS 

nos va a servir de Linter para una mejor escritura de JavaScript/React.
Agregaremos un nuevo script en nuestro package.json: ""lint"": ""standard"".
Ahora vamos a ignorar aquellos archivos que no queremos que el Linter arregle, añadiremos en nuestro package.json lo siguiente:



### Clase 7 ¿Qué es CSS-in-JS?
Antes la forma en la que construíamos nuestras aplicaciones era con HTML-centric:

<button className='button button-red'>
	Click here!
button>
const button = document.querySelector('button')
button.addEventListener('click', function () {
	doSomething()
})
.button {
	border-radius: 4px;
}

.button-red {
	background: red;
	color: #fff;
}
Luego pasamos a JavaScript-centric:

render () {
	return (
		<button
			className='button button-red'
			onClick={doSomething}
		>
			Click here!
		button>
	)
}
.button {
	border-radius: 4px;
}

.button-red {
	background: red;
	color: #fff;
}
Ahora hoy en día pasamos a CSS-in-JS nos permite no solo hacer el jsx si no colocar los estilos en el mismo JavaScript, de la siguiente manera:

const Button = styled.button`
	border-radius: 4px;
	${props => props.accent && `
		background: red;
		color: #fff;
	`}


render () {
	return (
		
			Click here!
		
	)
}
Con CSS-in-JS no debemos preocuparnos por tener dos clases igual, no nos debemos preocupar por el Critical Path CSS, tendremos un CSS mucho más óptimo.

En esta clase utilizaremos styled-components el cual es una biblioteca para CSS-in-JS pensada más que todo para React

* ICONOS

https://react-icons.github.io/react-icons/icons?name=di

# GENRADOR DE LOGO

https://maketext.io/

