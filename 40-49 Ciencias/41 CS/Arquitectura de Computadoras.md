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

- [[Memoria RAM]] - Almacena la informacion a corto plazo
- [[Memoria de Almacenamiento]] - Almacena información a largo plazo
- [[CPU]]
	- [[Unidad de Logica Aritmetica]] - Realiza operacion primitivas
	- Unidad de Control - Controla el orden de operaciones
- Input - Informacion que se pone en la maquina
- Output - Informacion que sale de la maquina 

[[Maquina de Turing]]

## Compuertas Logicas
Son usadas para controlar la forma en que la corriente fluye por los circuitos para dar instrucciones a una computadora. Depende del algebra booleana y se componen principalmente de compuertas:
- NOT
- AND
- OR
- XOR

## Circuitos Integrados y PCB
Los **circuitos integrados** juntan varios componentes discretos (Transistores) en un solo componente, reduciendo los costos y aumentando la capacidad de los aparatos electrónicos. Las PCB o **placas madre** tienen un objetivo similar, agrupando grandes circuitos en un espacio más reducido.

### Ley de Moore
Es un enunciado que predice que cada dos años se duplica la cantidad de transistores en un circuito integrado, abaratando los precios y aumentando la potencia de los dispositivos. Expertos predicen que esto quedara obsoleto en el futuro reciente, debido a ciertas limitaciones que no nos dejaran reduciendo el tamaño de los circuitos.
___
