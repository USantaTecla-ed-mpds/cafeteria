# game-klondike.0.0.publicationLanguage
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  
  
## requirements 

* Escribe con un lenguaje de publicación (html/css, svg, ...) un tablero lo "más" parecido posible a la siguiente imagen

![Tictactoe](../docs/images/klondike.png) 


## Críticas   


###  lab-turing


### lab-dijkstra 


    
###  lab-lovalace 



    
###  lab-chomsky
1. El código debe ser fluido y resuable entre otras caracteristicas más, por lo cual para crear el efecto de superposición de las cartas en lugar de ir seleccionando uno por uno los elementos li de la  pila podemos utilizar unas reglas de estilos generica, por ejemplo:
ul.pile li:nth-child(1)  { margin: 0em; }
<br>
ul.pile > li  { margin: -8em; }

Con esto evitamos tener que modificar las reglas del estilo con JavaScript cada vez que se realice un movimiento. Por lo cual aqui estamos aplicando la fluidez antes cambio de estados y la reusabilidad del css.
