---
status:
references:
created: 2022-06-16 12:25
---
tags:: #on/CS  #on/IT 
up:: [[Computadoras]]
Links: 
# Arquitectura de Computadoras
En el pasado, la mayoria de computadoras primitivas estaban diseñadas para cumpir una tarea en especifico debido a las obvias limitaciones en la tecnologia de aquel. Las mas antiguas eran de naturaleza analoga, es decir, no dependian de electricidad y en su lugar usaban mecanismos complejos como un reloj. Entre estos estan las primeras calculadoras y la computadora de Gabbage. Esta jamas fue construida, pero seria la base para las computadoras de proposito general que se inventaron despues.

Las computadoras actuales ya no poseen estas limitaciones, lo que nos ha permitido fabricar computadoras de proposito general, que pueden almacenar programas en memoria para su posterior ejecucion, extendiendo enormemente sus capacidades.

A comienzos del siglo XX el desarrollo de aparatos electromecanicos estaba en su apogeo. El principal problema con estos es que ocupaban mucho espacio y dependian de reles, lo que los hacia lentos y dificiles de mantener. A mediados de 1940, los tubos de vacio se harian lo suficientemente baratos como para ser una alternativa viable. Aun asi, seguian siendo fragiles y podian quemarse como una bombilla comun. No fue hasta el invento del transistor que las computadoras empezaron a reducir su tamaño en un enorme porcentaje y mejorar por mucho su capacidad para realizar operaciones. Actualmente, los transistores miden nanometros y permiten realizar operaciones millones de veces por segundo.

## Arquitectura Basica

```nomnoml
[Memoria] -> [Unidad de Control]
[Memoria] -> [Unidad de Logica Aritmetica]
[Unidad de Control] -> [Memoria]
[Unidad de Logica Aritmetica] -> [Memoria]
[Unidad de Control] -> [Unidad de Logica Aritmetica]
[Unidad de Logica Aritmetica] -> [Unidad de Control]
[Input] -> [Unidad de Control]
[Unidad de Logica Aritmetica] -> [Output]
```

- Memoria - Almacena la informacion
- [[Unidad de Logica Aritmetica]] - Realiza operacion primitivas
- Unidad de Control - Controla el orden de operaciones
- Input - Informacion que se pone en la maquina
- Output - Informacion que sale de la maquina 

Alan Turing demostro que se puede computar cualquier cosa computable por medio de solo 6 operaciones primitivas: 
- mover hacia la izquierda
- mover hacia la derecha
- escanear
- leer
- borrar
- no hacer nada

A esto se le llama maquina de turing y es la base para practicamente todos los lenguajes de programacion modernos. Esto significa que cualquier cosa que es computable en un lenguaje de programacion es computable en otro, ya que ambos son Turing completos.

## Compuertas Logicas
Son usadas para controlar la forma en que la corriente fluye por los circuitos para dar instrucciones a una computadora. Depende del algebra booleana y se componen principalmente de compuertas:
- NOT
- AND
- OR
- XOR
___
