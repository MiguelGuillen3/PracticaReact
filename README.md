Programa TicTacToe

La funcion Square se encarga principalmente de establecer que cada vez que se haga un click en el juego, en este se renderizara un cuadrado y a su vez se rellenara con "X" o "O" dependiendo al jugador que le este tocando.

La funcion Board se encarga de factorizar las funciones que hacia "Square", ademas de calcular los turnos para cada jugador y a su vez calcula el ganador a traves de los clicks que los jugadores van haciendo.

La funcion Game se encarga de hacer un historial de las jugadas que se van haciendo durante todo el proceso, y asimismo tambien habilita para poder regresar en el tiempo a la jugada anterior y asi repetir otra vez todo el juego TicTacToe.

La funcion calculateWinner, como establece su nombre toma el "const" de la funcion Board y establece cual es el jugador que ha terminado ganando el juego.