---
created: 2022-08-22 10:15
---
tags:: #Mathematics 
up:: [[Geometria Analitica]]
Links: 
# Rectas en el Plano
![[Rectas en el Plano.canvas]]
## Pendiente de una Recta
El **ángulo entre rectas dirigidas** es el ángulo formado por los lados que se alejan del vértice.

El **ángulo de inclinación** de una recta es el ángulo que esta forma con la dirección positiva del eje $X$ si se considera que la recta está dirigida hacia arriba.

La **pendiente** de una recta es la tangente de su ángulo de inclinación.

> [!teorema]+
> Si $(x_1, y_1)$ y $(x_2, y_2)$ son dos puntos pertenecientes a la recta y $m$ es la pendiente de la recta, entonces $$m = \frac{y_2 - y_1}{x_2 - x_1} ; \; x_2 \neq x_1$$

Este teorema puede demostrarse por medio de trigonometría.

Si la pendiente es negativa, significa que al ver el grafico de izquierda a derecha el valor de $y$ se reduce a medida que $x$ incrementa. Si es positiva, $y$ incrementa junto con $x$ . Además, el [[Valor Absoluto]] de la pendiente indica que tan empinada es la recta.

## Propiedades de una Recta
La característica principal de una recta es la pendiente es constante a lo largo de la misma, lo que permite definir a la recta por medio de su pendiente y un punto perteneciente a esta.

## Ecuaciones
### Ecuación Vectorial Paramétrica
Se obtiene al expresar las propiedades de una recta por medio de [[Vectores Geometricos]]. $$
L:\overrightarrow P=\overrightarrow{P_{1}}+\lambda \overrightarrow{L}
$$
donde $\overrightarrow{P_{1}}\in L$ y $\overrightarrow{L}\parallel L$

### Ecuación Paramétrica
Se obtiene conociendo los valores de $\overrightarrow{P_{1}}$ y $\overrightarrow{L}$ en la ecuación vectorial paramétrica. $$
\begin{align}
x & =  x_{1}  +\lambda   Lx \\
y & =  y_{1}  +\lambda Ly
\end{align}
$$

### Forma Punto-Pendiente de la Ecuación de la Recta
Si una recta tiene pendiente $m$ pasa por el punto $(x_1, y_1)$ , entonces por cualquier otro punto $(x,y)$ en la recta se tiene $$m = \frac{y - y_1}{x - x_1}$$ y $$y - y_1 = m(x - x_1)$$
### Forma de Dos Puntos de la Ecuación de la Recta
Si una recta pasa por los puntos $(x_1, y_1)$ y $(x_2, y_2)$ , entonces su pendiente es  $$m = \frac{y_2 - y_1}{x_2 - x_1}$$
Sustituyendo esta expresión en la ecuación punto-pendiente se tiene $$y - y_1 = \frac{y_2 - y_1}{x_2 - x_1} (x - x_1)$$
### Forma Pendiente-Intecepto de la Ecuación de la Recta
Si una recta tiene pendiente $m$ e intercepto en $y$ igual a $(0, b)$ , entonces  para cualquier punto $(x,y)$ donde $x \neq 0$ $$m = \frac{y - b}{x - 0}$$ y $$y = mx + b$$

### Forma Intercepto de la Ecuación de la Recta
Si una recta tiene $a$ intercepto en $x$ y $b$ intercepto en $y$ , pasa por los puntos $(a,0$) y $(0, b)$ . La ecuación de la recta es $$y - b = \frac{0 - b}{a - 0} (x - 0) \; ; a \neq 0$$
que se simplifica a $bx + ay = ab$ . Si $a$ y $b$ son diferentes de cero tenemos $$\frac{x}{a} + \frac{y}{b} = 1$$
### Recta Paralela al Eje Y
$x=k$ , donde $k$ es una constante, es la ecuación de una **recta vertical** cuya pendiente no esta definida, debido a que todos los valores de $x$ son iguales y la división entre cero no esta definida. 

### Forma General
Toda recta puede representarse por una ecuación de la forma $$
Ax+By+C=0
$$ donde $A$ y $B$ no pueden ser igual a cero al mismo tiempo. Esto significa que todas las rectas pueden representarse por una ecuación de primer grado, y reciprocamente.

Esta ecuación puede ser convertida a la forma pendiente-intercepto, que permite conocer la pendiente de la recta y su intercepto con $Y$ .

### Forma Normal
$$
x\cos(\omega)+y\sin(\omega)-h=0
$$
donde $\omega$ es el ángulo de inclinación de recta perpendicular y $h$ es la distancia desde la recta al origen. Esta ecuación puede obtenerse al despejar la fórmula de la distancia al origen.

### Forma Determinante
$$
\begin{vmatrix}
x & y & 1 \\
x_{1} & y_{1} & 1 \\
x_{2} & y_{2} & 1
\end{vmatrix}=0
$$
Se obtiene usando sistema de ecuaciones en donde las incognitas son los coeficientes de la ecuación general.

## Ángulo entre Rectas
El **ángulo entre dos rectas** viene dado por la formula $$
\tan(\theta)=\frac{m_{2}-m_{1}}{1+m_{1}m_{2}}
$$
A partir de esto se pueden obtener las siguientes conclusiones:

Dos rectas no verticales son **paralelas** si y solo si sus pendientes son iguales.

Dos rectas no verticales son **perpendiculares** si y solo si el producto de sus pendientes es igual a $-1$ .

## Posiciones Relativas
### Entre Rectas
Si dos rectas son **paralelas** entonces $$A_{1}B_{2}-A_{2}B_{1}=0$$, si las rectas no son paralelas entonces se intersectan en un punto.

Si dos rectas son **perpendiculares** entonces $$
A_{1}A_{2}+B_{1}B_{2}=0
$$
Si dos rectas son **coincidentes**, sus coeficientes son proporcionales.

## Distancias
### Distancia al Origen
Se obtiene al proyectar el vector de posición de la recta sobre un vector perpendicular a esta y obtener la longitud, lo que se expresa como $$
h=\overrightarrow P \cdot \overrightarrow{\mu_{N}}
$$
### Distancia a un Punto
$$
d=\frac{|Ax+By+C|}{\sqrt{ A^{2}+B^{2} }}
$$

## Familia de Rectas
Conjunto de rectas que satisfacen una única condición geométrica.

### Familia de Rectas Paralelas
$$y=mx+k$$

### Familia de Rectas que Pasan por un Punto
$$
y-y_{1}=k(x-x_{1})
$$

### Familia de Rectas que Pasan por la Intersección de Dos Rectas
$$
A_{1}x+B_{1}y+C_{1}+k(A_{2}x+B_{2}Y+C_{2})=0
$$
___
