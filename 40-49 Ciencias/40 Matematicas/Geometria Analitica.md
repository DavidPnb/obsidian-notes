---
created: 2022-11-02 18:20
---
tags:: #Mathematics 
up:: [[40.05 Geometria]]
# Geometría Análitica
La geometría analítica es el estudio de la [[40.05 Geometria|Geometría]] utilizando un sistema de coordenadas, lo que permite usar los métodos y herramientas del [[40.02 Algebra|Algebra]].

## Vectores
En el enfoque vectorial, varios conceptos de vectores son fundamentales, como el producto punto y el producto cruz. En este contexto, los vectores pueden ser considerados una representación analítica de un segmento dirigido. A esto se le llama comunmente **vector geométrico**. Este concepto se usa mucho en la física, en donde un vector se usa para representar magnitudes que se comprenden mejor al pensar en ellas como una flecha con un origen y un extremo.

### Características de un Vector
Un vector geométrico tiene tres características
- **Módulo** - Representa la longitud del vector. Es igual a la longitud del segmento entre el origen y el extremo del vector
- **Dirección** - Esta determinada por la pendiente de la recta que contiene al vector
- **Sentido** - Una de las dos orientaciones posibles de la recta que contiene al vector

Esto contrasta con el concepto de un **escalar**, que pueden ser representados por una única magnitud.

Un vector generalmente se representa como $\overrightarrow{A}$ , usando $|\overrightarrow{A}|$ para referirse al modulo del vector. Un vector entre dos puntos se representa como  $\overrightarrow{AB}$ , donde $A$ es el origen del vector, $B$ es el extremo y $|\overrightarrow{AB} |$ es el modulo del vector.

Dos vectores son **paralelos** si tienen la misma dirección.

### Igualdad de Vectores
Dos vectores son iguales si y solo si sus características son iguales.

### Suma de Vectores
La suma geométrica de vectores se realiza usando la **regla del paralelogramo**, donde un vector se posiciona con su origen en el extremo del vector anterior, y el **vector suma** va desde el origen del primer vector hasta el extremo del último.

- **Propiedades**
	- Conmutativa
		- $\overrightarrow{A}+\overrightarrow{B}=\overrightarrow{B}+\overrightarrow{A}$
	- Asociativa
		- $(\overrightarrow{A}+\overrightarrow{B})+\overrightarrow{C}=\overrightarrow{A}+(\overrightarrow{B}+\overrightarrow{C})$
	- Existencia de elementro neutro
		- $\overrightarrow{A}+\overrightarrow{0}=\overrightarrow{A}$
	- Existencia de opuesto
		- $\overrightarrow{A}+\overrightarrow{B}=\overrightarrow{0}$
	- Monotonía de la igualdad vectorial respecto a la suma de vectores
		- $\overrightarrow{A}=\overrightarrow{B}, \overrightarrow{C}=\overrightarrow{D}\implies\overrightarrow{A}+\overrightarrow{C}=\overrightarrow{B}+\overrightarrow{D}$

### Resta de Vectores
Geométricamente, $\overrightarrow{A}-\overrightarrow{B}$ es el vector que al sumarse con $\overrightarrow{B}$ resulta en el vector $\overrightarrow{A}$ . Este vector tiene como origen el extremo de $\overrightarrow{B}$ y como extremo el extremo de $\overrightarrow{A}$ . Se calcula como $\overrightarrow{A}-\overrightarrow{B}=\overrightarrow{A}+(-\overrightarrow{B})$ , donde $-\overrightarrow{B}$ es el opuesto de $\overrightarrow{B}$.

### Producto entre un Vector y un Escalar
Produce un vector proporcional al vector original cuyo sentido depende del signo del escalar.

- **Propiedades**
	- Distributiva respecto a la suma de vectores
		- $\lambda(\overrightarrow{A}+\overrightarrow{B})=\lambda\overrightarrow{A}+\lambda\overrightarrow{B}$
	- Distributiva respecto a la suma escalar
		- $(\alpha+\beta)\overrightarrow{A}=\alpha\overrightarrow{A}+\beta\overrightarrow{A}$
	- Monotonía de la igualda vectorial respecto al producto de un escalar por un vector
		- $\overrightarrow{A}=\overrightarrow{B},\lambda=\alpha\implies \lambda\overrightarrow{A}=\alpha\overrightarrow{B}$
		- $\overrightarrow{A}=\lambda\overrightarrow{C},\alpha\overrightarrow{B}=\overrightarrow{D}\implies \overrightarrow{A}+\alpha \overrightarrow{B}=\lambda\overrightarrow{C}+\overrightarrow{D}$
	- Asociativa respecto al producto de un escalar por un vector
		- $(\alpha \beta)\overrightarrow{A}=\alpha(\beta\overrightarrow{A})=\beta(\alpha\overrightarrow{A})$
	- $\pm1*\overrightarrow{A}=\pm\overrightarrow{A}$
	- $0*\overrightarrow{A}=\overrightarrow{0}$
	- $\lambda\overrightarrow{A}=\overrightarrow{A}\lambda$

