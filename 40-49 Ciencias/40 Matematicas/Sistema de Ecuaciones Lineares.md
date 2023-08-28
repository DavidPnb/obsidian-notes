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


## Determinantes
[[Determinantes]]
___
