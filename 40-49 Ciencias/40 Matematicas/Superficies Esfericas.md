---
created: 2022-05-17 21:35
---
tags:: #Mathematics 
up:: [[Geometria Analitica]]
# Superficies Esfericas
![[Superficies Esfericas.canvas]]

La superficie esferica es el lugar geometrico descrito por un punto que se mueve en el espacio de tal forma que siempre su distancia a un punto fijo llamado **centro** es igual a una constante llamada **radio**.

## Ecuaciones
### Ecuacion Vectorial Parametrica
A partir de la condición original tenemos que $$
SE:\overrightarrow P=\overrightarrow C+r\overrightarrow{\mu _{r}}
$$
Donde $P$ es un punto cualquiera de la SE, $C(h,k,l)$ es el centro de la SE y $\overrightarrow{r}$ es un vector cuyo módulo es igual al radio $r$ .

### Ecuación Escalar
$$
|\overrightarrow{P}-\overrightarrow{C}|=r
$$
se obtiene al despejar la ecuación vectorial paramétrica.

### Ecuacion Ordinaria
$$SE:(x-h)^2+(y-k)^2+(z-l)^2=r^2$$
se obtiene elevando al cuadrado ambos miembros de la ecuación escalar.

A partir de esto se sabe que $x^{2}+y^{2}+z^{2}=r^{2}$ es la ecuación de la superficie esferica cuyo centro es el origen de coordenadas, y por lo tanto, es simétrica respecto a este.

### Ecuacion General
$$SE:x^2+y^2+z^2+Dx+Ey+Fz+G=0$$
donde $$C\left( \frac{D}{-2}, \frac{E}{-2}, \frac{F}{-2} \right)$$
$$
r=\frac{1}{2}\sqrt{ D^{2}+E^{2}+F^{2}-4G }
$$

## Posiciones Relativas
### Posiciones Relativas entre SE y Plano
1. Si $d>r$, entonces $\pi$ y SE no se tocan
2. Si $d<r$, entonces $\pi$ y SE cortan generando una circunferencia de interseccion
3. Si $d=r$, entonces $\pi$ es tangente a SE

### Posiciones Relativas entre SE y Recta
1. Si $d>r$, entonces $l$ y SE no se tocan
2. Si $d=r$, entonces $l$ es tangente a SE
3. Si $d<r$, entonces $l$ corta a SE

### Posiciones Relativas entre SE
1. Si $d_1>r_1 \wedge d_2>r_2$ y los signos de $d_1$ y $d_2$ son opuestos, entonces $SE_1$ y $SE_2$ no se tocan exteriormente
2. Si $d_1>r_1 \wedge d_2>r_2$ y los signos de $d_1$ y $d_2$ son iguales, entonces $SE_1$ y $SE_2$ no se tocan interiormente
3. Si $d_1=r_1 \wedge d_2=r_2$ y los signos de $d_1$ y $d_2$ son opuestos, entonces $SE_1$ y $SE_2$ son tangentes exteriormente 
4. Si $d_1=r_1 \wedge d_2=r_2$ y los signos de $d_1$ y $d_2$ son iguales, entonces $SE_1$ y $SE_2$ no se tocan interiormente
5. Si $d_1<r_1 \wedge d_2<r_2$ y los signos de $d_1$ y $d_2$ son opuestos, entonces $SE_1$ y $SE_2$ se cortan exteriormente
6. Si $d_1<r_1 \wedge d_2<r_2$ y los signos de $d_1$ y $d_2$ son iguales, entonces $SE_1$ y $SE_2$ se cortan interiormente

> [!note]+ Distancia entre $SE_1$ y $SE_2$
>
> Para encontrar la distancia entre $SE_1$ y $SE_2$, se utiliza el plano radical $\pi_R$, que es un plano perpendicular a la recta que une los centros de las SE y contiene los puntos comunes a ambas superficies si los hubiere. Su ecuacion se obtiene de la siguiente manera:
> $\pi_R:SE_2-SE_1=0; \overrightarrow{N_R}=(D_2-D_1,E_2-E_1,F_2-F_1$

### Familia de SE
$SE_f:SE_1 + \lambda SE_2=0;\forall \lambda \neq -1$
___