### Vectores Unitarios
Son vectores cuyo modulo es igual a uno, y por lo tanto estan caracterizados por su dirección y sentido. El vector unitario en la dirección de $\overrightarrow{A}$ , denotado como $\overrightarrow{\mu}_{A}$ , se calcula como $\frac{\overrightarrow{A}}{|\overrightarrow{A}|}$.

### Base de Vectores
Se dice que un vector $\overrightarrow{C}$ es una **combinación lineal** de $\overrightarrow{A}$ y $\overrightarrow{B}$ si $\overrightarrow{C}=\lambda_{1}\overrightarrow{A}+\lambda_{2}\overrightarrow{B}$ .

> [!teorema] Teorema de la Base (**a**)
> Cualquier vector $\overrightarrow{C}$ puede ser escrito como una combinación lineal de dos vectores no nulos y no paralelos $\overrightarrow{A}$ y $\overrightarrow{B}$ que esten el mismo plano

> [!teorema] Teorema de la Base (**b**)
> Cualquier vector $\overrightarrow{D}$ en el espacio tridimensional puede ser escrito como combinación linear de tres vectores no nulos y no paralelos $\overrightarrow{A}$ , $\overrightarrow{B}$ y $\overrightarrow{C}$

La **dimensión** de una base es el número de vectores que pertenecen a la base

- Vectores
	- Son elementos de un conjunto llamado **espacio vectorial**
		- Vectores Equipolentes
			- Vectores que poseen las mismas características
		- Vectores Libres
			- Vectores que cumplen una relación de equivalencia
				- $\overrightarrow{a}\approx\overrightarrow{b}$
					- $|\overrightarrow{a}|=|\overrightarrow{b}|$
					- $\text{Dirección de } \overrightarrow{a} = \text{Dirección de } \overrightarrow{b}$
					- $\text{Sentido de } \overrightarrow{a} = \text{Sentido de } \overrightarrow{b}$
					- Vectores Fijos
						- $\text{Origen de } \overrightarrow{a} = \text{Origen de } \overrightarrow{b}$
		- Vectores de Posición
			- Vectores cuyo origen es el sistema de coordenadas
		- Vector Unitario
			- Su módulo es igual a $1$
		- Vector Nulo
			- $\overrightarrow{0}$
				- $\overrightarrow{a}=(0,0,0)$
		- Vectores Opuestos
			- Tienen sentidos opuestos
				- $\overrightarrow{A}+\overrightarrow{B}=\overrightarrow{0}$
		- Igualdad de Vectores - Dos vectores son iguales si y solo si sus características son iguales
			- $\overrightarrow{A}=\overrightarrow{B}$
				- $A_{x}=B_{x}$
				- $A_{y}=B_{y}$
				- $A_{z}=B_{z}$
		- Suma algebraica de vectores - La suma geométrica de vectores se realiza usando la **regla del paralelogramo**, donde un vector se posiciona con su origen en el extremo del vector anterior, y el **vector suma** va desde el origen del primer vector hasta el extremo del último
			- $\overrightarrow{A}+\overrightarrow{B}$
				- $(A_{x}+B_{x},A_{y}+B_{y},A_{z}+B_{z})$
				- Tambien es un vector
				- Propiedades
					- Conmutativa
						- $\overrightarrow{A}+\overrightarrow{B}=\overrightarrow{B}+\overrightarrow{A}$
					- Asociativa
						- $(\overrightarrow{A}+\overrightarrow{B})+\overrightarrow{C}=\overrightarrow{A}+(\overrightarrow{B}+\overrightarrow{C})$
					- Existencia de elementro neutro
						- $\overrightarrow{A}+\overrightarrow{0}=\overrightarrow{A}$
					- Existencia de opuesto
						- $\overrightarrow{A}+\overrightarrow{B}=\overrightarrow{0}$
					- Monotonía de la igualdad vectorial respecto a la suma de vectores
						- $\overrightarrow{A}=\overrightarrow{B}, \overrightarrow{C}=\overrightarrow{D}\implies\overrightarrow{A}+\overrightarrow{C}=\overrightarrow{B}+\overrightarrow{D}$
		- Diferencia de vectores - Geométricamente, $\overrightarrow{A}-\overrightarrow{B}$ es el vector que al sumarse con $\overrightarrow{B}$ resulta en el vector $\overrightarrow{A}$
			- $\overrightarrow{A}-\overrightarrow{B}=\overrightarrow{A}+(-\overrightarrow{B})$

## Sistemas de Coordenadas
Los sistemas de coordenadas son los que permiten representar las figuras geométricas de forma analítica y explorar algebraicamente sus propiedades.

### Segmento Dirigido
El concepto de segmento en geometría elemental se extiende al agregarle un **sentido** o **dirección**. El primer punto del segmento es llamado **origen** y el segundo se llama **extremo**. En un segmento dirigido, las longitudes de dos segmentos con sentidos opuestos tienen signos diferentes. Esto significa que $\overline{AB}=-\overline{BA}$  y $\overline{AB}+\overline{BC}=\overline{AC}$.

