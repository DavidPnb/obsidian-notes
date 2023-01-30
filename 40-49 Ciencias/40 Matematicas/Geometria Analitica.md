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

El **módulo de la suma de vectores** es $$
|\overrightarrow{A}+\overrightarrow{B}|^{2}=|\overrightarrow{A}|^{2}+|\overrightarrow{B}|^{2}-2|\overrightarrow{A}||\overrightarrow{B}|\cos \theta
$$ por la ley de cosenos; [[40.06 Trigonometria]]. $\theta$ es el ángulo entre los dos vectores

### Resta de Vectores
Geométricamente, $\overrightarrow{A}-\overrightarrow{B}$ es el vector que al sumarse con $\overrightarrow{B}$ resulta en el vector $\overrightarrow{A}$ . Este vector tiene como origen el extremo de $\overrightarrow{B}$ y como extremo el extremo de $\overrightarrow{A}$ . Se calcula como $\overrightarrow{A}-\overrightarrow{B}=\overrightarrow{A}+(-\overrightarrow{B})$ , donde $-\overrightarrow{B}$ es el opuesto de $\overrightarrow{B}$.

El **módulo de la resta de vectores** es igual al módulo de la suma de vectores.

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
> Cualquier vector $\overrightarrow{D}$ en el espacio tridimensional puede ser escrito como combinación linear de tres vectores no nulos, no paralelos al mismo plano y no paralelos entre sí $\overrightarrow{A}$ , $\overrightarrow{B}$ y $\overrightarrow{C}$

La **dimensión** de una base es el número de vectores que pertenecen a la base, y es igual al número de dimensiones involucradas en el espacio.

En dos dimensiones, es conveniente escoger como base dos vectores unitarios que se ubiquen sobre el eje $X$ y el eje $Y$, de modo que sean perpendiculares. Estos vectores son llamados $\mathbf{i}$ y $\mathbf{j}$ respectivamente.

De este modo, cualquier vector $r$ en dos dimensiones puede representarse como una combinación lineal $r=x\mathbf{i}+y\mathbf{j}$ . Donde $x=|r|\cos \theta$ y $y=|r|\sin \theta$ , y $\theta$ es el ángulo que forma el vector con $\mathbf{i}$ , y por lo tanto, forma tambien con el eje $X$ . Estas definiciones nos permiten representar vectores en el sistema de coordenadas rectangulares en dos dimensiones.

El vector $r=\overrightarrow{OP}$ es llamado el **vector de posición** de $P$ , ya que las coordenadas del vector son iguales a las coordenadas rectangulares de su extremo. Además, $(\mathbf{r},\theta)$ donde $\mathbf{r}=|r|$ son las **coordenadas polares** del punto $P$. $\theta=\tan ^{-1}\frac{y}{x}$ y $\mathbf{r}$ al ser una longitud es siempre positivo.

En tres dimensiones, se escogen como base tres vectores unitarios perpendiculares entre sí, de modo que el vector de posición $r$ es igual a $r=x\mathbf{i}+y\mathbf{j}+z\mathbf{k}$ . Los vectores unitarios $\mathbf{i}$ , $\mathbf{j}$ y $\mathbf{k}$ son la **base canónica**. Usando el teorema de Pitágoras se puede concluir que $|r|=\sqrt{ x^{2}+y^{2}+z^{2} }$

Los ángulos $\alpha$ , $\beta$ y $\rho$ que un vector forma con los ejes de coordenadas son llamados los **ángulos directores** del vector. Usando trigonometría se obtiene que
$$\cos(\alpha)=\frac{A_{x}}{|\overrightarrow{A}|}$$

$$\cos(\beta)=\frac{A_{y}}{|\overrightarrow{A}|}$$

$$\cos(\rho)=\frac{A_{z}}{|\overrightarrow{A}|}$$

$$\cos ^{2} (\alpha)+\cos ^{2}(\beta)+\cos ^{2}(\rho)=1$$

