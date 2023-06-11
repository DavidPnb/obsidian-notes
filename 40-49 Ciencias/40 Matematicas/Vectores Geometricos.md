---
created: 2023-02-02 13:03
---
tags:: #Mathematics 
up:: [[Geometria Analitica]]
# Vectores Geométricos
![[Vectores Geometricos.canvas]]

En el enfoque vectorial, varios conceptos de vectores son fundamentales, como el producto punto y el producto cruz. En este contexto, los vectores pueden ser considerados una representación analítica de un segmento dirigido. A esto se le llama comunmente **vector geométrico**. Este concepto se usa mucho en la física, en donde un vector se usa para representar magnitudes que se comprenden mejor al pensar en ellas como una flecha con un origen y un extremo.

## Características de un Vector
Un vector geométrico tiene tres características
- **Módulo** - Representa la longitud del vector. Es igual a la longitud del segmento entre el origen y el extremo del vector
- **Dirección** - Esta determinada por la pendiente de la recta que contiene al vector
- **Sentido** - Una de las dos orientaciones posibles de la recta que contiene al vector

Esto contrasta con el concepto de un **escalar**, que pueden ser representados por una única magnitud.

Un vector generalmente se representa como $\overrightarrow{A}$ , usando $|\overrightarrow{A}|$ para referirse al modulo del vector. Un vector entre dos puntos se representa como  $\overrightarrow{AB}$ , donde $A$ es el origen del vector, $B$ es el extremo y $|\overrightarrow{AB} |$ es el modulo del vector.

Dos vectores son **paralelos** si tienen la misma dirección.

## Igualdad de Vectores
Dos vectores son iguales si y solo si sus características son iguales.

## Suma de Vectores
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

## Resta de Vectores
Geométricamente, $\overrightarrow{A}-\overrightarrow{B}$ es el vector que al sumarse con $\overrightarrow{B}$ resulta en el vector $\overrightarrow{A}$ . Este vector tiene como origen el extremo de $\overrightarrow{B}$ y como extremo el extremo de $\overrightarrow{A}$ . Se calcula como $\overrightarrow{A}-\overrightarrow{B}=\overrightarrow{A}+(-\overrightarrow{B})$ , donde $-\overrightarrow{B}$ es el opuesto de $\overrightarrow{B}$.

El **módulo de la resta de vectores** es igual al módulo de la suma de vectores.

## Producto entre un Vector y un Escalar
Produce un vector proporcional al vector original cuyo sentido depende del signo del escalar y cuyo módulo es $\lambda$ veces mayor.

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

## Vectores Unitarios
Son vectores cuyo modulo es igual a uno, y por lo tanto estan caracterizados por su dirección y sentido. El vector unitario en la dirección de $\overrightarrow{A}$ , denotado como $\overrightarrow{\mu}_{A}$ , se calcula como $\frac{\overrightarrow{A}}{|\overrightarrow{A}|}$.

### Proyección de un Vector sobre Otro
$$
(\overrightarrow A \cdot \overrightarrow{\mu_{B}})\cdot\overrightarrow{\mu_{B}}
$$
donde $\overrightarrow A$ es el vector a proyectar.

## Base de Vectores
Se dice que un vector $\overrightarrow{C}$ es una **combinación lineal** de $\overrightarrow{A}$ y $\overrightarrow{B}$ si $\overrightarrow{C}=\lambda_{1}\overrightarrow{A}+\lambda_{2}\overrightarrow{B}$ .

> [!teorema] Teorema de la Base (**a**)
> Cualquier vector $\overrightarrow{C}$ puede ser escrito como una combinación lineal de dos vectores no nulos y no paralelos $\overrightarrow{A}$ y $\overrightarrow{B}$ que esten el mismo plano

> [!teorema] Teorema de la Base (**b**)
> Cualquier vector $\overrightarrow{D}$ en el espacio tridimensional puede ser escrito como combinación linear de tres vectores no nulos, no paralelos al mismo plano y no paralelos entre sí $\overrightarrow{A}$ , $\overrightarrow{B}$ y $\overrightarrow{C}$

La **dimensión** de una base es el número de vectores que pertenecen a la base.

