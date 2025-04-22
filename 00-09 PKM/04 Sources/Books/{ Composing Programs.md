---
alias: 
created: 2025-04-03 12:53
---
[[41.00 Ciencias de la Computacion MOC|Ciencias de la Computacion]]

# { Composing Programs
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
___

