# Klondike
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  

## index

* [domainModel](#domainModel)  
    * [vocabulary](#vocabulary)  
    * [initialState](#initialState)  
    * [finalState](#finalState)
    * [instructions](#instructions)  


## domainModel  
  
![klondike](../docs/images/klondike.png)  

[WIKI](https://es.wikipedia.org/wiki/Solitario_de_cartas)

[Youtube](https://www.youtube.com/watch?v=yjgQXcFVBQY)


### vocabulary

![Vocabulario]()  
  
Estoy bastante de acuerdo con el modelo.
Las relaciones entre Player y Goal con Movement tienen cardinalidad n, pero n no es un número fijo, sería de 1 a n

En MovementType se podría agregar el número de cartas permitidas en cada Movement, TableuToTableu 1..13, etc.

El atributo rank de Card se podría omitir, queda bastante claro que Card está compuesta por un Rank.

El cliente Windows calcula una puntuación, sería un atributo de Player.

### initialState  
  
![Estado_inicial]()  

Todas las cartas, independientemente del valor faceUp, tendrían rank y suit = random. Puede generar confusión.

### finalState 

![Estado_final]()  
  
Parece que cada Foundation tiene sólo 2 cartas, una nota entre las cartas "A" y "K" aclararía que el suit está completo.

En lugar de mostrar los 7 Tableau vacíos, con uno sólo y una nota aclaratoria serviría.



### instructions  
  
![Instrucciones]()  
  
  - El título lleva a confusión: "diagram of sequence" cuando es un "Activity diagram".

  - Las acciones "Prepare Stock" y "Prepare tableaus" pueden ir en la misma caja, forma parte de la preparación del juego.

  -  Falta el primer movimiento Stock to Waste antes de comprobar si el juego está acabado.

  - Parece que se elige un movimiento y después se comprueba si es posible. Si no lo es, se podría omitir la acción "No move"
![Instrucciones]()  
  
