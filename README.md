# MVC_Plantilla
Estructura para proyecto PHP usando el patrón MVC.

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

1. **/ app**: Directorio con todo lo referente al proyecto, núcleo, MVC propiamente dicho.

  - / config: Guarda todos los archivos necesarios para configurar la aplicación. P.e: Constantes o variables globales.
  - / controllers: Ficheros controladores. Pe: 
  - / models: Ficheros correspondientes al modelo. Pe: demo.class.php
  - / views: Ficheros correspondientes a las vistas.
    - /assets : Contiene todos los recursos CSS,JS,FONTS,etc
    - /layouts: Contiene los layouts.
    - /templates: Contiene las plantillas html o embebidas.
    
  - *constantes.php*: Fichero que contine las constantes que se usarán a lo largo del proyecto.		
    
2. **/ lib**: Directorio de librerías, plugins, etc.
  
3. ***index.php***: Fichero raíz del proyecto que servirá como despachador.

### NOTA:
Los ficheros contenidos en los diferentes directorios como **demo-<titulo>.<extensión>**, son referenciales.