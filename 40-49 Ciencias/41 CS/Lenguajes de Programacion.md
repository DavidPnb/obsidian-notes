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
De forma similar a como funciona la [[30.06 Sintaxis]] en un lenguaje natural, la sintaxis determina como se deben combinar los simbolos para que el lenguaje interprete el codigo como valido.

## Semantica
A diferencia de la sintaxis, esta se encarga de describir el significado de las operaciones y como afectan al comportamiento de los programas

[[30.07 Semantica]]

## Logica
La logica del codigo no depende de la sintaxis ni el significado, sino del resultado final que se desea que el programa ejecute.

## Tipos
Los tipos en un lenguaje de programación le dicen a este la forma en que debe interpretar los **objetos** de datos.

- **Escalares** - No pueden ser subdivididos
	- **int** - representa un entero; [[Numeros Enteros]]
	- **float** - representa [[Numeros Reales]]
	- **bool** - representa valores booleanos
	- **None** - es un tipo especial de dato que indica que la expresión no devuelve ningun valor
- **No Escalares** - Al igual que con los [[Vectores Geometricos]], son multidimensionales y estan asociados a mas de un valor

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

## Estructuras de Datos
Son las distintas formas en que podemos almacenar datos en un programa, sin tomar en cuenta las propias variables.

### Arrays
Tambien conocidos como **listas** o **vectores** los, **arreglos** almacenan una serie de valores en la memoria de forma secuencial y son las estructuras de datos más simples. La información en los arrays puede ser accedida usando índices. Además, podemos crear **matrices**, que simplemente son arreglos multidimiensionales al igual que las matrices en matemáticas. 

### Strings
Los **strings** son cadenas de caracteres codificados, esto incluye letras, numeros y simbolos; [[Codificacion Binaria]]. Pueden ser representados tanto con comillas simples ( *' '* )  como con comillas dobles ( *" "* ), lo que es util para representar apóstrofes. 

Estos strings pueden **concatenarse**, juntando los caracteres de dos strings en uno solo de forma analoga a la operación de suma. Los strings son objetos no escalares, y pueden usarse como si fueran listas donde cada caracter es un valor diferente. 

Los strings tambien son arrays y los caracteres en ellos pueden ser accedidos con índices.

### Listas Enlazadas
Los elementos contenidos en una **lista enlazada** contienen un valor y una dirección de memoria señala al siguiente valor en la lista, esto permite almacenar información de forma más dinamica que un array. Las listas enlazadas pueden ser **circulares**, con el ultimo elemento señalando al primero como elemento siguiente, o el ultimo elemento puede señalar a un valor nulo (**NULL**), que señala el final de la lista enlazada.

Las listas enlazadas pueden ser representadas como **queues** en donde el primer elemento que se añade es el primero en ser removido (**FIFO**), o como **stacks** donde el ultimo elemento que se añade es el primero en ser removido (**LIFO**). Los procesos de añadir y remover elementos de un queue son llamados **enqueue** y **dequeue** respectívamente, en un stack son **push** y **pop**.

### Arboles
Son formas de representar la información de manera jerarquica, con elementos **padre** que señalan a elementos **hijos**. El elemento **raíz** no tiene elementos padre y los elementos **hoja** que no tienen hijos.

### Grafos
Funcionan como arboles sin el elemento jerárquico en donde todos los elementos, llamados **nodos**, pueden conectarse entre si.

### Structs
Tambien son llamados **objetos** y permiten almacenar multiples variables asociadas. Son la manera más facil de almacenar información compuesta y representar objetos de la vida real.

## Funciones
Son piezas de codigo reusables a las que se les da un nombre y pueden ser utilizadas en varias partes de un programa. La creación de funciones es la principal manera en la que se crean **abstracciones** y **modularidad**, que son la parte más esencial de un programa moderno porque mejoran la **legibilidad** y hacen que los proyectos sean más **escalables**. La abstracción implica que al introducir información adecuada siempre se va a recibir información adecuada, sin la necesidad de preocuparse por el funcionamiento interno del codigo. La modularidad significa que diferentes piezas de codigo separadas cumplen una funcionalidad separada, y en conjunto producen la funcionalidad del programa completo.

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

## Recursión
Las funciones recursivas son funciones que se llaman a si mismas dentro de su codigo. Este proceso es similar a como funciona la recursión en las matemáticas. Para utilizar la recursión se divide un problema en problemas cada vez más simples hasta que se llega al caso más simple, que puede ser resuelto directamente. La recursión es comúnmente vista como una alternativa a la iteración que se ve en los bucles, en la que se sacrifica tiempo de computo por legibilidad para el programador.
___
