# Setting up the development environment
|Install|Unistall|Delete Cache|view version|
|-------|--------|------------|------------|
|npm install -g @angular/cli|npm unistall -g angular/cli|npm cache verify|npm --version|

## Inicializar el proyecto
    ng new NombreProyecto
## Inicializar el servidor
    ng serve
## Estructura de proyecto    
    [node_modules] ➜ Se trata donde se almacenan todas las bibliotecas de terceros.
    
    [src] ➜ La carpeta del codigo principal.
      [↓ app] ➜ Directorio donde se almacenan los modulos y los componentes.
      [↓ assets] ➜ Directorio donde se almacenan los activos estaticos.
      [↓ environment] ➜ Almacena la configuración de los diferentes entornos.
## Estructura inicial
        [main.ts] ➜ [main.js] ➜ [index.html]
        componentes ➜ module ➜ [index.html] 
La base de nuestro proyecto se forja en el main.ts, y toda esta estructura compleja estara formada de diferentes elementos:
## MODULOS:
 Los modulos se ocuparan de dividir nuestra app en diferentes secciones, la cuales tendran
 sus diferentes comportamientos y componentes, en cada módulo se especificaran que componentes
 formaran parte de él ➜ Ejemplo ➜ AppComponent // 
                                  
## COMPONENTES: DATA ➜ HTML template ➜ LOGIC
    ng g c COMPONENTE
           
## SERVICES:

 