### Base Canónica
En dos dimensiones, es conveniente escoger como base dos vectores unitarios que se ubiquen sobre el eje $X$ y el eje $Y$, de modo que sean perpendiculares. Estos vectores son llamados $\mathbf{i}$ y $\mathbf{j}$ respectivamente.

De este modo, cualquier vector $r$ en dos dimensiones puede representarse como una combinación lineal $r=x\mathbf{i}+y\mathbf{j}$ . Donde $x=|r|\cos \theta$ y $y=|r|\sin \theta$ , y $\theta$ es el ángulo que forma el vector con $\mathbf{i}$ , y por lo tanto, forma tambien con el eje $X$ . Estas definiciones nos permiten representar vectores en el sistema de coordenadas rectangulares en dos dimensiones.

El vector $r=\overrightarrow{OP}$ es llamado el **vector de posición** de $P$ , ya que las coordenadas del vector son iguales a las coordenadas rectangulares de su extremo. Además, $(\mathbf{r},\theta)$ donde $\mathbf{r}=|r|$ son las **coordenadas polares** del punto $P$. $\theta=\tan ^{-1}\frac{y}{x}$ y $\mathbf{r}$ al ser una longitud es siempre positivo.

En tres dimensiones, se escogen como base tres vectores unitarios perpendiculares entre sí, de modo que el vector de posición $r$ es igual a $r=x\mathbf{i}+y\mathbf{j}+z\mathbf{k}$ . Los vectores unitarios $\mathbf{i}$ , $\mathbf{j}$ y $\mathbf{k}$ son la **base canónica**. Usando el teorema de Pitágoras se puede concluir que $|r|=\sqrt{ x^{2}+y^{2}+z^{2} }$ . La **descomposición canónica** consiste en expresar un vector como una combinación lineal de la base canónica.

### Cosenos Directores
Los ángulos $\alpha$ , $\beta$ y $\rho$ que un vector forma con los ejes de coordenadas son llamados los **ángulos directores** del vector. Usando trigonometría se obtiene que
$$\cos(\alpha)=\frac{A_{x}}{|\overrightarrow{A}|}$$

$$\cos(\beta)=\frac{A_{y}}{|\overrightarrow{A}|}$$

$$\cos(\rho)=\frac{A_{z}}{|\overrightarrow{A}|}$$

$$\cos ^{2} (\alpha)+\cos ^{2}(\beta)+\cos ^{2}(\rho)=1$$

Por lo tanto los cosenos directores de los ejes $X$ , $Y$ y $Z$ son $1$ , $0$ , $0$ **;** $0$ , $1$ , $0$ y $0$ , $0$ , $1$ respectivamente.

## Espacios Vectoriales
Este concepto permite abstraer las propiedades de los vectores sin tener que recurrir a un sistema geométrico. Un **espacio vectorial** es un conjunto con elementos llamados **vectores**, los cuales satisfacen ciertos postulados y pueden efectuar en ellos dos operaciones:

### Operaciones
1. **Suma** - Dos vectores pueden combinarse produciendo como resultado otro vector perteneciente al espacio vectorial
2. **Multiplicación Escalar** - Un vector puede multiplicarse por un número real cualquiera, resultando en otro vector perteneciente al EV

### Postulados
1. $x+y=y+x$
2. $x+(y+z)=(x+y)+z$
3. Existe un vector único en EV llamado vector nulo $O$ tal que $x+O=x$ para todo $x$ en EV
4. Para todo elemento existe un único inverso $-x$ tal que $x+(-x)=O$
5. $a(x+y)=ax+ay$
6. $(a+b)x=ax+bx$
7. $a(bx)=(ab)x$
8. $1\cdot x=x$
9. $O\cdot x=O$

### Teoremas
1. $-1\cdot x=-x$
2. $aO=O$
3. $x+y=x+z\implies y=z$
4. $ax=ay,a\neq0\implies x=y$
5. $ax=bx,x\neq O\implies a=b$
6. Si $S$ es un subconjunto de un EV donde se cumple que $x+y$ y $ax$ pertenecen a $S$ si $x$ y $y$ pertenecen a $S$

