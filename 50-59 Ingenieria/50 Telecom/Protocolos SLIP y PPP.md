---
status:
references:
created: 2022-07-15 09:43
---
tags:: #on/IT 
up:: [[Networking]]
Links: 
# Protocolos SLIP y PPP
Son dos protocolos muy populares para las conexiones entre los usuarios y los proveedores de Internet. Tambien se usan para conectar routers en una subred.
- **SLIP** - *Serial Line IP*
	- No tiene detección de errores
	- Solo soporta IP
	- Solo funciona sobre lineas no sincronizadas
	- Cada extremo debe saber previamente la dirección IP del otro
	- No tiene sistema de autenticación
	- Muy poco conocido
	- Tiene problemas de compatibilidad
- **PPP** - *Point to Point Protocol*
	- Tiene un sistema de tramas, que distingue el comienzo y final de una trama y provee manejo de errores
	- Puede operar sobre lineas síncronas y asíncronas
	- Tiene un metodo para negociar opciones a nivel de red, independiente del protocolo de red usado
___
