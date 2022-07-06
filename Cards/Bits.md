tags:: #on/IT 
up:: [[Señales Digitales]]
Links: 
# Bits
Para representar un numero en binario, al igual que sucede con un numero decimal, se usan digitos; a estos digitos en binario se les llaman bits.

![[Pasted image 20220604130628.png|300]]

## Codigos Usuales para Datos
Una caracteristica comun a todos los sistemas de transmision de mensajes hoy en dia  es que la informacion digital se envia de una manera codificada, es decir cada elemento se representa siempre de igual manera y con la misma duracion dependiendo del codigo elegido.

### Codigo ASCII
Si se quisieran mandar el abecedario con mayusculas y minusculas, numeros, signos de puntuacion y simbolos adicionales, un numero de combinaciones menor a 256 (8 bits) se quedaria corto. Por esto se usa el Codigo Estandar Americano de Intercambio de Informacion (ASCII), que puede ser de 7 o de 8 bits.

![[Pasted image 20220604132411.png|400]]

Con este codigo, ademas de los bits del mismo, cuando se realiza una transmision se suele enviar un bit de mas, llamado bit de paridad, que sirve para determinar de manera muy sencilla si se ha producido un error en la transmision. Asi pues, se puede ver nombrado como codigo ASCII de 8 bits a un codigo ASCII de 7+1 bits.

## Bytes
Habitualmente, los ordenadores manejan caracteres de 8 bits que almacenan en memoria como un caracter. Es tan importante y frecuente mandar los bits de 8 en 8 que se usa un nombre especifico para nombrar conjuntos de 8 bits: bytes.

Luego de realizar la conversion a bits se igualan todos los numeros a 8 bits. Para ello se incluyen ceros a la izquierda que no tiene ningun valor. Normalmente, se unifica el numero de bits porque es mas comodo para su tratamiento por sistemas digitales.

Con esta tecnica se pueden representar numeros negativos, decimales, etc. Por ejemplo, para los negativos se pone antes un bit como bit de signo. Si es $0$, el numero es positivo, y si es $1$, el numero es negativo. Los decimales se colocan especificando cual es la parte entera y cual es la parte decimal.
___
