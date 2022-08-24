tags:: #concept #on/IT  
up:: [[50-59 Ingenieria/50 Telecom - CyberSec - IT/50.00 Telecom - CyberSec - IT MOC]]
Links: 
# Señales Digitales
Las [[Señales Analogicas]] son las señales que representan al mensaje. Las señales digitales son señales creadas por el hombre, totalmente artificiales, y no se parecen en nada al mensaje que quieren representar o que quieren transmitir. Estas tienen dos caracteristicas principales, la primera: solo pueden tener dos niveles o dos valores. La señal analogica, por el contrario, puede tener cualquier valor. En la señal digital solo hay dos valores de voltios: un valor alto y un valor bajo, no hay ningun valor intermedio. La ultima caracteristica es que la transicion del valor alto al valor bajo no se puede producir en cualquier momento, no es arbitrario, se tiene que producir en momentos predeterminados.

![[Pasted image 20220521102110.png|400]]

Ultimamente se utiliza mucho la transmision digital debido a que:
- La tecnologia digital se ha abaratado mucho
- Al usar repetidores en vez de amplificadores, el [[Ruido (IT)|Ruido]] y otras distorsiones no es acumulativo
- La utilizacion de banda ancha es mas aprovechada por la tecnologia digital
- Los datos transportados se pueden encriptar, y por lo tanto, hay mas seguridad en la informacion
- Al tratar digitalmente todas las señales, se pueden integrar servicios de datos analogicos con digitales como texto y otros

- **Valores de la Señal**
	- Lo normal en los valores es que el fabricante de un equipo elija los valores que le sean apropiados. No hay un estandar, hay estandares, segun los fabricantes. Cuando se tiene que unir un equipo con otro, los dos tienen que entenderse y tener adaptados sus niveles. Existe lo que se llama un protocolo y una interfaz, que garantiza la union fisica
- **Transiciones de la Señal**
	- Puede depender del fabricante, caso de un ordenador, o puede depender de un estandar internacional, caso del telefono. En el caso de un ordenador las transiciones se producen en nanosegundos pero el numero es variable
	- Para el telefono, esta estandarizado que solo se produzcan 64000 transiciones por segundo, que corresponde a una cada 15.625 microsegundos
	- Resumiendo los cambios se producen en momentos prefijados y los dos niveles dependen del fabricante. Al nivel alto le solemos llamar uno y al nivel bajo lo denominamos cero. Ni el nivel alto es un voltio, ni el nivel bajo es cero voltios, pero se adoptan estos valores por comodidad
	- ***Las señales digitales se componen de ceros y unos, en realidad, nivel alto y nivel bajo, que se alternan en momentos predeterminados***

## Conversion Analogico-Digital
La digitalizacion es el proceso que transforma una señal analogica a una digital antes de su transmision. Basicamente consiste en transformar la informacion analogica en ceros y unos, niveles altos y niveles bajos.

Para convertir una señal en analogica se necesitan tres procesos. La primera es tomar muestras a intervalos regulares, muestrear. La segundo es ver el valor de cada muestra, cuantificar. Y la tercera es convertir esa muestra a ceros y unos, codificar

### Muestreo
En el mundo digital nunca se manda toda la informacion, se mandan muestras. Al recibir la señal se tiene que recomponer la informacion uniendo los puntos de las muestras, y en este caso, lo que se reproduce no es igual a lo que se envia, se pierde tanta mas calidad cuanto menor es el numero de muestras.

En telefonia, esta perdida de calidad suele ser tolerable, ya que normalmente corresponde a sonidos agudos y en un telefono estos no se transmiten. En el telefono digital basta con 8000 muestras por segundo, se pierden detalles, pero lo conversacion es totalmente inteligible.

En el mundo de la musica se toman muchisimas mas muestras, para que al recomponer la señal esta sea mas fiel a la original. En los CDs se toman 44100 muestras por cada uno de los canales, porque se quiere mucho mas detalle; el numero de muestras esta determinado por el detalle que se quiere transmitir, obteniendo una reproduccion fiel a la original

### Cuantificacion
Luego de que se toman las muestras, se ve cuanto vale cada una para poder enviarlas como una secuencia de numeros. Para adaptarlos a un medio digital, los equipos digitales convierten esa numeracion a sistema binario.

### Codificacion
![[Pasted image 20220521110324.png]]

A esto se le llama matematica binaria, porque usa dos cifras para todas las operaciones, lo que hacen los dispositivos digitales es manejar los numeros con esta codificacion. A estas señales se les llama digitales porque utilizan numeros o digitos.

## Bits
[[Codificacion Binaria]]
___
