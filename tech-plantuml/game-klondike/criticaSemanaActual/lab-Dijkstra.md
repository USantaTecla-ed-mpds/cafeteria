# Klondike
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  


### vocabulary

- Faltan los tipos de movimientos (StockToWaste, TableauToTableau...).
- No entiendo la relaci�n de agregaci�n Pile 0--> Card si las del Waste --> Card, Stock --> Card ... son de asociaci�n.
- Solo hay **13** cartas por palo pero Foundation o Move tienen relaci�n 0..**14** con Card. 
- Se podr�an relacionar las cardinalidades con el Rank y el Suit. RankCount en lugar de 13. SuitCount en vez de 4 (eso ya te dir�a que hay un Foundation por cada palo por ejemplo). RankCount * SuitCount en lugar de 52.
- Pile tiene el comportamiento validMove() pero un objeto de una subclase de Pile no tiene la informaci�n para llevarlo a cabo. isValidMove() ser�a del Move.






  
