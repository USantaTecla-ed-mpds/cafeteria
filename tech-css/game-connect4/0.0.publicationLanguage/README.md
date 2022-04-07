# game-connect4.0.0.publicationLanguage
Universo Santa Tecla  
[uSantaTecla@gmail.com](mailto:uSantaTecla@gmail.com)  
  
## requirements 

* Escribe con un lenguaje de publicación (html/css, svg, ...) un tablero lo "más" parecido posible a la siguiente imagen

![connect4](../docs/images/conecta4.jpg) 


## Críticas   


###  lab-turing


### lab-dijkstra 


    
###  lab-lovalace 



    
###  lab-chomsky
1. El enlace externo debe tener la ruta absuluta o relativa delante del fichero css por ejemplo href="./connect4.css" para evitar confunsión.
2. Incorrecto valor en la propiedad grid-template-areas
3. Alta probabilidad de colisión de estilos por especificidad debido a estilos con selector de nombre o pseudo-elemento, por ejemplo usas el selector "table, th, td" si a futuro se añade otra tabla con otros estilo existe colisión.