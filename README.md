# Openweather

Aplicación web para ver el estado del clima

## Prerequisitos:

Antes de comenzar a interactuar con la aplicación, debes tener instalado el pack de iconos de Bootstrap.  Para ello, en una terminal de linux debes ejecutar:
```
$ npm i bootstrap-icons
``` 


## Clonando el repositorio:
Para clonar el repositorios, es necesario ejecutar lo siguiente:

```
$ git clone https://github.com/clasesucatmarlon/gradiweb-test.git
```

## API de OpenWeather:
Para el desarrollo de la aplicación se trabajó con la API proporcionada por OpenWeather.  Para ello se hizo uso de las siguientes rutas para extraer la información desde el archivo JSON de la misma.

> __Url para la consulta actual del clima:__
> https://api.openweathermap.org/data/2.5/weather?id=${idCity}&appid=${apiKey}&units=metric
  
> __Url para la consulta del clima para los tres dias siguientes:__
> http://api.openweathermap.org/data/2.5/forecast?id=${idCity}&appid=${apiKey}&units=metric
  

* Parámetros:
	```
	idCity: Código de la ciudad. Por ejemplo, para la ciudad de Bogotá el código es: 3688685 (la lista se puede ver en city.list.json)
	```
  	```
	apiKey: Código API que se obtiene en la sección de API Keys (https://home.openweathermap.org/api_keys). Para poder generar una Api Key es necesario estar previamente registrado.
	```

## Ejecutando la aplicación:
Para ejecutar la aplicación se debe abrir en el brwser de preferencia el archivo index.html que se encuentra en el directorio raíz.

## Tecnologías usadas:
1. HTML 5.
2. CSS 3.
3. BootStrap 4
4. JavaScript
5. Control de versiones Git y Github.
6. Despliegue: Heroku

  

## Aplicación desarrollada por:

[Marlon Aurelio García Morales](https://clasesucatmarlon.github.io/portafolioMG/)

[Linkedin](https://www.linkedin.com/in/marlonagarciam/)  
     
 [Twitter](https://twitter.com/garciamarlon)

## Contact0:

Para contactarme escribir a: <clasesucatmarlon@gmail.com>.