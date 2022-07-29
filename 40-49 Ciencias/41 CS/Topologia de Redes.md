---
status:
references:
created: 2022-07-29 12:35
---
tags:: #on/IT #on/CS 
up:: [[Networking]]
Links: 
# Topologia de Redes
Es lo que define la estructura de una red y la forma en que se conectan sus dispositivos. Se escoge dependiendo de las necesidas especificas del grupo que instala la red.

- **Topologia Fisica** - Describe como los dispositivos de la red estan conectados fisicamente
- **Topologia Logica** - Describe como los datos fluyen a traves de la red

## Tipos de Topologia Fisica
- **Estrella** - Implenta una computadora central que actua como centro
	- Cada dispositivo se conecta a la computadora central con un cable dedicado
- **Anillo** - Conecta a los dispositivos en un patron de anillo circular, donde los datos fluyen en una direccion
	- Cada dispositivo recibe y pasa los datos, hasta que llegan al destinatario
- **Bus** - Conecta a todos los dispositivos con un solo cable
	- El cable funciona como un canal compartido de comunicacion que los dispositivos pueden usar sin un dispositivo de conexion separado
- **Arbol** - Combina las caracteristicas de Bus y Estrella
	- Las computadoras estan conectadas a traves de un sistema jerarquico
- **Mesh** - Conecta todos los dispositivos entre si
	- Usa *routing dinamico* para encontrar el camino mas corto entre los dispositivos
___
