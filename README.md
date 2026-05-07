Changelog:
    Se han realizado ajustes en las físicas y parámetros cinemáticos del juego con el objetivo de incrementar la dificultad general y requerir un menor tiempo de reacción. A continuación, se detallan las modificaciones respecto a la versión original:

Ajustes en la Lógica y Físicas
- Incremento de Velocidad del Proyectil: Se modificó la función tap(x, y), la cual calcula el vector de velocidad inicial de la bola al hacer clic. Al reducir el divisor matemático de la distancia, el proyectil ahora se dispara con una velocidad de salida significativamente mayor.

- Aceleración de los Objetivos: Se actualizó el ciclo de actualización dentro de la función move(). La velocidad de desplazamiento horizontal de los objetivos se triplicó, pasando de un decremento en la coordenada X de 0.5 a 1.5 por cada iteración del juego.