---
status:
references:
created: 2022-07-29 12:39
---
tags:: #on/CS  #on/IT 
up:: [[Networking]]
Links: 
# Modelos y Protocolos de Red
Los modelos describen el diseño usado para describir la comunicación entre dispositivos. Los protocolos determinan como se transmiten los datos entre dispositivos.

## Modelo OSI
Es una estructura conceptual que describe el flujo de datos a traves de una red compuesta de 7 capas:
1. **Fisica** - Trasmite los datos físicamente mediante electricidad o luz
2. **Enlace de Datos** - Define el formato de los datos en la red. Se encarga del encapsular paquetes de datos
3. **Red** - Interpreta las direcciones e indica el camino que tomaran los datos. Trabaja con segmentos o *frames*
4. **Transporte** - Transporta y verifica la integridad de los datos. Generalmente por TCP
5. **Sesion** - Maneja la información entre distintas computadoras y se encarga de autenticar los datos
6. **Presentacion** - Se asegura que los datos estan en un formato usable y encripta la información
7. **Aplicacion** - Es la que interactua directamente con el usuario

## Protocolos TCP/IP
[[Modelo TCP]]

## Protocolos IOT
1. **Fisica**
2. **Enlace de Datos**
	- Zigbee
	- BLE
	- Wi-fi
	- LoRa
	- NFC
	- Celular
	- Zwave
3. **Red**
	- IPv4
	- IPv6
	- IPsec
	- ICMP
	- 6LowPAN
4. **Transporte** 
	- UDP
	- TCP
5. **Aplicación**
	- HTTP
	- MQTT
	- CoAP
	- AMQP
	- XMPP

## Protocolos Cripto
Metodos de pago seguro construidos sobre la red Blockchain.
- **Protocolo Blockchain** - Una forma abierta y distribuida de registrar transacciones de manera permanente y verificable
___
