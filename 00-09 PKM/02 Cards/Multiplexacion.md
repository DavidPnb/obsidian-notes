tags:: #concept 
up:: [[Telecom - CyberSec - IT MOC]]
Links: 
# Multiplexacion
El concepto de multiplexacion surge cuando se trata de transmitir, simultaneamente, por un mismo canal un conjunto de señales. Hay $n$ lineas de entrada al multiplexor, y este se conecta a un demultiplexor, via una linea de transmision. Llamamos canal a cada posible conexion, y asi, la linea es capaz de llevar $n$ canales separados de voz o datos.

El multiplexor combina los datos de las $n$ entradas y las transmite sobre la linea. El demultiplexor acepta las cadenas multiplexadas, las separa y las dirige hacia las salidas correspondientes. Existen tres tecnicas de multiplexacion: division de frecuencias, division de tiempo sincrona y division de tiempo estadistica.

## Multiplexacion por Division de Frecuencia
Muchos canales de voz circulan por un unico circuito, o por un solo par de hilos, gracias a esta tecnologia que llamamos multiplexacion. Asi que esta tecnologia se llama multiplexacion por division de frecuencias o en ingles FDM, porque como se ve todas las frecuencias que viajan por el circuito estan divididas de 4 en 4KHz para cada canal. Al equipo electronico que hace posible esta tecnologia, unos armarios con tarjetas electronicas donde entran normalmente miles de conversaciones telefonicas, se le llama un multiplexor. Las siglas que se usan para los multiplexores son "MUX". Lo que tenemos en el otro extremo es un demultiplexor, que hace la funcion inversa, y lo denominamos "DEMUX"

## Separacion entre Canales
En el mundo de la radio se transmite de 50 a 5000Hz y la separacion, por lo tanto, tiene que ser mas grande. Ademas la tecnologia de la radio obliga a bastante mas separacion para evitar interferencias y por eso en la radio de onda media, el estandar para toda Europa es de 9KHz; en Estados Unidos, sin embargo, es de 10Khz de separacion de manera que todas la frecuencias de onda media en EEUU siempre acaban en un 0.

En el caso de la FM, la tecnologia de mandar en frecuencia modulada requiere una separacion todavia mayor, ademas de que en FM se esta enviando 15KHz en un canal y 15KHz en otro canal, que son 30KHz, y ademas en FM se mandan mas cosas como el nombre de la emisora y musica ambiental. Por lo tanto, la separacion es mucho mayor, es de 100KHz. Las frecuencias en FM se miden en MHz y 100Khz es una decima de MHz, de modo que en FM la separacion es de 100Khz, que es lo mismo que decir 0.1MHz, por eso las frecuencias en FM siempre tienen un decimal.

El concepto de separacion permite mandar por el mismo canal del dial de onda media muchas emisoras de radio. Por un solo canal, muchas conversaciones telefonicas. Por un solo canal muchas emisoras de FM, gracias a que van separadas en frecuencia.
___
