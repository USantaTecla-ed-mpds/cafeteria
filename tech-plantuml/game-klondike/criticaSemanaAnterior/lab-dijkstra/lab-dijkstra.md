# Klondike
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  

## index
   * [domainModel](#domainModel) 
   * [vocabulary](#vocabulary)  
   * [initialstate](#initialstate)  
   * [finalstate](#finalstate) 
   
### domainModel  
  
![klondike](./docs/images/klondike.png)  

### vocabulary

![Vocabulario](./docs/images/klondike_class.png) 

- Falta clase **Player**
- Un **Foundation** tiene un agregado de 1..13 cartas pero al inicio de la partida tiene 0 cartas.
- Un **Deck** tiene un agregado de 1..* cartas. �No podr�a tener 0 cartas cuando est�n todas las del **Deck** en el **Waste**?.
- Un **Pile** tiene 1..7 cartas. �No podr�a tener 0 cartas cuando muevo todas las cartas de un **Pile** a otro? �y por qu� m�ximo tiene 7 cartas?
- Por qu� la relaci�n entre clases **Deck**, **Waste**, **Foundation** con **Card** es de agregaci�n y entre **Pile** y **Card** es de composici�n?
- No dir�a que la relaci�n entre clases **Deck**, **Waste**, **Foundation** y **Pile** con **Card** es de composici�n si no de asociaci�n porque las cartas se van moviendo de un sitio a otro durante la partida, la relaci�n es compartida/p�blica.
- Quitar�a la clase acci�n porque ya est� la de movimiento (la relaci�n ser�a directamente de **Goal** a **Move**).
- Dir�a que la relaci�n entre Goal y Move es de uso (el objetivo se alcanza usando los movimientos).
- Llamar�a a la clase "Goal" de otra forma (AllCardsToFoundationsGoal) para reflejar cu�l es el objetivo.
- Entre las clases de movimiento hay cosas en com�n, WasteToFoundation y PileToFoundation podr�an heredar de clase base From*ToFoundation por ejemplo.


  
### initialState  
  
![Estado_inicial](./docs/images/Klondike_estado_inicial_objetos.png)  

- Cuando un objeto **Waste** tiene 0 objetos **Card** el objeto **Card** no deber�a aparecer.
- Si **Deck** tiene 24 cartas se deber�a dibujar 24 relaciones, una con cada uno de los 24 objetos Card, no una relaci�n entre dos objetos de cardinalidad 24. Para no pintar los 24 objetos **Card** y sus relaciones con **Deck** se hace de otra manera. Lo mismo para el resto de relaciones del diagrama (Klondike con Pile, Pile con Card etc)
- Relacionado con lo anterior, un objeto Pile no puede tener relaci�n con cartas que est�n todas bocarriba.
- El color es en realidad una propiedad del palo seg�n el diagrama de clases, pero no de la carta.
- La carta del Deck deber�a tener propiedades stick y ranking y sus valores como las otras, aunque este bocaabajo.
  
### finalState 

![Estado_final](./docs/images/klondike_estado_final_objetos.png)  

- Como en el diagrama anterior creo que no se puede pintar que un objeto Klondike tiene una relaci�n de cardinalidad 7 con un objeto Pile para indicar que se relaciona con 7 objetos.
- El Klondike tiene un Goal y el Goal est� asociado a acciones que tienen 1 movimiento, �D�nde est�n estos objetos que son palabras clave (Goal, Action, Move) en el diagrama?.

  
