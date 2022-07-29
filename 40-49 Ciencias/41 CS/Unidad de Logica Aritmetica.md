---
alias: ["ALU"]
status:
references:
created: 2022-07-28 16:33
---
tags:: #on/CS 
up:: [[Arquitectura de Computadoras]]
Links: 
# Unidad de Logica Aritmetica
La Unidad de Logica Aritmetica es una de las partes más esenciales de las [[Computadoras]], encargandose de realizar todas las operaciones logicas y matematicas. Esta compuesta por dos unidades diferentes: La **aritmetica** y la **logica**, que a nivel fisico dependen de una serie de compuertas logicas acomodadas de forma especifica

## Unidad Aritmetica
Realiza las operaciones aritmeticas como sumas y restas utilizando [[Codificacion Binaria]], al igual que otras operaciones como incrementos o decrementos. 

Las unidades logicas más complejas tienen series de compuertas diseñadas de forma especifica para la multiplicación; por otro lado, los aparatos más simples como dispositivos IOT dependen de adición repetida para hacer multiplicaciones, lo que hace que tarden más tiempo. Este  cambio en la eficiencia del tiempo de computo es una de las causas de la diferencia de precios en CPUs.

Cuando uno de estas operaciones produce un resultado con mayor numero de bits que los que se pueden representar, se produce un **integer overflow**, provocando errores y comportamiento inesperado. Estos son bastante frecuentes en los videojuegos antiguos, que dependian de hacer que el juego cupiera en una cantidad muy pequeña de memoria.

## Unidad Logica
La unidad logica se encarga del operaciones logicas más fundamentales, como AND, OR, NOT, etc.. Ademas maneja las operaciones de comparación y de validación, devolviendo **valores booleanos** en forma de ceros y unos.
___
