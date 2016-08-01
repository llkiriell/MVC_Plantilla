# MVC_Plantilla
Estructura para proyecto PHP usando el patrón MVC.

## Estructura de proyecto

- **MVC_Proyecto** 
  - ***/ app***			
    - / models	
    - / controlles		
    - / views		
    - constantes.php		
  - ***/ libs***		
  - ***/ site***		
    - / html		
    - / css			
    - / js		
    - / ajax			
    - / imges			
  - ***index.php***

### Descripciones

1. **/ app**: Directorio con todo lo referente al proyecto, núcleo, MVC propiamente dicho.

  - / models: Ficheros correspondientes al modelo. Pe: demo.class.php
    
  - / controllers: Ficheros controladores. Pe: 
    
  - / views: Ficheros correspondientes a las vistas.
    
  - *constantes.php*: Fichero que contine las constantes que se usarán a lo largo del proyecto.		
    
2. **/ libs**: Directorio de librería, plugins, etc.

3. **/ site**: Directorio dedicado al FrontEnd, ficheros estáticos, plantillas, estilos.

  - / html: Plantillas html, módulos, etc.		
  - / css: Hojas de estilos.			
  - / js: Ficheros JavaScript. 		
  - / ajax: Ficheros referentes a AJAX.			
  - / images: Imágenes del proyecto
  
4. ***index.php***: Fichero raíz del proyecto que servirá como despachador.

### NOTA:
Los ficheros contenidos en los diferentes directorios como **demo-<titulo>.<extensión>**, son netamente referenciales.
