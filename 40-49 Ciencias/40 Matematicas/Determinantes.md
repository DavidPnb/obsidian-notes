---
created: 2022-12-07 13:26
---
tags:: #Mathematics 
up:: [[Algebra Lineal]]
# Determinantes
## Segundo Orden
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

## Tercer Orden
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
