# game-klondike.0.0.dataLanguages
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  
  
## requirements 


## Críticas   


###  lab-turing


### lab-dijkstra 


    
###  lab-lovalace 



    
###  lab-chomsky

1. Player no es un elemento del nodo start, tiene que ser un elemento de la raiz para que la información este modularizada.
2. Se almacena información relevante de la partida en atributos, por ejemplo el número de cartas, estado, posición... estos datos deben residir como contenido de los elementos y reservar los atributos para:
    * Información de valores cortos
    * Información de valores enumerados
    * Meta-información de la implantación

3. Si estás pintando un historico de movimientos el uso de ID ayudaría a ver el orden de ejecución.
4. Para señalar el origen y el destino de un movimiento puedes reducir el contendido del XML con referencias de ID.

