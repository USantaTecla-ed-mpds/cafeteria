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

![connect4](../docs/images/conecta4.jpg)  

[WIKI](https://es.wikipedia.org/wiki/Conecta_4)

[Youtube](https://www.youtube.com/watch?v=JBSbiilzg9U)


### vocabulary

1. El uso de la interfaz no es correcta debido a que una interfaz solo define operaciones para un conjunto de clases que comparte funcionalidades, pero implementaciones distintas, en este caso no aplica.

2. El jugador está asociado a objetivo y el objetivo cambia en función del estado de la partida, pero el jugador no agrega nuevos objetivos, únicamente itera entre los tres existentes, por lo cual no es una relación de agregación sino de asociación o composición.

3. Sobra la asociación entre 4InALine y Checker es redundante debido a que está definido en put.
  
### initialState  
  
1. Falta las relaciones definidas en el vocabulario.

2. Falta las clases a la que pertenece cada objeto.
  
### finalState 
1. Goal debe estar relacionado con Player
   
2. Player está asociado a Checker, sin embargo, se indica relación de uso.

### instructions  
  
![Instrucciones]()  
  
![Instrucciones]()  
  
 