### Sistema de Coordenadas Lineal
Un **sistema de coordenadas** establece una relación biunívoca entre puntos geométricos y números reales.

1. Siendo $X'X$ una recta cuya dirección positiva es de izquierda a derecha, y siendo $O$ un punto fijo sobre la recta
2. Se toma un punto $A$ a la derecha de $O$ como punto de referencia, y se considera a $\overline{OA}$ como unidad de longitud
	1. Si $P$ es un punto de $X'X$ situado a la derecha de $O$ tal que $OP$ contiene $x$ veces a $\overline{OA}$ , entonces $P$ corresponde a el número real $x$
	2. Si $P'$ es un punto de $X'X$ situado a la izquierda de $O$ tal que $OP$ contiene $x'$ veces a $\overline{OA}$ , entonces $P$ corresponde a el número real $-x$

En este caso, todos los puntos yacen sobre una recta, por lo que se le llama **sistema unidimensional** o **sistema de coordenadas lineal**.

La recta $X'X$ es llamada **eje** y el punto $O$ es llamado **origen** en el sistema de coordenadas. El número real $x$ que corresponde al punto $P$ es su **coordenada** y se representa como $(x)$ . De acuerdo con las convenciones adoptadas, al punto $O$ le corresponde $(0)$ y al punto $A$ le corresponde $(1)$ .

El punto $P$ y su coordenada $(x)$ es la **representación geométrica** del número real $x$. El número real $x$ es la **representación análitica** del punto $P$ . Habitualmente, un punto $P$ y su coordenada se escriben juntos como $P(x)$ .

La **longitud de un segmento dirigido** $P_{1}P_{2}$ es $x_{1}-x_{2}$ .

> [!teorema]- Teorema 1.
> En un sistema de coordenadas lineal, la longitud del segmento dirigido que une dos puntos se obtiene restando la coordenada del origen de la coordenada del extremo

> [!info]-
>  $\overline{AB}+\overline{BC}=\overline{AC}$ por Postulado
>  $x_{1}+\overline{P_{1}P_{2}}=x_{2}$ por Sustitución
>  $\overline{P_{1}P_{2}}=x_{2}-x_{1}$ por Despeje

La **distancia entre dos puntos** se define como el valor absoluto de la longitud del segmento que une los puntos. Si representamos a la distancia como $d$ , entonces $$
d=|\overline{P_{1}P_{2}}|=|x_{2}-x_{1}|
$$
### Sistema de Coordenadas en el Plano
El sistema de coordenadas bidimensional es usado en la Geometría Analítica plana y puede representar cualquier punto ubicado dentro de un plano.

El sistema de coordenadas más común que se utiliza es el sistema de coordenadas rectangulares, tambien usado en el álgebra y la trigonometría. Este sistema consta de dos rectas $X'X$ y $Y'Y$ , llamadas **ejes de coordenadas**, que son perpendiculares entre sí. La recta $X'X$ es llamada eje $X$ ; la recta $Y'Y$ es llamada eje $Y$, y su punto de intersección $O$ es el **origen**. La dirección positiva del eje $X$ es hacia la derecha y la dirección positiva del eje $Y$ es hacia arriba. Los ejes dividen al plano en cuatro regiones llamadas **cuadrantes**.
- Cuadrante $\mathrm{I}$ - Semieje $X$ positivo, Semieje $Y$ positivo
- Cuadrante $\mathrm{II}$ - Semieje $X$ negativo, Semieje $Y$ positivo
- Cuadrante $\mathrm{III}$ - Semieje $X$ negativo, Semieje $Y$ negativo
- Cuadrante $\mathrm{IV}$ - Semieje $X$ positivo, Semieje $Y$ negativo

Siendo $A$ la proyección perpendicular de $P$ sobre el eje $X$ y $B$ la proyección perpendicular de $P$ sobre el eje $Y$, la longitud del segmento dirigido $OA$ se representa por $x$ y es llamada **abscisa**. De forma similar, la longitud del segmento dirigido $OB$ se representa por $y$ y es llamada **ordenada**. Los números reales $x$ y $y$ se llaman coordenadas del punto $P$ y se representan como el par ordenado $(x, y)$ , donde $(x,y) \neq (y,x)$ siempre que $x\neq y$ .

Si se consideran solo los puntos cuyas ordenadas son cero, el sistema se reduce a un sistema lineal; por lo tanto, el sistema de coordenadas lineal es un caso especial del sistema de coordenadas bidimensionales.

Sean $P_{1}(x_{1},y_{1})$ y $P_{2}(x_{2},y_{2})$ dos puntos cualquiera, la **distancia entre los dos** es igual a $|\overline{P_{1}P_{2}}|$ .  La longitud de este segmento puede obtenerse por medio del teorema de Pitagoras.

> [!teorema]- Teorema 2.
> La distancia $d$ entre los puntos $P_{1}(x_{1},y_{2})$ y $P_{2}(x_{2},y_{2})$ es dada por la formula $$d=\sqrt{ (x_{2}-x_{1})^{2}+(y_{2}-y_{1})^{2} }$$

___
