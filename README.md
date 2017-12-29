# SOFTWARRIOR - SW DECISIONES

### Readme
Acá se podrá encontrar la documentación necesaria para entender el código del proyecto.

### Estructura del Proyecto
```
|
|-- /bower_components
|-- /semantic
|-- /app
    |-- /config
    |-- /controllers
    |-- /models
    |-- /public
    |-- /routes
    |-- /views
|-- semantic.json
|-- package.json
|-- server.js
|-- readme.md
```

* En ``/bower_components`` se podrán hallar todos los archivos necesarios para el funcionamiento del cronómetro.
* En ``/semantic`` se podrán hallar todos los archivos necesarios para el funcionamiento del framework de diseño **Semantic-UI**
* En ``/app`` están todos los archivos necesarios de la aplicación propiamentetal.
    * ``/config`` contiene los archivos para configurar la conexión a la Base de Datos (En este caso se ha utilizado Mysql), y la configuración del módulo passport.
    * ``/controllers`` contiene los archivos de los controladores utilizados.
    * ``/models`` contiene los archivos de los modelos que serán enviados para crear la BD.
    * ``/public`` contiene archivos que requiere angularJS para hacer las conexiones pertinentes.
    * ``/routes`` contiene los archivos que configuran las rutas que conectará controladores con vistas.
    * ``/views`` contiene todas las vistas HTML de la aplicación
* En ``semantic.json`` están las configuraciones del template de diseño utilizado.
* En ``package.json`` está toda la información del proyecto, incluyendo los modulos y versiones utilizados.
* En ``server.js`` se cargan todos los archivos necesarios para levantar el proyecto.

###Para correr el Proyecto de SW-Decisiones
Configure la BD en el archivo
```sh
$ app/config/config.json
```

Instalamos los modulos
```sh
$ npm install
```
Levantamos el servidor
```sh
$ node server.js
```
Para acceder al proyecto, desde su navegador web ingrese a **localhost:5000/home**