Por lo tanto los cosenos directores de los ejes $X$ , $Y$ y $Z$ son $1$ , $0$ , $0$ **;** $0$ , $1$ , $0$ y $0$ , $0$ , $1$ respectivamente.

## Conceptos Básicos de la Geometría Analítica
Se desarrollan ideas y fórmulas básicas al proponer y resolver problemas de carácter fundamental usando los conceptos previos.

### Longitud del Vector entre dos Puntos
El vector que va desde $P_{1}$ hasta $P_{2}$ es $\overrightarrow{P_{1}P_{2}}=\overrightarrow{P_{2}}-\overrightarrow{P_{1}}$ por suma de vectores, así que las coordenadas del vector entre los dos puntos son $\overrightarrow{P_{1}P_{2}}=(x_{2}-x_{1},y_{2}-y_{1},z_{2}-z_{1})$ 

La **distancia entre dos puntos** es entonces $|\overrightarrow{P_{1}P_{2}|}=\sqrt{ (x_{2}-x_{1})^{2}+(y_{2}-y_{1})^{2}+(z_{2}-z_{1})^{2}}$ 

### Punto Medio de un Segmento
$\overrightarrow{P_{1}M}$ es $\frac{1}{2}\overrightarrow{P_{1}P_{2}}$ porque tiene la mitad de su longitud y la misma dirección y sentido, donde $\overrightarrow{P_{1}P_{2}}$ es el segmento formado por dos puntos y $M$ es el punto medio del segmento, entonces $M=\frac{1}{2}\overrightarrow{P_{1}P_{2}}+\overrightarrow{P_{1}}=\frac{1}{2}(\overrightarrow{P_{1}}+\overrightarrow{P_{2}})$ . En general, para encontrar un punto que divide a un segmento en una razón determinada se debe tomar en cuenta que el vector que va desde el origen del segmento hasta el punto es igual al vector del segmento multiplicado por un escalar que depende de la razón dada.

### Producto Escalar
El **Producto Escalar** o **producto punto** de $\overrightarrow{A}$ y $\overrightarrow{B}$ , denotado por $\overrightarrow{A}\cdot\overrightarrow{B}$ es $A_{x}B_{x}+A_{y}B_{y}+A_{z}B_{z}$ y recibe ese nombre debido a que el resultado de la operación es escalar.
- Propiedades
	- $\overrightarrow{A}\cdot\overrightarrow{B}=|\overrightarrow{A}| |\overrightarrow{B}|\cos \theta$
	- $\lambda(\overrightarrow{A}\cdot\overrightarrow{B})=(\lambda\overrightarrow{A})\cdot\overrightarrow{B}=\overrightarrow{A}\cdot(\lambda\overrightarrow{B})$
	- $\overrightarrow{A}\cdot\overrightarrow{A}=|\overrightarrow{A}|^{2}$
	- $\overrightarrow{A} \cdot(\overrightarrow{B}+\overrightarrow{C})=\overrightarrow{A}\cdot\overrightarrow{B}+\overrightarrow{A}\cdot\overrightarrow{C}$

### Ángulo entre dos Rectas
Esto puede resolverse al conseguir el ángulo entre vectores en las rectas, lo que permite encontrar el ángulo entre entre rectas que no se intersectan. Para esto, se trasladan los dos vectores hasta el origen, convirtiendolos en vectores de posición. A partir de aquí, se puede usar la ley de cosenos y despejar para obtener $$\cos \theta=\overrightarrow{\mu}_{A}\cdot\overrightarrow{\mu_{B}}=\frac{\overrightarrow{A}\cdot\overrightarrow{B}}{|\overrightarrow{A}| |\overrightarrow{B}|}$$
- **Condición de perpendicularidad**
	- $\overrightarrow{A}\perp\overrightarrow{B}\iff\overrightarrow{A}\cdot\overrightarrow{B}=0$

### Producto Vectorial

### Producto Mixto

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
