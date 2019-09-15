# RiceMVC - Estructura directorios para aplicaciones web
Estructura de directorios para iniciar un proyecto web usando el patrón MVC y con lenguaje PHP.

## Estructura de proyecto
```
├───app
│   ├───config
│   ├───controllers
│   ├───models
│   └───views
│       ├───assets
│       │   ├───css
│       │   ├───fonts
│       │   ├───images
│       │   └───js
│       ├───layouts
│       └───templates
├───lib
└───test
```

### Descripciones

1. **/ app**: Directorio con todo lo referente a la aplicación. Es el núcleo del proyecto. Aquí se encuentra el patrón MVC y otros directorios que sirven de soporte.

  - / config: Guarda todos los ficheros necesarios para configurar la aplicación. Hay dos archivos por defecto: Constantes (variables globales) y conexión (base de datos).
    - *constantes.php*: Fichero que contine las constantes que se usarán a lo largo del proyecto.	
    - *conexion.php*: Fichero que contine la clase para conectarse a una base de datos.	
  - / controllers: Ficheros de controladores. Pe: demo-controller.php, demo.controller.php 
  - / models: Ficheros correspondientes al modelo. Pe: demo-class.php, demo.class.php
  - / views: Ficheros correspondientes a las vistas.
    - /assets : Contiene todos los recursos css, javascript, fonts, imágenes, etc.
    - /layouts: Contiene los layouts en html y php.
    - /templates: Contiene las plantillas html o php embebidas.
2. **/ lib**: Directorio de librerías, plugins, etc.
  - / bower_components: Fichero creado por Bower donde se almacenan los componentes que se intalen.	
  
3. **/ test**: Fichero que guardará todo lo referente a las pruebas.
4. ***index.php***: Fichero raíz del proyecto que servirá como despachador.

### NOTA:
Los ficheros contenidos en los diferentes directorios como **demo-<titulo>.<extensión>**, son referenciales.