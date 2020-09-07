# 2. Soporte técnico

Una empresa encargada del Soporte técnico en un edificio de oficinas necesita hacer un programa para que un robot limpie todas las máquinas infectadas de diferentes tipos de virus informáticos. Se lo contrata a usted para realizar el mencionado programa en Gobstones con la siguiente representación:
* El hall del edificio se representa en la celda de la esquina Sur-Oeste.
* El hall de cada piso se representa en la celda del borde Oeste del piso en cuestión, donde los pisos son representados en una fila, desde la fila siguiente a la más al Sur hacia el Norte, tantos pisos como se indique en el hall del edificio.
* Cada piso tiene una cantidad distinta de máquinas, y la cantidad se indicará en el hall del piso.
* La cantidad de virus en una máquina puede variar, pudiendo haber entre 1 y 6 virus distintos en una misma máquina, y representandosé con entre 1 y 6 bolitas de color Rojo.
* Una indicación de que la máquina de la celda actual no tiene virus (marca de OK) se representa con una bolita Verde.

Para poder solucionar completamente el problema cuenta con las siguientes dos funciones primitivas:

```
function cantidadDePisos()
/*
    PROPÓSITO: Describe la cantidad de pisos que hay en
        el edificio.
    PRECONDICIONES: El cabezal está en el hall del edificio.
    TIPO: Número.
*/
```

```
function cantidadDeMáquinasEnElPiso()
/*
    PROPÓSITO: Describe la cantidad de máquinas en el piso
        actual.
    PRECONDICIONES: El cabezal está en el hall de uno de
        los pisos.
    TIPO: Número.
*/
```

```
function cantidadDeVirusEnLaMáquina()
/*
    PROPÓSITO: Describe la cantidad de virus que hay en la máquina actual.
    PRECONDICIONES: El cabezal está en alguna de las máquinas de un piso.
    TIPO: Número.
*/
```

> ### Atención:
> Realizar también en máquina completando los procedimientos  dados y probar que
> funcione para todos los edificios ya armados en los tableros propuestos.


> **Autores**
>
> Esta actividad fue diseñada por la profesora Valeria De Cristófolo de la UNQ,
> modificado y mejorado por el docente Andrés Atencio de UNaHur y los auxiliares
> académicos Emiliano Churruca y Alberto Sánchez.