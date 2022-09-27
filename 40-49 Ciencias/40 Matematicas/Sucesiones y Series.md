---
created: 2022-09-26 10:04
---
tags:: #Mathematics 
up:: [[Algebra Elemental]]
# Sucesiones y Series
Las **sucesiones** son [[Funciones]] definidas en el conjunto de los [[Numeros Enteros]] positivos. Los números en la sucesión son llamados **términos**. Las **series** son la suma de los términos de una sucesión infinita, por esta razón, tambien se las conoce como **series infinitas**. Las sucesiones y series entran en la categoría de **progresiones** debido a que el orden de los elementos del conjunto si importan y repetir términos tambien puede afectar el orden de la progresión

Las sucesiones son la base de muchas estructuras en [[Lenguajes de Programacion]]. Las series han sido malinterpretadas por mucho tiempo debido a que en la antigüedad el hecho de que una suma infinita pudiera resultar en un número finito era considerado paradójico. Esto cambio con la invención del Cálculo y los límites.

## Sucesiones Aritméticas
Son sucesiones en las que cada término es obtenido al sumar el término anterior con una constante llamada **diferencia común**.

### Fórmulas
1. **Término enésimo** $l=a+(n-1)d$
2. **Suma de los primeros n términos** $S=\frac{n}{2}(a+l)=\frac{n}{2}[2a+(n-1)d]$

Donde $a$ es el primer término, $d$ es la diferencia común, $n$ es el número de términos, $l$ es el término enésimo y $S$ es la suma de los primeros $n$ términos.

## Sucesiones Geométricas
Son sucesiones en las que cada término es obtenido al multiplicar el término anterior por una constante llamada **razón común**.

### Fórmulas
1. **Término enésimo** $l=a^{n-1}$
2. **Suma de los primeros n términos** $S=\frac{a(r^{n}-1)}{r-1}=\frac{rl-a}{r-1}$ 

Donde $a$ es el primer término, $r$ es la razón común, $n$ es el número de términos, $l$ es el término enésimo y $S$ es la suma de los primeros $n$ términos.

## Series Geométricas Infinitas
La suma hasta infinito ($S_{\infty}$) de cualquier sucesión geométrica en donde la razón común es numéricamente menor que uno es dada por $$
S_{\infty}= \frac{a}{1-r}, \text{ donde } |r| \leq 1
$$
## Sucesiones Harmónicas
Una sucesión harmónica es una sucesión de números en donde sus recíprocos forman una sucesión aritmética.

## Medias
Los términos entre dos términos cualquiera de una sucesión son las **medias** entre esos dos términos.
___
