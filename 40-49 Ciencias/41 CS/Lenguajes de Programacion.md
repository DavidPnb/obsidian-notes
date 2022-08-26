---
status:
references:
created: 2022-06-23 15:40
---
tags:: #on/CS 
up:: [[41.00 Ciencias de la Computacion MOC]]
Links: 
# Lenguajes de Programacion
Estos son los que interpretan las intrucciones dadas por el programador en lenguaje entendible por el humano y lo transforman en algo que la computadora puede entender. Esta formado por valores primitivos (numeros, caracteres), operaciones y combinaciones de operaciones mas complejas que devuelven un valor llamadas expresiones. Tambien contienen una serie de abstracciones que permiten tratar esas expresiones como valores primitivos.

## Sintaxis
De forma similar a como funciona la [[Sintaxis]] en un lenguaje natural, la sintaxis determina como se deben combinar los simbolos para que el lenguaje interprete el codigo como valido.

## Semantica
A diferencia de la sintaxis, esta se encarga de describir el significado de las operaciones y como afectan al comportamiento de los programas

[[Semantica]]

## Logica
La logica del codigo no depende de la sintaxis ni el significado, sino del resultado final que se desea que el programa ejecute.

## Tipos
Los tipos en un lenguaje de programación le dicen a este la forma en que debe interpretar los **objetos** de datos.

- **Escalares** - No pueden ser subdivididos
	- **int** - representa un entero; [[Numeros Enteros]]
	- **float** - representa [[Numeros Reales]]
	- **bool** - representa valores booleanos
	- **None** - es un tipo especial de dato que indica que la expresión no devuelve ningun valor
- **No Escalares** - Al igual que con los [[Vectores]], son multidimensionales y estan asociados a mas de un valor

## Operaciones
Las operaciones fundamentales de un lenguaje de programación son:
- Suma
- Resta
- Multiplicación
- División
- Resto de la División
- Potencias

[[Aritmetica]]

Estas siguen el orden de las operaciones, y se pueden usar parentesis para especificar un orden de evaluación especifico

## Variables
Las variables son una forma de asignar una referencia en la memoria con un valor y relacionarla con un nombre para ser usada mas tarde ; [[Arquitectura de Computadoras]] . Esta es la principal manera de mantener **abstracción** en un lenguaje de programación, lo que facilita mucho la forma en que creamos y mantenemos nuestros programas.

Esto no hace más que asociar la variable con un valor, por lo que se puede sobreescribir el valor de la variable siempre que se quiera.

## Control de Flujo
Es lo que separa a un lenguaje de programación de una calculadora permitiendo al programa realizar dependiendo de si se cumplen o no una serie de condiciones logicas y/o matematicas. El tipo más simple son los **condicionales**, que ejecutan codigo solo si se cumple una condición.

El otro tipo de estructura de control es el **bucle**, que ejecuta el codigo una cierta cantidad de veces dependiendo de la condición.

## Strings
Los **strings** son cadenas de caracteres codificados, esto incluye letras, numeros y simbolos; [[Codificacion Binaria]]. Pueden ser representados tanto con comillas simples ( *' '* )  como con comillas dobles ( *" "* ), lo que es util para representar apóstrofes. 

Estos strings pueden **concatenarse**, juntando los caracteres de dos strings en uno solo de forma analoga a la operación de suma. Los strings son objetos no escalares, y pueden usarse como si fueran listas donde cada caracter es un valor diferente. 

## Funciones
Son piezas de codigo reusables a las que se les da un nombre y pueden ser utilizadas en varias partes de un programa. La creación de funciones es la principal manera en la que se crean **abstracciones** y son la parte más esencial de un programa moderno, porque mejoran la **legibilidad** y **modularidad** haciendo que los proyectos sean más **escalables**.

## Algoritmos
Un **algoritmo** es una serie de pasos que se realizan para resolver un problema específico. Tienen su origen el [[Algebra Elemental]] y su uso en [[40.00 Matematicas MOC|Matematicas]] tambien se extiende a la programación. 

La eficiencia de un algoritmo es estudiada en Analisis de Algoritmos.

## Input / Output
La mayoria de lenguajes de programación de propósito general tienen metodos para recibir información directamente del usuario, considerada como **input**; además, deben tener una manera de hacerle llegar información al usuario, llamada **output**, esto usualmente se hace mostrando texto en la consola.

## IDE

Los **entornos de desarrollo integrados** son herramientas diseñadas para facilitar la tarea de escribir codigo en un lenguaje de programación específico. Estos disponen de 3 funciones principales:
1. **Editor de Texto** - Similar a los editores de texto plano, pero tambien suele incluir **autocompletado** y **syntax highlightning**
2. **Shell** - Permite interactuar con el codigo que escribimos
3. **Debugger** - Ayuda a detectar **bugs** y diagnosticar problemas en el codigo
___
