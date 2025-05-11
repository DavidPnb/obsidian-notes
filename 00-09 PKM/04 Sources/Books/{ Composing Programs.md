 ---
alias: 
created: 2025-04-03 12:53

---
[[41.00 Ciencias de la Computacion MOC|Ciencias de la Computacion]]

# { Composing Programs
```toc
```
## Abstracciones con Funciones
Python 3 esta compuesto por los siguientes elementos fundamentales que pueden combinarse entre si para producir instrucciones complejas:
- **declaraciones** - Son los elementos que comunican instrucciones al lenguaje
- **expresiones** - Representan operaciones que al ser computadas resultan en un valor
- **funciones** - Permiten encapsular el codigo en una lógica interna capaz de manipular información
- **objetos** - Arreglos que permiten la organización de datos

### Elementos de Programación
Un lenguaje de programación no solo le comunica instrucciones de bajo nivel a una computadora. Este debe ser capaz de permitir la organización de ideas que puedan ser interpretadas por los programadores que mantengan el código. Para eso, un lenguaje debe tener las siguientes capacidades:
- **declaraciones y expresiones primitivas**
- **medios de combinación** - que produzcan un resultado compuesto a partir de elementos primitivos
- **medios de abstracción** - que asignen un resultado compuesto a un nombre, tratandolo como una sola unidad de código

Estas capacidades deben poder ser implementadas dentro de funciones y datos. Los datos son representaciones de información, y las funciones son las reglas de manipulación de estos datos. Las funciones pueden clasificarse de dos maneras: las **funciones puras** reciben información como parámetros y retornan un valor. Las **funciones no puras** realizan acciones que cambian el estado del interprete y no necesariamente retornan un valor. Las funciones puras son más usadas debido a que el mismo input siempre retorna el mismo resultado, lo que las hace más facil de probar. Las **expresiones de llamada** dan como resultado el valor de retorno de una función, y son el tipo de expresión más usada. El principal método de abstracción es  el uso de **variables** que asignan un nombre a un valor y lo almacenan en el entorno.

### Definición de Funciones
Una función puede ser definida usando la declaración 

``` python

def nombre(n1,n2,...,nk): 
	cuerpo
```

Los elementos dentro del paréntesis son llamados **parámetros formales**. Al llamar a una función se asigna cada argumento a su parametro formal respectivo. Dentro del entorno, cada función llama a un nuevo **frame** y le añade el contenido de los parametros formales como **variables locales**. Un frame tiene acceso a sus variables locales y a las variables de todos los frames superiores, incluyendo el **frame global** que contiene a todos los demás. La definición de funciones permite abstraer la lógica de un código. Una vez que una función es definida, la implementación de su lógica pasa a segunda plano. Para usarla solo se necesita conocer el **dominio** (valores que toma la función), el **rango** (valor que retorna la función) y el **propósito** (la relación entre el dominio y el rango).

### Diseño de Funciones
Las funciones ideales deben cumplir con un único propósito, y este debe poder ser expresado en menos de una línea. Además, una función puede ser usada para encapsular código repetido. Para eso, la lógica de una función debe ser lo más general posible. El uso tres comillas (`"""`) al comienzo del cuerpo de una función permite crear una documentación. En esta se puede expresar el propósito de la función y describir los parámetros usados. Los comentarios pueden usarse con el 
simbolo `#` al final de una línea, creando texto que solo los humanos pueden leer. Los **parámetros por defecto** se pueden definir junto con la función; estos reemplazan a su argumento respectivo en caso de que este no sea especificado al llamar la función.

### Control
El interprete de Python ejecuta declaraciones línea por línea, a menos que una declaración cambio el flujo de ejecución del programa. Una declaración compuesta tiene la forma

``` python
cabezera:
	cuerpo
```
donde la **cabezera** determina la forma en que se ejecuta el código en el **cuerpo**. Los **condicionales** evaluan una expresión y ejecutan el código en su cuerpo si esta expresión es equivalente a verdadero. Los **bucles** ejecutan el código en su cuerpo cierto número de veces dependiendo del resultado de su expresión. Estas expresiones son evaluadas en base a la lógica booleana. Una función también es una declaración compuesta.

### Funciones de Orden Superior
Permiten abstraer los procesos de computación que se utilizan en un programa. Una función puede ser usada como argumento de otra función, de esa forma se puede abstraer un proceso que manipula diferentes datos. Una función puede ser definida dentro de otra función; la función tiene acceso al entorno de la función en la que esta definida y la función solo forma parte del entorno mientras se llama a la función superior. Una función puede ser retornada por otra función. A partir de esto se pueden componer funciones. 

El **currying** es un proceso mediante el cual una función que toma varios argumentos se transforma en una función compuesta que toma un solo argumento. Los **lambdas** son funciones que no tienen un nombre y solo estan compuestas por una expresión de retorno

``` python
(x1,x2,...,x3): expresión
```

Los **decoradores** simplifican el  llamado de una función compuesta en una declaración.

``` python
def funcion1

@funcion1
def funcion2
```

es equivalente a

``` python
def funcion1

def funcion2

funcion1 = funcion2(funcion1)
```

### Recursión
Una **función recursiva** es una función que se llama a sí misma en su propio cuerpo. Una funcion recursiva divide un problema en problemas más simples para encontrar una solución. Suele tener una **base** que describe la solución del caso más simple, y un elemento recursivo que aplica la función a una versión más simple del problema. Dos funciones son **mutuamente recursivas** si cada una llama a la otra dentro de su cuerpo. Estas pueden usarse para abstraer una lógica de recursión compleja. Un **árbol de recursión** es una función que tiene más de un elemento recursivo; cada uno explorando distintas posibilidades de un problema.

## Abstracciones con Datos
Los **tipos de datos nativos** evaluan a un valor literal, este valor literal puede ser procesado por el lenguaje. Python reconoce tres tipos de datos numéricos: *int* (enteros), *float* (reales) y *complex* (complejos). Los floats solo son capaces de representar números de forma aproximada, por lo que no deben ser usados en comparaciones que requieran de precisión. La **abstracción de datos** se usa para manipular datos sin la necesidad de conocer como estos datos estan implementados. Siempre y cuando el comportamiento general no cambie, estas abstracciones ayudan a mantener la longevidad del programa.

## Secuencias
Las secuencias son datos que tienen una longitud `n` y contienen elementos que van desde una posición `0` hasta `n-1`. Se puede determinar si un elemento pertenece a una secuencia y se puede dividir una secuencia en secuencias más pequeñas. Las **listas** son las secuencias arquetipicas. Las listas admiten una operación de suma, que resulta en una lista con los elementos de otras dos. Multiplicar una lista por un entero positivo `n` crea una lista con cada elemento de la lista original repetido `n` veces. El bucle `for` permite iterar por cada elemento dentro de una secuencia. 
```python
for elemento in secuencia:
	proceso
```

Los **rangos** son secuencias que incluyen cada entero que se encuentra entre dos enteros positivos, incluyendo al primero. Los **strings** son secuencias de caracteres. Cada caracter es representado como un string de longitud 1; por esto, la operación de membresía verifica si un string se encuentra dentro de otro. La comprensión de listas permite crear una lista a partir de una secuencia. 
```python
[operación for elemento in secuencia if filtro]
```
La agregación de listas en un proceso donde se combinan los elementos de una lista en un solo valor. Los procesos de comprensión y agregación pueden ser replicados por funciones de orden superior.

## Objetos
Son representaciones de datos que tienen un comportamiento que cambia con el tiempo, y es almacenado en un **estado**. Los objetos contienen **atributos** con los datos que almacena el objeto y **métodos**, funciones que realizan operaciones en el objeto. Todos los datos en Python son objetos. Los objetos **inmutables** no cambian de valor; los **mutables** tienen un estado que puede cambiar durante la ejecución de un programa. La declaración `nonlocal` permite a una función almacenar un estado. Con esta, una asignación ccambia el valor de una variable en el entorno que es definida por primera vez. Los objetos modelan entidades modulares que pueden interactuar entre ellas.

La **comparación de identidad** `is` compara igualdad de dos objetos independientemente de su contenido. Si dos variables se refieren al mismo objeto mutable, cambiar el valor de una automaticamente cambia el valor de la otra (las comprensiones de lista crean una lista nueva). Los **diccionarios** son conjuntos no ordenados que almacenan valores usando **llaves** en lugar de índices. Una llave puede ser cualquier valor inmutable. Una llave solo debe tener un valor asignado. Un **tuple** es un conjunto ordenado inmutable.

## Programación Orientada a Objetos
La **programación orientada a objetos** es una implementación formal que permite crear abstracciones. Las **clases** son prototipos de las instancias que se generan a partir de estas. Cada instancia contiene **propiedades**, atributos propios de la instancia, y **métodos** que operan en base a esa instancia. Un **atributo de clase** es compartido por todas las instancias, y cambiarlo cambia automaticamente las propiedades correspondientes en las instancias. La **herencia** permite generar subclases en base a clases más generales. El valor de los nombres de atributos se resuelven desde la instancia hasta las clases de las que hereda.

Los métodos de una instancia reciben como primer parametro la variable `self` que hace referencia a la instancia desde la que son llamados. Esto diferencia a los métodos de las funciones. Cada clase contiene el método constructor `__init__` que se encarga de instanciarla. Los atributos y métodos de una instancia pueden ser accedidos usando notación de punto. Cada instancia de una clase crea un objeto diferente. 
___

