# Klondike
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  


### vocabulary

- Faltan los tipos de movimientos (StockToWaste, TableauToTableau...).
- No entiendo la relación de agregación Pile 0--> Card si las del Waste --> Card, Stock --> Card ... son de asociación.
- Solo hay **13** cartas por palo pero Foundation o Move tienen relación 0..**14** con Card. 
- Se podrían relacionar las cardinalidades con el Rank y el Suit. RankCount en lugar de 13. SuitCount en vez de 4 (eso ya te diría que hay un Foundation por cada palo por ejemplo). RankCount * SuitCount en lugar de 52.
- Pile tiene el comportamiento validMove() pero un objeto de una subclase de Pile no tiene la información para llevarlo a cabo. isValidMove() sería del Move.






  
