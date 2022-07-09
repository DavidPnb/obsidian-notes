---
alias: ["Redes"]
status:
references:
created: 2022-06-09 12:04
---
tags:: #on/CS #on/IT 
up:: [[Ciencias de la Computacion MOC]]
Links: 
# Networking
Una red de [[Computadoras]] permite que dos o mas dispositivos electronicos puedan conectarse entre si, de modo que los usarios puedan comunicarse y compartir recursos.

## Tipos de Redes
- **PAN** - Permite la comunicacion entre los dispositivos alrededor de una persona
	- Personal Area Network
	- Pueden ser alambricas o inalambricas
	- Su rango va desde varios centimetros a varios metros
	- USB
	- Infrarojos
	- Bluetooth
- **LAN** - Es un grupo de computadoras y perifericos que comparten informacion con un servidor
	- Local Area Network
	- Estan limitas a areas localizadas como oficinas y edificios
	- Requieren cables, switches y routers
- **MAN** - Estan optimizadas para un area geografica mayor que una LAN
	-  Metropolitan Area Network
	- Pueden conectar desde varios edificios hasta una ciudad completa
	- Generalmente estan formadas por varias LAN
- **WAN** - Es una red que se extiende sobre una gran area geografica
	- Wide Area Network
	- Pueden ser usadas por negocios, gobiernos o universidades
- **WLAN** - Es una red que conecta dos o mas dispositivos a traves de una conexion inalambrica para formar una LAN
	- Wireless Local Area Network
	- Tambien puede conectarse al Internet a traves de un dispositivo de puerta de enlace
- **VPN** - Establece una conexion privada entre varias redes publicas
	- Virtual Private Network
	- Encriptan el trafico de Internet en tiempo real

## Topologia
Es lo que define la estructura de una red y la forma en que se conectan sus dispositivos. Se escoge dependiendo de las necesidas especificas del grupo que instala la red.

- **Topologia Fisica** - Describe como los dispositivos de la red estan conectados fisicamente
- **Topologia Logica** - Describe como los datos fluyen a traves de la red

### Tipos de Topologia Fisica
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

## Tipos de Conexion
### Conexion Cableada
Depende de Cables.
- **De Marcado o Dial-Up** -  Depende de la conexion telefonica y no se puede usar el internet y el telefono a la vez
	- Requiere un modem
	- Bajo costo
	- Muy baja velocidad
- **ISDN** - Transmite digitalmente los datos por el telefono de forma simultanea
- **DSL** - Usa un cable separado de la red telefonica
	- No interviene con los telefonos
	- Puede proveer Wi-Fi
	- Medio costo
	- Cortas distancias
	- Velocidad media (< 100 Mbit/s)
- **Cable** - Usa el mismo tipo de cable que un televisor
	- Medio costo
	- Velocidad alta
	- Largas distancias
	- Susceptible a interferencia electromagnetica
- **Fibra Optica**
	- Alto costo
	- Baja disponibilidad
	- Velocidad maxima (200Gbit/s)

### Conexion Inalambrica
No depende de cables.
- **WPAN** - Conecta dispositivos en un corto rango
	- Bluetooth - Permite conexiones inalambricas de corta distancia y poco consumo
	- NFC - Metodo de transferencia de datos entre dispositivos compatibles que no necesita conexion a internet
	- RFID - Utiliza emparejamiento electromagnetico para identificar dispositivos
- **WLAN** - Conecta dos o mas dispositivos usando un metodo de distribucion inalambrica
	- Wi-Fi - Señal de radio enviada desde un router a otros dispositivos
- **WMAN** - Conecta varias WLAN
	- WIMAX - Alternativa inalambrica de banda ancha al cable y DSL
- **WWAN** - Conecta areas grandes como vecindarios o ciudades
	- LTE - Estandar de 4G soportado por GSM y CDMA
	- Celular - Red basada en areas con torres celulares que permite conexion via satelite

## Terminologia
[[Terminologia de Redes]]

## Modelos y Protocolos
Los modelos describen el diseño usado para describir la comunicación entre dispositivos. Los protocolos determinan como se transmiten los datos entre dispositivos.

### Modelo OSI
Es una estructura conceptual que describe el flujo de datos a traves de una red compuesta de 7 capas:
1. **Fisica** - Trasmite los datos físicamente mediante electricidad o luz
2. **Enlace de Datos** - Define el formato de los datos en la red. Se encarga del encapsular paquetes de datos
3. **Red** - Interpreta las direcciones e indica el camino que tomaran los datos. Trabaja con segmentos o *frames*
4. **Transporte** - Transporta y verifica la integridad de los datos. Generalmente por TCP
5. **Sesion** - Maneja la información entre distintas computadoras y se encarga de autenticar los datos
6. **Presentacion** - Se asegura que los datos estan en un formato usable y encripta la información
7. **Aplicacion** - Es la que interactua directamente con el usuario

### Protocolos TCP/IP
[[Modelo TCP]]

### Protocolos IOT
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

### Protocolos Cripto
Metodos de pago seguro construidos sobre la red Blockchain.
- **Protocolo Blockchain** - Una forma abierta y distribuida de registrar transacciones de manera permanente y verificable

## Estandares
Definen las leyes para el intercambio de datos y son necesario para la interoperabilidad de diversas tecnologias.
- **Formales** -  Son desarrollados por una organización o ente gubernamental
	- HTML
	- IP
	- HTTP
- **De Facto** - Resultan de un uso generalizado en un mercado o industria
	- Microsoft Windows
	- Teclados QWERTY

### Organizaciones
- **ISO** - *International Standards Organization*
	- Modelo OSI
- **ITU** - *International Telecommunication Union*
	- Estandar de telecomunicaciones internacional
- **DARPA** - *Defense Advanced Research Projects Agency*
	- Conjunto de protocolos TCP/IP
- **IEEE** - *Institute of Electronics and Electrical Engineers*
	- Estandares 802
- **W3C** - *World Wide Web Consortium*
	- Estandar www
- **IETF** - *Internet Engineering Task Force*
	- Mantiene los protocolos TCP/IP
	- Estandar RFC

## Puertos
Son los extremos de una comunicación a través de la red.
- 20
	- TCP
	- Datos FTP
- 21
	- TCP
	- Control FTP
- 22
	- TCP
	- SSH
- 23
	- TCP
	- Telnet
- 25
	- TCP
	- SMTP
- 53
	- TCP - UDP
	- DNS
- 67 - 68
	- UDP
	- DHCP
- 69
	- UDP
	- TFTP
- 80
	- TCP
	- HTTP
- 110
	- TCP
	- POP3
- 161
	- UDP
	- SNMP
- 443
	- TCP
	- SSL
- 16 - 384 - 32 - 767
	- UDP
	- Voz y video RTP






___
