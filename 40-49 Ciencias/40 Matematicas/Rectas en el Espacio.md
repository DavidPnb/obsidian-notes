---
created: 2022-08-22 10:11
---
tags:: #Mathematics 
up:: [[40.05 Geometria]]
Links: 
# Rectas en el Espacio
![[Rectas en el Espacio.canvas]]

La recta se construye a través de un punto y un vector que le da dirección, llamado **vector director** de la recta. Para que un punto pertenezca a la recta, el vector que va desde un punto de la recta a esta punto debe ser paralelo al vector director de la recta.

## Ecuaciones
### Ecuacion Vectorial Parametrica
$L:\overrightarrow{P}=\overrightarrow{P_1}+\lambda \overrightarrow{L}$, donde $\lambda \in \mathbb{R}$, $\overrightarrow{P_0} \in l$, y $\overrightarrow{L}$ es el vector director de la recta. Se obtiene a partir de la condición original

### Ecuacion Parametrica
Tiene la forma $\begin{align*}x=p_x+\lambda l_x \\ y=p_y+\lambda l_y \\ z=p_z+\lambda l_z \end{align*}\; , \lambda \in \mathbb{R}$ y se obtiene conociendo los valores de $P_{1}$ y $\overrightarrow L$ en la ecuación vectorial paramétrica.

### Ecuacion Simétrica
Se toma la ecuación paramétrica y se despeja el valor de $\lambda$ y luego se igualan las ecuaciones resultantes

$\begin{align*} \lambda =\frac{x-p_x}{l_x} \\ \lambda =\frac{y-p_y}{l_y} \\ \lambda =\frac{z-p_z}{l_z} \\ \frac{x-p_x}{l_x}=\frac{y-p_y}{l_y}=\frac{z-p_z}{l_z} \end{align*}$
### Recta como Interseccion de dos Planos
$$l: \begin{align*}
\pi_1 :A_1x+B_1y+C_1z+D_1=0 \\ \pi_2: A_2x+B_2y+C_2z+D_2=0
\end{align*}$$

Esta ecuación se obtiene al desarrollar la ecuación simétrica .Cualquier punto cuyas coordenadas satisfagan ambas ecuaciones del sistema pertenece a $l$

## Planos Proyectantes
Estos son los planos que pasan por $l$ y son perpendiculares a otro plano.

## Distancias
### Distancia entre un punto y una recta
$$d=\frac{|\overrightarrow{P_{1}Q}\times \overrightarrow{L}|}{|\overrightarrow L|}$$
Se obtiene usando proyección perpendicular y simplificando.

### Distancia entre una Recta y un Plano
En caso de que la recta este incluida en el plano o que la recta corte al plano, la distancia entre los dos es igual a cero. Si la recta es paralela al plano, la distancia entre los dos es igual a la distancia entre cualquier punto de la recta y el plano.

### Distancia entre dos Rectas que se cruzan
Para encontrar al vector distancia entre las rectas se calcula un vector $\overrightarrow{N}= \overrightarrow{L_1} \times \overrightarrow{L_2}$ perpendicular a ambos vectores, luego se toma un vector que vaya desde un punto de una recta a un punto en la otra recta, y finalmente, este ultimo vector se proyecta sobre el vector $\overrightarrow{N}$ $$
d=\frac{|\overrightarrow{P_{1}P_{2}}\cdot(\overrightarrow{L_{1}}\times\overrightarrow{L_{2}})|}{|\overrightarrow{L_{1}}\times\overrightarrow{L_{2}}|}
$$
## Posiciones Relativas
### Posiciones Relativas entre Rectas
- **Coplanares** - $|\overrightarrow{P_{1}P_{2}}\cdot(\overrightarrow{L_{1}}\times\overrightarrow{L_{2}})|=0$
	- $\overrightarrow{L_{1}}\parallel \overrightarrow{L_{2}}$
		- $\overrightarrow{L_{1}}\times\overrightarrow{L_{2}}=\overrightarrow{0}$
		- $\overrightarrow{L_{1}}=\lambda\overrightarrow{L_{2}}$
	- $\overrightarrow{L_{1}}\perp\overrightarrow{L_{2}}$
		- $\overrightarrow{L_{1}}\cdot \overrightarrow{L_{2}}=0$
	- $\overrightarrow{L_{1}}$ intersecta a $\overrightarrow{L_{2}}$
		- $\cos \theta=\frac{\overrightarrow{L_{1}}\cdot\overrightarrow{L_{2}}}{|\overrightarrow{L_{1}}||\overrightarrow{L_{2}}|}$
- $\overrightarrow{L_{1}}$ y $\overrightarrow{L_{2}}$ se cruzan

### Posiciones Relativas entre Recta y Plano
- $\pi \parallel \overrightarrow{L}$
	- $\overrightarrow{N}\cdot \overrightarrow{L}=0$
- $\pi \perp \overrightarrow{L}$
	- $\overrightarrow{N}\times\overrightarrow{L}=\overrightarrow{0}$
- $L$ intersecta a $\pi$
	- $\cos \theta=\overrightarrow{\mu_{L}}\cdot\overrightarrow{\mu_{N}}$
	- $90°-\theta=\phi$
___
