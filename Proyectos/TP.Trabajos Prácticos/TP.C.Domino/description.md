# Dominó

Se desea escribir un programa capaz de jugar al dominó. No vamos a armar todo
un juego, pero nos interesa definir las bases para poder hacerlo.

En primer lugar, vamos a asociar una representación a nuestras piezas de dominó.
Para ello utilizaremos la siguiente representación:
* El tablero en su totalidad representa la mesa donde se jugará dominó
* Una ficha de dominó consiste en una celda en donde existen entre una y seis bolitas de color Rojo, y una y seis bolitas de color Verde.
* Si en una celda donde hay una ficha hay adicionalmente una y solo una bolita Azul, esto indicará que la ficha está en posición horizontal, caso contrario será vertical.
* Si la ficha está vertical, la cantidad de bolitas de color Verde representa el número de arriba.
* Si la ficha está vertical, la cantidad de bolitas de color Rojo representa el número de abajo.
* Si la ficha está horizontal, la cantidad de bolitas de color Verde representa el número de la izquierda.
* Si la ficha está horizontal, la cantidad de bolitas de color Rojo representa el número de la derecha.

Con esa representación, queremos hacer un programa que ponga en la celda actual
la pieza 6/6 en posición vertical, en la celda lindante al Este la 6/2 horizontal,
y en la lindante al Oeste la 4/6 horizontal.
