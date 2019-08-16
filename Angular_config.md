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
## Modulos:
        Los modulos se ocuparan de dividir nuestra app en diferentes secciones, la cuales tendran
        sus diferentes comportamientos y componentes, en cada módulo se especificaran que componentes
        formaran parte de él ➜ Ejemplo ➜ AppComponent // 
        
        import { BrowserModule } from '@angular/platform-browser';
        @NgModule({
                declarations: [➜➜ AppComponent]
                ,imports: []
                ,providers: []
                ,bootstrap: [AppComponent]
         })                     
## Componentes:
        Los componentes son partes especificas de la app, estos se ocuparan de administrar partes 
        especificas de nuestra aplicación o website.
## Imports:
        Para cubrir las dependencias de los diferentes apartados de nuestra app, deberemos incluir
        los imports correspondientes, esto nos permitira añadir librerias y funcionalidades externas.
  
 
