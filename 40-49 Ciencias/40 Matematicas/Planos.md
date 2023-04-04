---
created: 2022-05-17 21:34
---
tags:: #Mathematics 
up:: [[Geometria Analitica]]
# Planos
![[Planos.canvas]]

En matemáticas, un plano es una superficie bidimensional plana que se extiende indefinidamente. Un plano es el análogo bidimensional de un punto (dimensiones cero), una línea (una dimensión) y un espacio tridimensional.

## Ecuaciones
### Ecuacion Vectorial Paramétrica
$\pi :\overrightarrow{P}= \overrightarrow{P_1}+ \lambda_1 \overrightarrow{A}+ \lambda_2 \overrightarrow{B}$

donde $\lambda_1,\lambda_2 \in \mathbb{R}$, $\overrightarrow{A}$ y $\overrightarrow{B}$ son vectores linealmente independientes que definen el plano, y $\overrightarrow{P_{1}}$ es el vector que representa la posición de un punto arbitrario pero fijo en el plano. 

### Ecuacion Paramétrica
Al conocer los componentes de $P_{1}$ , $\overrightarrow{A}$ y $\overrightarrow{B}$ se obtiene $$\begin{align}
x=x_{1}+\lambda_{1}A_{x}+\lambda_{2}B_{x} \\ y=y_{1}+\lambda_{1}A_{y}+\lambda_{2}B_{y} \\ z=z_{1}+\lambda_{1}A_{z}+\lambda_{2}B_{z}
\end{align}$$
### Ecuación Escalar
$\overrightarrow N\cdot(\overrightarrow P-\overrightarrow{P_{1}})=0$

Para encontrar a $\overrightarrow N$ se usa el producto vectorial entre dos vectores pertenecientes al plano.

### Ecuacion General
Dado un punto $P_1=(x_1,y_1,z_1)$ de un plano y un vector $\overrightarrow{N}=(A,B,C)$ perpendicular al plano, el plano sera el lugar geometrico descrito por un punto generico $P=(x,y,z)$ que se mueve en el espacio $\mathbb{R}3$ de tal forma que siempre el vector $P_1P$ sera perpendicular al vector $\overrightarrow{N}$

$\pi :Ax+By+Cz+D=0$

donde $(A,B,C)$ y $(x,y,z)$ son conocidos, y $D$ puede encontrarse reemplazando un punto del plano y resolviendo la ecuacion para $D$. En general, $D=-\overrightarrow N\cdot \overrightarrow{P_{1}}$

### Ecuación Simétrica
$$\frac{x}{a}+\frac{y}{b}+\frac{z}{c}-1=0$$
se obtiene al dividir la ecuación entre $-D$ , donde $a,b,c$ son los puntos de corte con los ejes coordenados.

### Ecuación Normal
$$\pi=\cos(\alpha)x+\cos(\beta)y+\cos(\rho)z-h=0$$
se obtiene al dividir la ecuación entre $|\overrightarrow N|$

### Forma Determinante
$$
\begin{vmatrix}
A_{x} & A_{y} & A_{z} \\
B_{x} & B_{y} & B_{z} \\
x-x_{1} & y-y_{1} & z-z_{1}
\end{vmatrix}=0
$$

## Distancias
### Distancia desde el Origen al Plano
$$
h=\overrightarrow{P_{1}}\cdot\overrightarrow{\mu_{N}}
$$

Se obtiene al proyectar el vector de posición de un punto en el plano sobre la normal del plano.

### Distancia entre Punto y Plano
$$d=\frac{|Ax_0+By_0+Cz_0+D|}{|\overrightarrow{N}|}$$

Se obtiene al proyectar un vector desde el punto en el plano sobre el punto en el exterior sobre la normal del plano.

## Posiciones de un Plano
- Si $D=0$
	- $O\in\pi$
- Si $N_{z}=0$
	- $\pi \perp XY$
- Si $N_{y}=0$
	- $\pi \perp XZ$
- Si $N_{x}=0$
	- $\pi \perp YZ$
- Si $N_{y}\,,N_{z}=0$
	- $\pi \perp X$
	- $\pi \parallel YZ$
- Si $N_{x}\,,N_{z}=0$
	- $\pi \perp Y$
	- $\pi \parallel XZ$
- Si $N_{x}\,,N_{y}=0$
	- $\pi \perp X$
	- $\pi \parallel Z$

## Familia de Planos
### Familia de Planos Paralelos
$$F :Ax+By+Cz+D_{f}=0$$
constituye una familia de planos paralelos porque todos tienen el mismo vector normal.

### Familia de Planos no Paralelos
$$F: \lambda_1\pi_1 + \lambda_2\pi_2=0$$
es la familia de planos que pasan por la interseccion de $\pi_1$ y $\pi_2$ .

## Posiciones Relativas entre Planos
1. Si $\pi_1$ y $\pi_2$ no se intersectan, entonces son paralelos. Esto significa que un plano tambien es perpendicular a la normal del otro plano y por lo tanto $\overrightarrow{N_1}= \lambda \overrightarrow{N_2}$.
2. Si $\pi_1$ y $\pi_2$ no son paralelos, estos se intersectan formando una recta. El angulo entre $\pi_1$ y $\pi_2$ es el mismo angulo entre $\overrightarrow{N_1}$ y $\overrightarrow{N_2}$ ya que los [[angulos]] de lados perpendiculares son iguales.
	- Si $\overrightarrow{N_1} \cdot \overrightarrow{N_2}>0$, el angulo es menor que $90°$.
	- Si $\overrightarrow{N_1} \cdot \overrightarrow{N_2}<0$, el angulo es mayor que $90°$.
	- Si $\overrightarrow{N_1} \cdot \overrightarrow{N_2}=0$, los planos son perpendiculares.
___