Se dice que $n$ vectores son **linearmente dependientes** si $a_{1}x_{1}+a_{2}x_{2}+\dots+a_{n}x_{n}=0$ , de lo contrario, se les considera **linearmente independientes**.

Si $S$ contiene un conjunto de $n$ vectores linealmente independientes, y todo conjunto de $n+1$ vectores en $S$ es linearmente independientede, se dice que $S$ es de **dimensión finita** y su **dimensión** es $n$ . Si $S$ no es de dimensión finita, se dice que es de **dimensión infinita**.

Un conjunto de $n$ **vectores** forman una **base** en el espacio vectorial $S$ al que pertenecen. Cualquier vector en $S$ puede ser representado como una combinación lineal de cierta base de $S$.

### Propiedades del Módulo
1. $|x+y|\leq|x|+|y|$
2. $|ax|=|a||x|$
3. $|x|\geq0$
4. $x\neq O\implies|x|\neq0$

## Álgebra de Vectores
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
El **Producto Vectorial** de  $\overrightarrow A$ y $\overrightarrow B$ , representado por $\overrightarrow A\times \overrightarrow B$, resulta en un vector perpendicular a $\overrightarrow A$ y $\overrightarrow B$. Se calcula como $$
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
A_{x} & A_{y} & A_{z} \\
B_{x} & B_{y} & B_{z}
\end{vmatrix}
$$

- Propiedades
	- $\overrightarrow A\times \overrightarrow B=(-1)\overrightarrow B\times \overrightarrow A$
	- $\overrightarrow A \times(\overrightarrow B+\overrightarrow C)=\overrightarrow A \times \overrightarrow B+\overrightarrow A\times \overrightarrow C$
	- $\lambda (\overrightarrow A\times \overrightarrow B)=\lambda \overrightarrow A\times \overrightarrow B=\overrightarrow A\times \lambda \overrightarrow B$
	- $\overrightarrow A \times(\overrightarrow B\times \overrightarrow C)$ es perpendicular al plano donde se encuentran $\overrightarrow B$ y $\overrightarrow C$
	- $|\overrightarrow A \times \overrightarrow B|=|\overrightarrow A| |\overrightarrow B| \sin(\theta)$
- $A_{\text{Paralelogramo}}=|\overrightarrow A \times \overrightarrow B|$
	- $\overrightarrow A$ y $\overrightarrow B$ son lados con un mismo vértice
- $\tan(\theta)=\frac{|\overrightarrow A \times \overrightarrow B|}{\overrightarrow A \cdot \overrightarrow B}$
- Condición de Paralelismo
	- $|\overrightarrow A \times \overrightarrow B|=0$

### Producto Mixto
El producto mixto de $\overrightarrow A$ , $\overrightarrow B$ y $\overrightarrow C$ , representado por $(\overrightarrow A\times \overrightarrow B)\cdot \overrightarrow C$ se calcula como $$
\begin{vmatrix}
A_{x} & A_{y} & A_{z} \\
B_{x} & B_{y} & B_{z} \\
C_{x} & C_{y} & C_{z}
\end{vmatrix}
$$
 
- Propiedades
	- $(\overrightarrow A\times \overrightarrow B)\cdot \overrightarrow C=\overrightarrow A\cdot (\overrightarrow B\times \overrightarrow C)$
	- $\lambda[(\overrightarrow A\times \overrightarrow B)\cdot \overrightarrow C]=(\lambda \overrightarrow A\times \overrightarrow B)\cdot \overrightarrow C=(\overrightarrow A\times \lambda \overrightarrow B)\cdot \overrightarrow C=(\overrightarrow A\times \overrightarrow B)\cdot \lambda \overrightarrow C$
	- $V_{\text{Paralelepipedo}}=(\overrightarrow A\times \overrightarrow B)\cdot \overrightarrow C$
		- $\overrightarrow A$ , $\overrightarrow B$ y $\overrightarrow C$ son aristas con un mismo vértice
- Condición de coplanaridad
	- $(\overrightarrow A\times \overrightarrow B)\cdot \overrightarrow C=0$


___

