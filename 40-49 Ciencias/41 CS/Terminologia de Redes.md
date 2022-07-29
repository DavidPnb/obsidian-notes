---
status:
references:
created: 2022-06-24 11:22
---
tags:: #on/CS  #on/IT 
up:: [[Networking]]
Links: 
# Terminologia de Redes
Toda la información que fluye en una red es divida en **paquetes** para ser enviada a otros dispositivos. Tambien se les llama *frames*, bloques, celdas o segmentos.

## Tipos de Flujo de Transmisión de Datos
- **Simplex**- Comunicación Unidireccional
- **Half-Duplex** - Comunicación Bidireccional Síncrona
- **Full-Duplex** - Comunicación Bidireccional Asíncrona

## Modos de Transmisión
[[Modos de Transmision de Red]]

## Flujo de Transmisión de Datos
Cuando se envia información, esta es divida en paquetes identificados individualmente. Estos no llegan al destino en un orden fijo, en su lugar son compilados en el orden correcto para producir el mensaje original.

## Dirección IP
Es usado para identificar logicamente cada dispositivo de una red

- **IPv4** - Protocolo principal de Internet
	- 4 300 000 000 direcciones IP
	- 32 bits - 4 bytes
	- 4 campos separados por puntos, con un maximo de 255 en cada campo
- **IPv6** - Protocolo mas reciente de Internet
	- $34 \times 10^{37}$ direcciones IP
	- 128 bits - 6 bytes
	- 8 campos separados por dos puntos *:*, con valores representados por numeros hexadecimales
	- Los primeros 5 campos son el prefijo global, el campo 6 representa la subred y los 2 ultimos campos indican la ID de la interfaz

### Tipos de Dirección IP
- **Estatica** - Asignada manualmente
- **Dinamica** - Asignada automaticamente

- **Publica** - Se usa para conectarse al Internet
- **Privada** - Conecta con otros dispositivos en la red local

- **Loopback** - Rango de direcciones reservadas para el host local
- **Reservados** - Reservados por la IETF y la IANA

## DNS
El *Domain Name System* permite asociar direcciones IP a nombres de dominio faciles de recordar por el usuario. El cliente se conecta al servidor DNS a traves del nombre del dominio, este busca la dirección IP asociada y la envia de regreso al cliente.

## DHCP
El *Dinamic Host Configuration Protocol* automatiza la asignación de direcciones IP a dispositivos de red. Usa un pozo de direcciones IP reservadas para automatizar la asignacion de IPs dinamicas o para asociar permanentemente una dirección IP a un dispositivo.

- **Alocación Estática** - El servidor usa una dirección IP permanente manualmente asignada para un dispositivo
- **Alocación Dinámica** - El servidor escoge que direccion asignar a un dispositivo cada vez que se conecta
- **Alocación Automática** - El servidor asigna una direccion IP permanente de forma automatica

## Subnetting
Es el proceso de tomar una red grande y dividirla en varias subredes individuales mas pequeñas. Esto para mejorar el trafico interno de la red. Cada mascara de subred identifica el limite entre la red IP y el host IP. Estas mascaras son usadas por routers para enviar los datos a el lugar correcto de una red.

## APIPA
El *Automatic Private IP Adressing* es una caracteristica de sistemas operativos como Windows, que permite la asignación de una dirección IP y mascara de subred para su uso en una red privada, cuando no esta disponible un servidor DHCP.

## NAT
La *Network Adress Translation* es un proceso que asigna multiples direcciones IP privadas a una sola dirección IP publica antes de transferir la información. Es usada por routers para mejorar la seguridad de la red, actuando de intermediario entre los dispositivos y el internet.

## Dirección MAC
[[Direccion MAC]]
___
