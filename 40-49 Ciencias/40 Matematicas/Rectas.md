---
created: 2022-08-22 10:11
---
tags:: #Mathematics 
up:: [[40.05 Geometria]]
Links: 
# Rectas
## Rectas en el Espacio
Cuando Euclides formalizó la geometría por primera vez en los Elementos, definió una línea general (recta o curva) como "sin anchura" y una línea recta como una línea "que se encuentra uniformemente con los puntos sobre sí misma". Estas definiciones sirven de poco, ya que utilizan términos que no están definidos por sí mismos. De hecho, el mismo Euclides no usó estas definiciones en este trabajo, y probablemente las incluyó solo para dejarle claro al lector lo que se estaba discutiendo. En la geometría moderna, una línea se toma simplemente como un objeto indefinido con propiedades dadas por axiomas, pero a veces se define como un conjunto de puntos que obedecen a una relación lineal cuando se deja sin definir algún otro concepto fundamental.

### Ecuacion Vectorial Parametrica
$l:\overrightarrow{OP}=\overrightarrow{OP_0}+\lambda \overrightarrow{L}$, donde $\lambda \in \mathbb{R}$, $\overrightarrow{P_0} \in l$, y $\overrightarrow{L}$ es el vector director de la recta

### Ecuacion Parametrica Cartesiana
Tiene la forma $\begin{align*}x=p_x+\lambda l_x \\ y=p_y+\lambda l_y \\ z=p_z+\lambda l_z \end{align*}\; , \lambda \in \mathbb{R}$ y se obtiene al separar la Ecuacion Vectorial Parametrica en una ecuacion para cada componente.

> [!note]+ Nota
> 
Esta ecuacion se usa para encontrar la interseccion de la recta con un plano u otra recta

### Ecuacion Continua
Se toma la Ecuacion Parametrica Cartesiana y se despeja el valor de $\lambda$ y luego se igualan las ecuaciones resultantes

$\begin{align*} \lambda =\frac{x-p_x}{l_x} \\ \lambda =\frac{y-p_y}{l_y} \\ \lambda =\frac{z-p_z}{l_z} \\ \frac{x-p_x}{l_x}=\frac{y-p_y}{l_y}=\frac{z-p_z}{l_z} \end{align*}$

> [!note]+ Nota
> 
Esta ecuacion se usa para determinar si un punto pertenece a la recta.

### Recta como Interseccion de dos Planos
$$l: \begin{align*}
\pi_1 :A_1x+B_1y+C_1z+D_1=0 \\ \pi_2: A_2x+B_2y+C_2z+D_2=0
\end{align*}$$

Cualquier punto cuyas coordenadas satisfagan ambas ecuaciones del sistema pertenece a $l$

### Planos Proyectantes
Estos son los planos que pasan por $l$ y son perpendiculares a los planos coordenados. Para obtener un plano proyectante determinado de la recta, se expresa la recta como la interseccion de dos planos y se multiplica uno de las ecuaciones de los planos por un escalar y se añade a la otra, de modo que se elimine una de las variables de las ecuaciones

### Distancia entre una Recta y un Plano
En caso de que la recta este incluida en el plano o que la recta corte al plano, la distancia entre los dos es igual a cero. En caso de que sean paralelos y la recta no pertenezca al plano basta con hallar la distancia de cualquier punto $P_0$ de $l$ al plano $\pi$

> [!note]+ Nota
> 
Se puede usar la formula: $d=\frac{|Ax_0+By_0+Cz_0+D|}{|\overrightarrow{N}|}$

### Distancia entre dos Rectas que se cruzan
Para encontrar al vector distancia entre las rectas se calcula un vector $\overrightarrow{N}= \overrightarrow{L_1} \times \overrightarrow{L_2}$ perpendicular a ambos vectores, luego se toma un vector que vaya desde un punto de una recta a un punto en la otra recta, y finalmente, este ultimo vector se [[Producto Escalar#Proyeccion de un Vector sobre otro | Proyecta]] sobre el vector $\overrightarrow{N}$

> [!note]+ Nota
> 
Se puede encontrar directamente la magnitud de la distancia entre las rectas usando la siguiente formula $|\overrightarrow{D}|= \frac{|\overrightarrow{L_1} * \overrightarrow{L_2}|}{|\overrightarrow{N}|}$

### Posiciones Relativas entre Recta y Plano
> [!note]+ Nota
> 
Para determinar la posicion relativa entre una recta y un plano basta con calcular el producto punto entre el vector director de la recta y la normal del plano. Si el resultado es igual a cero, la recta es perpendicular a la normal, y por lo tanto, es paralela al plano; pero si el resultado no es cero, la recta y el plano no son paralelos por lo que la recta y el plano se cortan

1. Si el plano y la recta no se cortan, entonces la recta es paralela al plano sin pertenecer a este, por lo que existe una distancia entre estos.

2. Si el plano y la recta se cortan, entonces se intersectan en algun punto. Para hallar el punto de interseccion se debe encontrar un punto que pertenezca al plano y a la recta al mismo tiempo. 
	Para hallar el angulo de corte se debe hallar la posicion relativa entre el vector director de la recta y la normal del plano y a partir de esta determinar el angulo con el plano. 
	Para hallar la proyeccion de $l$ sobre $\pi$ basta con proyectar dos puntos diferentes de la recta sobre el plano, y a partir de la proyeccion, calcular la ecuacion de la recta proyectada
___
