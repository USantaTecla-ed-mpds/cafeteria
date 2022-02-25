# Connect4
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  

## index

* [domainModel](#domainModel)  
    * [vocabulary](#vocabulary)  
    * [initialState](#initialState)  
    * [finalState](#finalState)
    * [instructions](#instructions)  
## domainModel  
  
![Connect4](../criticaSemanaAnterior/docs/images/conecta4.jpg)  

[WIKI](https://es.wikipedia.org/wiki/Solitario_de_cartas)

[Youtube](https://www.youtube.com/watch?v=yjgQXcFVBQY)

#### Vocabulary

1. Falta sentido de la relación (dirección) entre MOVE y PILE, más si cabe al tener dos enlaces.
2. Con respecto a la relación anterior se podría usar una única fecha con sentido hacia los dos lados.
3. Las jerarquías de suit y move (los dos diagramas a la derecha de Klondike), en ambos todos las clases están en minúsculas.
4. En el diagrama Klondike, las propiedades de suit, debería indicar el tipo, ya que un palo no tiene como propiedades 4 símbolos, podría tener sentido si indicamos que es boolean de los cuales solo uno podrá estar en verdadero (true).
5. En los dos diagramas a la derecha de Klondike todas las clases están en minúsculas.
6. En el diagrama a la derecha de Klondike, el de suit. suit no se compone de los cuatro símbolos, solo de 1. Sería una relación de herencia no de composición.
7. En el diagrama a la derecha de Klondike, el de suit. El color no se compone de dos colores. Sería una relación de herencia. Si veo la relación de uso aunque se podría agregar como propiedad en los cuatro símbolos.


#### InitialState

1. Objetos en mayúsculas
2. Objeto Card se compone a su vez de UpTurned y DownTurned, la relación no debería ser composición fuerte sino débil, o una propiedad en el objeto indicando su estado inicial.

#### FinalState

1. Tableu, Stock y Waste no deberían ser representados. Ya no interactuán con ningún otro objeto.
2. Objetos en mayúsculas




  
