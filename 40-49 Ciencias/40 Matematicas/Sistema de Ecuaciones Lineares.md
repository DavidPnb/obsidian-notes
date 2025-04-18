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

## Eliminación Gaussiana
Es un método usado para resolver matrices $n\times m$ .
1. Se toman múltiplos de la primera ecuación y se suman a las demás ecuaciones de modo que se elimine la primera variable
2. Se pasa a la segunda ecuación y la segunda incognita y se repite el proceso
3. Se continua hasta que se obtiene un **sistema triangular** en el cual cada ecuación tiene una incognita menos que su ecuación precedente (a excepción de la primera)

Al terminarse este proceso se lleva a cabo un proceso de sustitución empezando por la última ecuación.

El primer coeficiente de cada ecuación del sistema triangular es llamado **pivot**. Si uno de los pivots es igual a cero, el sistema no tiene solución o tiene soluciones infinitas.

La eliminación gaussiana tiene un costo computacional de $\frac{1}{3}n^{3}$ operaciones y la sustitución de $\frac{n^{2}}{2}$ aproximadamente.

## Matrices
Un sistema de ecuaciones puede representarse a través de una **matriz** de modo que las filas representen ecuaciones y las columnas representen variables. En este sentido un vector puede ser considerado una matriz de $n$ dimensiones.

### Operaciones
La suma se puede realizar en matrices con las mismas dimensiones y los índices de la matriz resultante son igual a la suma de los índices correspondientes de los operandos.

La multiplicación se realiza con una matriz con $m\times n$ dimensiones y una matriz de $n\times p$ dimensiones, lo que resulta en una matriz de $m\times p$ dimensiones. El índice $a_{ij}$ de la matriz resultante es igual al producto punto entre la fila $i$ de la primera matriz y la columna $j$ de la segunda matriz.

### Propiedades
1. Las operaciones con matrices son distributivas
2. Las operaciones con matrices son asociativas
3. La multiplicación de matrices no es conmutativa

### Factorización
Una matriz $Ax=b$ puede convertirse en una matriz $Ux=c$ , donde $U$ es una **matriz triángular superior** por medio de un proceso de eliminación. $A=LU$ con $L$ como la **matriz triángular inferior** que revierte la eliminación. Una matriz tambien puede resolverse como $A=LDU$ donde $D$ contiene los pivotes del $U$ original y la diagonal de $U$ esta formada por $1$.

## Determinantes
[[Determinantes]]
___
