---
created: 2025-04-27 12:56
---
tags:: 
up:: [[42.00 Fisica]]
# Electroéstatica
Describe las interacciones entre cargas eléctricas que no estan en movimiento respecto al sistema de referencia.

```toc
```

## Carga Eléctrica y Campo Eléctrico
### Carga Eléctrica
Un cuerpo puede tener dos tipos de carga eléctrica: carga positiva y carga negativa. Los objetos con cargas opuestas experimentan fuerzas de atracción y los objetos con cargas similares experimentan fuerzas de repulsión. Estos efectos son provocados por la [[Atomos#Estructura del Átomo|estructura del átomo]]. El valor de la carga negativa del electrón es cuantitativamente igual al valor de la carga positiva del protón. Esto significa que un cuerpo con carga negativa ha ganado electrones y un cuerpo con carga negativa ha perdido electrones. La carga eléctrica de un cuerpo esta cuantizada, y la suma de las cargas eléctricas se conserva en un sistema cerrado.

### Conducción Eléctrica
Un material puede clasificarse por su capacidad para conducir la carga eléctrica. Un **conductor** tiene electrones libres que pueden moverse por el material, distribuyendo uniformemente la carga eléctrica. Un **aislante** no contiene electrones libres, y la carga eléctrica se mantiene en un sector aislado. Un **semiconductor** puede cambiar sus propiedades si se le agrega cierta cantidad de átomos. La **conducción** es el proceso en el cual dos objetos con carga neutra adquieren carga eléctrica al frotarse entre ellos. En la **inducción** se acerca un objeto cargado a uno neutro, alterando la distribución de electrones del último.

### Ley de Coulomb
Una **carga puntual** representa un objeto con una carga eléctrica como un punto en el espacio. La ley de Coulomb establece que la fuerza eléctrica entre cargas puntuales es proporcional a la magnitud de cada carga e inversamente proporcional al cuadrado de las distancias. La fuerza eléctrica es conservativa y obedece las leyes de Newton. 

$$F = \frac{k_{e}|q_{1}||q_{2}|}{r^{ 2 }}$$

$$k_{e}= 9\times10^{ 9 }N \frac{m^{2}}{C^{2}}$$

La **fuerza eléctrica total** ejercida sobre una carga puntual equivale a la suma de las fuerzas ejercida por cada carga.

### Campo Eléctrico
El **campo eléctrico** es producido por una **fuente eléctrica**, y ejerce una fuerza sobre cualquier partícula cargada que este dentro de él. El **vector de campo eléctrico** en un punto determinado se define como la fuerza eléctrica que experimenta una **carga de prueba** positiva en el punto, dividida entre la carga de prueba. La carga de prueba debe ser una carga puntual. El **campo eléctrico neto** en un punto es igual a la suma de los campos generados por cada fuente. Una carga positiva experimenta una fuerza en el mismo sentido que el campo eléctrico, una carga negativa experimenta una fuerza en sentido opuesto al campo eléctrico.

$$\mathbf{F_{e}} = q \mathbf{E}$$
es una definición alternativa de fuerza eléctrica.

$$\mathbf{E}=\frac{k_{e}q}{r^{3}} \mathbf{r}$$

$$ \mathbf{E}=k_{e} \Sigma\frac{q_{i}}{r_{i}^{3}} \mathbf{r_{i}}$$

### Distribución de Carga Continua
Cuando la distancia entre un conjunto de cargas es considerablemente menor a la distancia a un punto, estas cargas pueden modelarse como una carga distribuida en una región continua.

$$ \mathbf{E}=k_{e}\lim_{ \Delta q_{i} \to 0 }  \Sigma\frac{\Delta q_{i}}{r_{i}^{3}} \mathbf{r_{i}}= k_{e}\int  \, \frac{dq}{r^{3}}\mathbf{r} $$
$$\sigma=\frac{Q}{A}$$

$$
\rho = \frac{Q}{V}
$$

$$
\lambda = \frac{Q}{l}
$$

### Líneas de Carga Eléctrica
Son una forma gráfca de representar los vectores de un campo eléctrico. Las líneas tiene la dirección y sentido del campo eléctrico en el punto. La cantidad de lineas en un área representa la magnitud del campo eléctrico. La cantidad de líneas que salen de una carga positiva es $Nq_{1}$, la cantidad de líneas que entran a una carga negativa es $N|q_{2}|$. Las líneas de campo eléctrico no pueden intersectarse.

![[Campo de carga puntual.png]]

![[Campo de un dipolo.png]]

![[Campo 3.png]]

![[Campo 4.png]]

## Ley de Gauss
### Flujo Eléctrico
El **flujo eléctrico** es una medida cuantitativa del campo eléctrico en una región del espacio. El flujo eléctrico es proporcional a la cantidad de líneas de campo eléctrico y define como la magnitud del campo eléctrico por el área. Cuando el campo eléctrico no es uniforme, el flujo eléctrico debe ser expresado por medio de una integral de superficie. Una **superficie cerrada** es una que divide el espacio en una región interior y una región exterior. El flujo eléctrico neto a través de una superficie cerrada es igual al número de líneas que entran menos el número de líneas que salen.

$$
\Phi_{E}=EA \cos \theta
$$

$$
\Phi_{E}=\int \mathbf{E} \cdot d \mathbf{A} 
$$

$$
\Phi _{E} = \oint \mathbf{E} \cdot d\mathbf{A} = \oint E_{N}  dA
$$


### Ley de Gauss
El flujo eléctrico producido por una carga en el interior de una superficie cerrada es igual para cualquier forma y dimensión. Cuando hay multiples cargas en el interior de la superficie, el flujo eléctrico dependera únicamente de la carga eléctrica neta. El signo del flujo eléctrico dependera del signo de la carga. El flujo eléctrico en una superficie cerrada sin cargas en su interior siempre es igual a cero. La ley de Gauss puede usarse para determinar la magnitud del campo eléctrico usando una superficie imaginaria. La superficie debe cumplir una o más de las siguientes condiciones:
1. El ángulo entre el campo eléctrico y la superficie es constante
2. El campo eléctrico es constante en la superficie

$$
\Phi _{E} = \oint \mathbf{E} \cdot d\mathbf{A} = \frac{ \sum q_{in}}{\epsilon_{0}}
$$

### Conductores en Equilibrio Electrostático
El **equilibrio electrostático** es una situación donde no existe movimiento de electrones. Un conductor en equilibrio electrostático presenta las siguientes propiedades:
1. El campo en el interior de la superficie es cero (el potencial es constante)
2. La carga se mantiene en el exterior de la superficie
3. El campo electrico justo en el exterior es $\frac{\sigma}{\epsilon_{0}}$
4. En una superficie irregular, $\sigma$ es menor en los lugares donde el radio de curvatura es mayor
La primera propiedad se da porque se mantiene una distribución de cargas que garantiza el equilibrio electrostático. La segunda y tercera son el resultado de la ley de Gauss. La cuarta es producto del potencial eléctrico

## Potencial Eléctrico
La fuerza eléctrica es una fuerza conservativa, por lo tanto, el trabajo aplicado por la fuerza eléctrica proviene de una reducción en la energía potencial eléctrica. El **potencial eléctrico** es una propiedad del campo eléctrico y se define como la diferencia de energía potencial eléctrica de una carga de prueba en dos puntos entre la carga de prueba. El potencial eléctrico se mide en voltios ($V=\frac{J}{C}$). El campo eléctrico es la tasa de cambio del potencial eléctrico respecto a la posición. Este también puede medirse en voltios por metro ($\frac{V}{m}$).

$$
\Delta U_{e}=-q_{0} \int_{A}^{B} \mathbf{E} \, d\mathbf{r} 
$$
$$
V=\frac{U_{e}}{q_{0}}
$$

$$
\Delta V = -\int_{A}^{B} \mathbf{E} \, d\mathbf{r} 
$$
$$
\mathrm{V} = \frac{J}{C}
$$

### Potencial Eléctrico en Campo Uniforme
En un campo eléctrico uniforme, las expresiones matemáticas del potencial eléctrico se simplifican. El potencial eléctrico se reduce en la dirección del campo eléctrico. Una carga positiva provoca una disminución de la energía potencial eléctrica del sistema al moverse en la dirección del campo eléctrico; lo que significa que la fuerza eléctrica realiza trabajo positivo. Si una carga negativa se mueve en dirección del campo eléctrico, aumenta la energía potencial eléctrica. Para que una carga negativa se mueva en dirección del campo eléctrico, una fuerza externa debe realizar trabajo positivo. Una **superficie equipotencial** es una superficie continua donde todos los puntos tienen el mismo potencial eléctrico. La superficie equipotencial de un campo uniforme es un plano perpendicular al campo eléctrico.

$$
\Delta V = - \mathbf{E} \cdot \, \mathbf{r} 
$$

$$
\Delta U_{e} = -q_{0} \mathbf{E} \cdot \mathbf{r}
$$

### Potencial por una Carga Discreta
El potencial eléctrico por una carga discreta depende únicamente de la distancia. En caso de haber varias cargas se usa el principio de superposición. El campo eléctrico es considerado un **campo conservativo** por estar asociado a una fuerza conservativa. La distancia para la cual $V= 0$ se toma como $r= \infty$. La energía potencial eléctrica de un par de cargas es equivalente al trabajo necesario para mover una carga desde infinito hasta su posición actual. En caso de haber más, se suma la energía potencial por cada par de cargas.

$$
\Delta V=- k_{e}\int_{A}^{B} \frac{Q}{r^{2}}\mathbf{r_{P/Q}} \, d\mathbf{r} = \frac{k_{e}Q}{r_{A}} - \frac{k_{e}Q}{r_{B}}
$$
$$
V= k_{e} \Sigma\frac{q_{i}}{r_{i}}
$$

$$
U_{e}=\frac{k_{e}q_{1}q_{2}}{r}
$$

### Campo Eléctrico a partir de Potencial Eléctrico
El valor del campo eléctrico es igual a la derivada del potencial eléctrico respecto al desplazamiento. El campo eléctrico es cero en lugares donde el potencial eléctrico es constante. A partir de este resultado se puede deducir que las líneas de campo son perpendiculares a una superficie equipotencial. Las superficies equipotenciales de una carga puntual son superficies esféricas concéntricas.

![[Superficies Equipotenciales.png]]

$$
E_{x_{i}}= -\frac{dV}{dx_{i}}
$$
$$
\mathbf{E} = -\frac{ \partial V }{ \partial x }\mathbf{i} -\frac{ \partial V }{ \partial y }\mathbf{j} - \frac{ \partial V }{ \partial z }\mathbf{k} 
$$
### Potencial por una Carga Continua
El potencial eléctrico por una carga continua es obtenido integrando el potencial eléctrico respecto a un diferencial de carga. Este también puede ser obtenido usando la ley de Gauss. Esto es especialmente util para distribuciones de carga infinita.

$$
V = k_{e}\int  \, \frac{dq}{r} 
$$

### Potencial en Conductores Eléctricos
Ya que la carga eléctrica de un conductor se acumula en su superficie, la superficie de un conductor en equilibrio electrostático es una superficie equipotencial. El potencial eléctrico en el interior del conductor es constante y su valor es igual al de la superficie. Por lo tanto, dos conductores conectados comparten el mismo potencial eléctrico. El campo eléctrico cercano a una superficie conductora es inversamente proporcional al radio de curvatura. En una superficie conductura con una cavidad, el campo dentro de la cavidad debe ser igual a cero siempre que no existan cargas en la cavidad.
___
