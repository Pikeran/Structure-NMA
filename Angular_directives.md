# DIRECTIVES:
- Estructura ➞ modifican la estructura del DOM.
- Atributo ➞ modifican los atributos del DOM.

En la pagina oficial de [Angular](https://angular.io/api/core/Directive) posees toda la documentación necesaria.
Aqui se mostrara un pequeño recopilatorio de algunas directivas que considero útiles.

### NGIF
        <div *ngIf = "ejemplo.lenght > 0">
            Contenido
        </div>
Si se cumple lo especificado se mostara el elemento ↑.

### HIDDEN PROPERTY
        <div [hidden] = "ejemplo.lenght == 0">
            Contenido
        </div>
Si se cumple lo especificado no se mostará el elemento ↑.

### NGSWITCHCASE
        <div [ngSwitchCase] = "menus">
              <div *ngSwitchCase = "'menu1'"> Contenido </div>
              <div *ngSwitchCase = "'menu2'"> Contenido </div>
              <div *ngSwitchDefault > ContenidoDefault </div>
        </div>
        <a (click) = "menus = 'menu1'"> Seleccion 1 </a>
        <a (click) = "menus = 'menu2'"> Seleccion 2 </a>
 Funciona como un selector switch de Java, el selector especificado se mostrará.
 
 ### NGFOR
        <ul>
          <li *ngFor = "let x of y; index as i">
                {{ i }} - {{ x.name }}
          </li>
        </ul>
