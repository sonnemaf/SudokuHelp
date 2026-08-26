# El juego
El juego contiene 106 fichas, incluidos 2 comodines. Hay fichas de 4 colores diferentes: 
negro, rojo, amarillo y verde, numeradas del 1 al 13. Todas las fichas se mezclan juntas. 
Cada jugador recibe 14 fichas al azar, que se colocan en su soporte.

## Objetivo
El objetivo es ser el primero en deshacerse de todas las fichas de su soporte formando 
escaleras y grupos con ellas, y colocándolos después sobre la mesa.
Todas las escaleras deben constar de al menos 3 fichas del mismo color y con números 
consecutivos. Una escalera con las fichas 12-13-1 no es válida.

![image](Set1.png)

Los grupos deben constar de 3 o 4 fichas de colores diferentes con el mismo número.

![image](Set2.png)

# Comodines
Un comodín puede sustituir a cualquier ficha al formar una combinación. El comodín puede 
ser sustituido por fichas que ya se hayan jugado. No puedes conservar un comodín sustituido 
para utilizarlo en un turno posterior. Puedes utilizar y reorganizar los comodines como 
quieras, sin ninguna restricción aparte de que cada ficha debe acabar formando parte de una 
combinación válida.

![image](Set3.png)

# Desarrollo del juego
Para poder colocar fichas sobre la mesa, cada jugador debe realizar una combinación inicial 
con un número mínimo de puntos, formada por uno o más conjuntos.

El número mínimo de puntos requerido es diferente en cada nivel de juego.

- Fácil -> 27
- Normal -> 30
- Difícil -> 33
- Experto -> 36

Estos puntos deben proceder únicamente de las fichas de tu mano y no de las fichas que ya 
estén sobre la mesa. Una vez que hayas colocado tus puntos iniciales, puedes jugar libremente 
en la mesa y manipular y reorganizar las combinaciones. No puedes utilizar fichas de otros 
jugadores para formar los puntos iniciales.
Si no puedes añadir fichas a ninguna de las escaleras o grupos, tuyos o de tus oponentes, 
debes coger una ficha de la mesa. Después debes esperar hasta tu siguiente turno para jugar.

# Puntuación
Una vez declarado el ganador, los jugadores perdedores deben sumar los valores de las fichas 
que les queden en sus soportes. Esta es su puntuación de la partida. El comodín tiene un valor 
de penalización de 50. La puntuación de un jugador en la partida se resta de su puntuación 
acumulada actual. A continuación, la puntuación de cada jugador perdedor en la partida se suma 
a la puntuación acumulada actual del ganador. Por ejemplo, supongamos que el jugador A gana 
una partida, el jugador B obtiene una puntuación de 5, el jugador C una puntuación de 10 y el 
jugador D una puntuación de 3. El jugador A tendrá entonces una puntuación acumulada de 18, 
el jugador B tendrá -5, el jugador C -10 y el jugador D -3. Si la partida termina sin ganador, 
el jugador que tenga menos fichas en su soporte será el ganador. La puntuación se calculará 
entonces de la manera habitual.
