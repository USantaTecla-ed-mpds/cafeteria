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
  
![klondike](./docs/images/klondike.png)  

[WIKI](https://es.wikipedia.org/wiki/Solitario_de_cartas)

[Youtube](https://www.youtube.com/watch?v=yjgQXcFVBQY)

###  lab-turing

* [domainModel](#domainModel)  
    * [vocabulary](#vocabulary)  
      * Los movimientos estan asociado a una carta, sobra la asociaciación Card y Pile.
      * Card no son agregados de las clases Stock, Waste, Tableau, Foundation, es suficiente asociar Card a Pile.
      * Card es un concepto abstracto, por lo cual los palos deben heredar de Card, sobra la clase Rank.
      * La relación de composición entre Color y las clases hijas de Suit deben ser inversa, es decir tiene sentido decir las Picas son de color negro, en lugar de decir el negro son Pikas, esto ultimo es lo que representa el diagrama.
    * [initialState](#initialState)  
      * Si en el modelo del dominio Stock, Waste... son compuestos de Klondike en el diagrama de objetos también.
    * [finalState](#finalState)
      * Si en el modelo del dominio Stock, Waste... son compuestos de Klondike en el diagrama de objetos también.
    * [instructions](#instructions)
      * El diagrama de maquinas de estados debe estar unificado o separado por paquetes.


### vocabulary

![Vocabulario]()  
  
### initialState  
  
![Estado_inicial]()  
  
### finalState 

![Estado_final]()  
  
### instructions  
  
![Instrucciones]()  
  
![Instrucciones]()  
  
