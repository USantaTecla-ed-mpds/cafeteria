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
vocabulary

1º Yellow y Red es un valor de Disk no tiene un comportamiento distinto por ser amarillo o rojo, usar un enumerado para resaltarlo si es significante en el diagrama.
2º La relación de composición entre Disk y Goal es incorrecta porque indicas que un disco esta unido de forma privada, duradera e inherente a un objetivo, lo correcto es una relacion de uso ya que que un objetivo utiliza un disco para cumplir una labor.

initialState

Nada que destacar.

finalState

1º Incoherencia respecto al diagrama de clases, el turn no es compuesto de connect4, quien es compuesto de connect4 es player.
2º Player esta asociado a turno.
3º Parece más un diagrama de clases que de estados, no representa el estado final de una partida solo se indica las relaciones de los objetos.


[WIKI](https://es.wikipedia.org/wiki/Solitario_de_cartas)

[Youtube](https://www.youtube.com/watch?v=yjgQXcFVBQY)





  
