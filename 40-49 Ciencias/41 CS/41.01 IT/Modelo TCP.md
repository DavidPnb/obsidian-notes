---
status:
references:
created: 2022-07-01 10:22
---
tags:: #on/IT 
up:: [[Networking]]
Links: 
# Modelo TCP/IP
Conjunto de estandares basado en el model OSI que permite la comunicación entre computadoras en una red.

El nivel inferior de la arquitectura conocido como **Acceso a la Subred** agrupa las funciones del nivel físico, enlace de datos, y parte de la red.

El nivel **Internet** corresponde al subnivel de red encargado de la interconexion entre redes. Utiliza el protocolo IP y su objetivo es conectar redes heterogeneas.

El nivel **Control de la Transmisión** corresponde al nivel de transporte del modelo OSI. Utiliza el protocolo TCP y el UDP.

El nivel **Proceso de Aplicación** es algo indefinido ya originalmente TCP se limitaba al intercambio de datos. Actualmente, estan disponibles algunos protocolos estandar para aplicaciones.

1. **Acceso a la Subred**
	- ARP
	- PPP
	- Ethernet
2. **Internet**
	- IP
	- NAT
	- ICMP
	- OSPF
	- EIGRP
3. **Transporte** 
	- UDP
	- TCP
4. **Aplicación**
	- DNS
	- DHCP
	- BOOTP
	- SMTP
	- POP
	- IMAP
	- FTP
	- TFTP
	- HTTP

### Protocolo TCP
El *Transmition Control Protocol* es uno de los protocolos mas utilizados y es el responsable de las comunicaciones a través de internet.

- Se asegura de que los datos llegan a destino
- Mas lenta y requiere mas recursos
- FTP
- Email
- Navegacion Web

### Protocolo UDP 
*User Datagram Protocol*.

- Mas rapida pero sin verificación de integridad de datos
- Streaming
- Gaming
- VoIP


___
