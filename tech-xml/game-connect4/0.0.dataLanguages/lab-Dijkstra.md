# game-connect4.0.0.dataLanguages
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  
  
## requirements 

[Enunciado](https://github.com/USantaTecla-ed-mpds/cafeteria/blob/master/tech-xml/example.md)

## Initial state
- El enunciado pide modelar la historia de una partida, pero la información del xml no contiene movimientos.
- hole (singular) en vez de holes1, holes2, holes3 . La coordenada del hole son 2 números que ya vienen indicados por el row y el column.
- Un hole no tiene una propiedad "valor" que puede ser yellow o red si no que contiene o no una ficha amarilla o roja. Creo que sería así:
		
		<hole>
        	<row>1</row>
        	<column>1</column>
        	</yellowPiece>
    	</hole>
    	<hole>
        	<row>1</row>
        	<column>2</column>
    	</hole>
    
- Es el Connecta4 en lugar del TicTacToe.

## Second state

- Misma crítica que antes

