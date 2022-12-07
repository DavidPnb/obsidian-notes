---
created: 2022-08-29 11:22
---
tags:: #Mathematics 
up:: [[Ecuaciones Lineares]]
Links: 
# Sistema de Ecuaciones Lineares
## Sistema de Dos Incognitas
Una ecuación linear de dos variables $x$ y $y$ es una ecuacion de la forma $ax + by = c$ , donde $a, b, c$ pertenecen a los [[Numeros Reales]] y no son todos cero. Si consideramos dos o más de estas ecuaciones: $$\begin{array}{lcl} a_1x & + & b_1y & = & c_1 \\ a_2x & + & b_2y & = & c_2 \\ \vdots &  & \vdots & & \vdots \\ a_nx & + & b_ny & = & c_n \end{array}$$ Tenemos un **sistema de ecuaciones lineares con dos incognitas**. Un par de valores $x$ y $y$ $(x, y)$ que satisface todas las ecuaciones es conocido como una **solución simultanea**.

### Metodos de Resolución
1. **Reducción** - De ser necesario se multiplican las ecuaciones por numeros que hagan que los coeficientes de una incógnita sean numericamente iguales en dos de las ecuaciones, luego se restan ambas ecuaciones si sus signos son iguales, o se suman si sus signos son diferentes; se resuelve la ecuación resultante para encontrar el valor de una de las incognitas
2. **Sustitución** - Se resuelve una de las ecuaciones para una incognita y el resultado se sustituye en otra ecuación para encontrar el valor de la otra incognita
3. **Método Gráfico** - Se grafican las ecuaciones, la solución es el punto de intersección de todas; [[Rectas en el Plano]]

Si son [[Rectas Paralelas]], entonces las ecuaciones son **inconsistentes** y no tienen solución simultanea. Las ecuaciones son **consistentes** si se intersectan y, por lo tanto, hay una única solución. Si las ecuaciones representan a la misma recta, las ecuaciones son **dependientes** y el sistema tiene infinitas soluciones. Si los métodos de resolución algebraicos resultan en un enunciado que es siempre verdadero, las ecuaciones son dependientes; si resultan en un enunciado que es siempre falso, las ecuaciones son inconsistentes.

## Sistema de Ecuaciones con Tres Incognitas
Un **sistema de ecuaciones lineales con tres incognitas** se resuelve al eliminar una incognita de una ecuación y luego eliminar esa incognita de las otras dos ecuaciones. Las ecuaciones de tres incognitas representan [[Planos]], y estos planos pueden ser paralalelos e **inconsistentes**; coincidir o intersectarse en una recta, siendo **dependientes**; o intersectarse en un punto y ser **consistentes**

Estas ecuaciones tienen la forma $ax + by + cz = d$ , donde donde $a, b, c, d$ pertenecen a los [[Numeros Reales]] y no son todos cero. Si consideramos tres ecuaciones: $$\begin{array}{lcl} a_1x+b_1y+c_1z & = & d_1 \\ a_2x+b_2y+c_2z & = & d_2 \\ a_3x+b_3y+c_3z & = & d_3 \end{array}$$
y encontramos un valor $(x, y, z)$ que satisfaga todas, se dice que tenemos una **solución simultanea** para el sistema de ecuaciones

## Determinantes
$$
\begin{vmatrix}
a_{1} & b_{1} \\
a_{2} & b_{2}
\end{vmatrix}
$$ es un **determinante de segundo orden** donde $a_{1},b_{1},a_{2},b_{2}$ son los **elementos** del determinante, y $a_{1}b_{2}-b_{1}a_{2}$ es conocida como la **expansión** del determinante. Este determinante puede usarse para resolver sistemas de ecuaciones lineales de la forma $$\begin{array}{lcl} \\
a_{1}x & + & b_{1}y & = & c_{1} \\
a_{2}x & + & b_{2}y & = & c_{2}
\end{array}
$$
Si el determinante asociado a este sistema es diferente de cero, significa que el sistema tiene solución, la cual se expresa como $$
x=\frac{\begin{vmatrix}
c_{1} & b_{1} \\
c_{2} & b_{2}
\end{vmatrix}}{\begin{vmatrix}
a_{1} & b_{1} \\
a_{2} & b_{2}
\end{vmatrix}}
$$
$$
y=\frac{\begin{vmatrix}
a_{1} & c_{1} \\
a_{2} & c_{2}
\end{vmatrix}}{\begin{vmatrix}
a_{1} & b_{1} \\
a_{2} & b_{2}
\end{vmatrix}}
$$
Se puede observar que el denominador es el determinante del sistema y el numerador es igual al denominador con la columna de los coeficientes de las variables reemplazada por la columna de los coeficientes.

Los **determinantes de tercer orden** pueden ser expresados en términos de los determinantes de segundo orden como $$
\begin{vmatrix}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{vmatrix}
= a_{1}
\begin{vmatrix}
b_{2} & c_{2} \\
b_{3} & c_{3}
\end{vmatrix} -b_{1}\begin{vmatrix}
a_{2} & c_{2} \\
a_{3} & c_{3}
\end{vmatrix} +c_{1}\begin{vmatrix}
a_{2} & b_{2} \\
a_{3} & b_{3}
\end{vmatrix}
$$ donde los determinantes de segundo orden son llamados **menores**. El valor de una determinante de tercer orden tambien se puede encontrar al multiplicar los elementos de cualquier columna o fila por sus menores y asignando los siguientes signos
$$
\begin{vmatrix}
+ & - & + \\
- & + & - \\
+ & - & +
\end{vmatrix}
$$
Estos determinantes pueden usarse para resolver sistemas lineares de la forma $$
\begin{array}{lcl} a_1x+b_1y+c_1z & = & d_1 \\ a_2x+b_2y+c_2z & = & d_2 \\ a_3x+b_3y+c_3z & = & d_3 \end{array}
$$ con soluciones $$
x=\frac{\begin{vmatrix}
d_{1} & b_{1} & c_{1} \\
d_{2} & b_{2} & c_{2} \\
d_{3} & b_{3} & c_{3}
\end{vmatrix}}{\begin{vmatrix}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{vmatrix}}
$$
$$
y=\frac{\begin{vmatrix}
a_{1} & d_{1} & c_{1} \\
a_{2} & d_{2} & c_{2} \\
a_{3} & d_{3} & c_{3}
\end{vmatrix}}{\begin{vmatrix}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{vmatrix}}
$$
$$
z=\frac{\begin{vmatrix}
a_{1} & b_{1} & d_{1} \\
a_{2} & b_{2} & d_{2} \\
a_{3} & b_{3} & d_{3}
\end{vmatrix}}{\begin{vmatrix}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{vmatrix}}
$$
Este procedimiento para resolver sistemas 2x2 y 3x3 usando determinantes se llama **regla de Cramer** y puede ser extendido a sistemas de ecuaciones $n\times n$ .
___
