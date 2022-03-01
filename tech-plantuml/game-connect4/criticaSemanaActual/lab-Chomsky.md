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

1. Cardinalidad 1, no es necesario representarla.
2. Relación Player - Goal no es de composición. No es un parte del Player y nace con un Goal que pueda ser Vertical, Horizontal,........
3. Relación Goal - Movement si debería ser composición fuerte. No es posible un Goal sin un Movement.
4. El Movement no se compone de Grid. La relación correcta debería ser relación de uso. En esa relación sobran los 1 en ambos extremos.
5. Falta relación de Turn con Movement.
6. Falta sentido de la relación entre Player y Piece.
7. La relación Grid Coordinate tiene más de 1 en cardinalidad. Debería ser 6x7.
8. La relación Board - Grid es de 1.


#### InitialState

1. Objetos en mayúsculas
2. Falta sentido de la relación entre YellowPiece y Player2
3. Falta relación de Player1 con RedPiece
4. El objeto Gridnxn debería llamarse Grid y no diferente a la clase. Es un objeto inventado que no está en el modelo de dominio.
5. Falta conocer el estado de Grid, indicar cuantas piezas posee.
6. Goal no está representado.


#### FinalState

1. Objetos en mayúsculas
2. Falta sentido de la relación entre YellowPiece y Player2
3. Falta relación de Player1 con RedPiece
4. El objeto Gridnxn debería llamarse Grid y no diferente a la clase. Es un objeto inventado que no está en el modelo de dominio.
5. Falta conocer el estado de Grid, indicar cuantas piezas posee.
6. Goal no está representado


  
