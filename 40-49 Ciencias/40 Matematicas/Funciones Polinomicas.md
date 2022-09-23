---
created: 2022-09-23 13:16
---
tags:: #Mathematics 
up:: [[Funciones]]
# Funciones Polinomicas
Una ecuación racional integral de grado $n$ en la variable $x$ es una ecuación que puede ser escrita en la forma $$a_nx^n + a_{n-1}x^{n-1} + a_{n-2}x^{n-2} + \dots + a_1x + a_0 = 0, \; a_n \neq 0$$
Donde $n$ es un entero positivo y $a_n, a_{n-1}, a_{n-2}, \dots, a_1, a_0$ son constantes. El coeficiente de mayor grado es llamado el **coeficiente principal** y $a_0$ es llamado el **termino constante**.

Un polinomio de grado $n$ en la variable $x$ es una función de $x$ que puede ser escrita en la forma $$P(x) = a_nx^n + a_{n-1}x^{n-1} + a_{n-2}x^{n-2} + \dots + a_1x + a_0, \: a_n \neq 0$$
Donde $n$ es un entero positivo y $a_n, a_{n-1}, a_{n-2}, \dots, a_1, a_0$ son constantes. Entonces, $P(x) = 0$ es una ecuación racional integral de grado $n$ en la variable $x$ . Cualquier valor de $x$ que elimina a $P(x)$ es llamado una **raíz** de $P(x) = 0$ .

## Ceros de Ecuaciones Polinomicas


> [!teorema]- 1. Teorema del Resto
> Si $r$ es cualquier constante y un polinomio $P(x)$ es dividido por $(x-r)$, el resto es $P(r)$

> [!teorema]- 2. Teorema del Factor
> Si $r$ es una raíz de la ecuación $P(x) = 0$, $(x - r)$ es un factor de $P(x)$ . El converso tambien es verdadero

> [!teorema]- 3. División Sintética
> Es un método simplificado de dividir un polinomio $P(x)$ por $(x-r)$, donde $r$ es cualquier numero asignado. Este método es análogo al algoritmo de división tradicional

> [!teorema]- 4. Teorema Fundamental del Algebra
> Toda ecuación polinómica $P(x)=0$ tiene al menos una raíz
   
> [!teorema]- 5. Numero de Raices de una Ecuación
>  Una ecuación $P(x)=0$ de grado $n$ tiene $n$ raices

## Resolución de Ecuaciones Polinomicas
1. Raices Complejas e Irracionales
	1. Si un numero complejo es raíz de la ecuación integral racional $P(x)=0$ con coeficientes reales, el conjugado de este numero tambien es una raíz
	2. Si la ecuación integral racional $P(x)=0$ tiene como raíz al binomio $a + b\sqrt{x}$ , el conjugado de este binomio tambien es raíz de la ecuación
2. Teorema de Raíz Racional
	1. Si $b/c$ , una fracción en sus terminos más simples, es una raiz de la ecuación $$a_nx^n + a_{n-1}x^{n-1} + a_{n-2}x^{n-2} + \dots + a_1x + a_0 = 0, \; a_n \neq 0$$ con coeficientes enteros, entonces $b$ es un factor de $a_0$ y $c$ es un factor de $a_n$
3. Teorema de Raíz Integral
	1. Si una ecuación $P(x)=0$ tiene coeficientes enteros y el coeficiente principal es $1$ , las raices de $P(x) = 0$ son enteros y factores de $a_0$ 
4. Teorema del Valor Medio
	1. Si $P(x)$ es una ecuación polinómica con coeficientes reales, se pueden aproximar las raices al buscar los puntos de la grafica en donde $y=0$ 
5. Límites Superiores e Inferiores de Raices Reales
	1. Un numero $a$ es llamado **límite superior** de las raices reales de $P(x)$ si no hay raíz más grande que $a$. Un numero $b$ es llamado **límite inferior** de las raices reales de $P(x)$ si no hay raíz más pequeña que $a$.
	   Siendo $P(x) = a_nx^n + a_{n-1}x^{n-1} + a_{n-2}x^{n-2} + \dots + a_1x + a_0 = 0$ donde $a_0, a_1, \dots, a_n$ son números reales y $a_n>0$ , entonces
		1. Si bajo división sintética de $P(x)=0$ por $(x-a)$ , donde $a \geq 0$ , todos los números obtenidos en la tercera fila son positivos o cero, entonces $a$ es un límite superior para todas las raices reales de $P(x)$
		2. Si bajo división sintética de $P(x)=0$ por $(x-b)$ , donde $b \geq 0$ , todos los números obtenidos en la tercera fila se alternan entre positivos y negativos o son cero, entonces $b$ es un límite inferior para todas las raices reales de $P(x)$
6. Regla de los Signos de Descartes
	1. Si los terminos de un polinomio con coeficientes reales son ordenados por grados descendientes de $x$ , entonces una variación de signo ocurre cuando dos terminos consecutivos difieren en signo. El numero de raices positivas de $P(x)=0$ es igual al número de variaciones de signo o es menor que ese número por un entero positivo

## Aproximación de Ceros Reales
Para esto se usa el Teorema del Valor Medio para encontrar un intervalo lo suficientemente pequeño en donde se encuentre una raíz.
___
