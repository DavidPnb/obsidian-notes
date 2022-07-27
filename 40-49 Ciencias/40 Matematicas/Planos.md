---
status:
tags: 
references:
created: 2022-05-17 21:34
---
Links: [[]]
# Planos
En matemáticas, un plano es una superficie bidimensional plana que se extiende indefinidamente. Un plano es el análogo bidimensional de un punto (dimensiones cero), una línea (una dimensión) y un espacio tridimensional.

### Ecuacion General
Dado un punto $P_0=(x_0,y_0,z_0)$ de un plano y un vector $\overrightarrow{N}=(A,B,C)$ perpendicular al plano, el plano sera el lugar geometrico descrito por un punto generico $P=(x,y,z)$ que se mueve en el espacio $\mathbb{R}3$ de tal forma que siempre el vector $P_0P$ sera perpendicular al vector $\overrightarrow{N}$

$\pi :Ax+By+Cz+D=0$

donde $(A,B,C)$ y $(x,y,z)$ son conocidos, y $D$ puede encontrarse reemplazando un punto del plano y resolviendo la ecuacion para $D$.

En matematicas, es comun expresar la normal como un vector unitario

> [!info]+ Informacion
> 
>Esta ecuacion viene dada por el producto punto entre el vector $\overrightarrow{N}=(A,B,C)$ y el vector $P_0P$, donde $Ax+By+Cz$ vienen dados por el producto punto entre $\overrightarrow{N}$ y $\overrightarrow{P}$ y $D$ es igual al producto punto entre $\overrightarrow{N}$ y $\overrightarrow{P_0}$. Esto debido a una de las [[Producto Escalar#Propiedades | Propiedades]] del producto escalar

### Ecuacion Vectorial Parametrica
$\pi : \overrightarrow{OP_0}+ \lambda_1 \overrightarrow{V_1}+ \lambda_2 \overrightarrow{V_2}$

donde $\lambda_1,\lambda_2 \in \mathbb{R}$, $\overrightarrow{V_1}$ y $\overrightarrow{V_2}$ son vectores linealmente independientes que definen el plano, y $\overrightarrow{OP_0}$ es el vector que representa la posición de un punto arbitrario pero fijo en el plano. Los vectores $\overrightarrow{V_1}$ y $\overrightarrow{V_2}$ se pueden visualizar como vectores que comienzan en $\overrightarrow{OP_0}$ y apuntan en diferentes direcciones a lo largo del plano. Los vectores $\overrightarrow{V_1}$ y $\overrightarrow{V_2}$ pueden ser perpendiculares, pero no paralelos.

> [!note]+ Nota
> 
Se puede convertir esta ecuacion a una ecuacion general al calcular el producto vectorial entre $\overrightarrow{V_1}$ y $\overrightarrow{V_2}$ y usarlo como la normal del plano

### Ecuacion con Tres Puntos
Siendo $p_1=(x_1,y_1,z_1)$, $p_2=(x_2,y_2,z_2)$, y $p_3=(x_3,y_3,z_3)$ puntos no colineales.

$\begin{align*}
ax_1+by_1+cz_1+d=0 \\ ax_2+by_2+cz_2+d=0 \\ ax_3+by_3+cz_3+d=0
\end{align*}$

> [!note]+ Nota
> 
>Esta ecuacion tambien puede describirse en forma general usando $\overrightarrow{N}=(p_2-p_1)\times(p_3-p_1)$ y usando cualquiera de los tres puntos como $p_0$ en la ecuacion $\overrightarrow{P_0P} * \overrightarrow{N}=0$
### Distancia entre Punto y Plano
$d=\frac{|Ax_0+By_0+Cz_0+D|}{|\overrightarrow{N}|}$

### Familia de Planos
#### Familia de Planos Paralelos
En general la ecuacion $X+Y+Z+K=0; \forall K \in \mathbb{R}$
Constituye una familia de planos paralelos porque todos tienen el mismo vector normal

#### Familia de Planos no Paralelos
La ecuacion $\pi f: \lambda_1\pi_1 + \lambda_2\pi_2=0$
Es la familia de planos que pasan por la interseccion de $\pi_1$ y $\pi_2$

### Posiciones Relativas entre Planos
1. Si $\pi_1$ y $\pi_2$ no se intersectan, entonces son paralelos. Esto significa que un plano tambien es perpendicular a la normal del otro plano y por lo tanto $\overrightarrow{N_1}= \lambda \overrightarrow{N_2}$.

2. Si $\pi_1$ y $\pi_2$ no son paralelos, estos se intersectan formando una recta. El angulo entre $\pi_1$ y $\pi_2$ es el mismo angulo entre $\overrightarrow{N_1}$ y $\overrightarrow{N_2}$ ya que los [[angulos]] de lados perpendiculares son iguales.

	Si $\overrightarrow{N_1} * \overrightarrow{N_2}>0$, el angulo es menor que $90°$.

	Si $\overrightarrow{N_1} * \overrightarrow{N_2}<0$, el angulo es mayor que $90°$.

	Si $\overrightarrow{N_1} * \overrightarrow{N_2}=0$, los planos son perpendiculares.
___
