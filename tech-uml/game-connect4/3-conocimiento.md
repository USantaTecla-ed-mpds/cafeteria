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

![connect4](./docs/images/conecta4.jpg)  

[WIKI](https://es.wikipedia.org/wiki/Conecta_4)

[Youtube](https://www.youtube.com/watch?v=JBSbiilzg9U)


## Críticas   


###  lab-turing

  * [domainModel](#domainModel)  
    * [vocabulary](#vocabulary)
    * [initialState](#initialState)  
    * [finalState](#finalState)
    * [instructions](#instructions)

### lab-dijkstra 

  * [domainModel](#domainModel)  
    * [vocabulary](#vocabulary)
    * [initialState](#initialState)  
    * [finalState](#finalState)
    * [instructions](#instructions)

    
###  lab-lovalace 

  * [domainModel](#domainModel)  
    * [vocabulary](#vocabulary)
      * Las clases tienen que estar en singular
      * Jerarquía de clasificación incorrecta, Pieces no comparte caracteristicas con Board y Color no comparte caracteristicas con Piezes, tienen una relación de  composición. 
      * Falta relación de  asociacion con Player y Pieces 
      * Turn no tiene una asociación directa y publica con Goal, la asociación debe estar entre Player y Turn
    </ol>

    * [initialState](#initialState)  
    * [finalState](#finalState)
    * [instructions](#instructions)

    
###  lab-chomsky
   Al principio tratar con los repositorios y entender realmente qué son es duro. ¡Ánimo!
  * [domainModel](#domainModel)  
    * [vocabulary](#vocabulary)  
        El segundo diagrama (plantUML) está mucho mejor. Voy a comentar cosas del primero:
     **Se abusa muchísimo de la composición** y creo que se confunden ella y la agregación con la herencia (en goal está el mejor ejemplo; también en color).
     Creo que **en general hay un problema bien de UML o bien de conceptualización**. Lo más probable que sea de entender qué quiere decir cada tipo de flecha de UML.  
      **Las clases están escritas en minúscula**.Debería ser mayúscula.  
      Del segundo:  
      **No termino de ver la cardinalidad de Conecta4 y Player hacia Turn**. Si se entiende Turno como la entidad que controla a quién le toca, entonces solo hay una. Sin embargo, si se entiende como cada turno, entonces el jugador no tiene uno. Además, un movimiento no se compone de un turno; en todo caso al revés. Puede que haya sido un error de dónde colocar el rombo.   
     Seguro que las clases ayudan a mejorarlo y en las siguientes ya se ve más claro. Al principio siempre es difícil. 😊  
    * [initialState](#initialState)  
    **Nunca había visto un diagrama de objetos donde se simbolice, mediante composición, a qué clase pertenece un objeto**. Lo señalo porque me ha sorprendido mucho, no me parece que esté correcto pero quizá es algo que yo no sabía.  
    **Falta el tipo de asociación entre Player2 y PieceRed**.  
    **Que Movement se componga de tres objetos pero nadie se asocie con él es raro**. Sería una instancia perdida a la que nadie tendría acceso. ¿Entiendo que sería el Player1 el que tiene al Movement o bien se asocia con él?
    * [finalState](#finalState)  
    Similar a lo anterior.
    * [instructions](#instructions)

 
 ###  lab-boole

  * [domainModel](#domainModel)  
    * [vocabulary](#vocabulary)  
    * [initialState](#initialState)  
    * [finalState](#finalState)
    * [instructions](#instructions)
