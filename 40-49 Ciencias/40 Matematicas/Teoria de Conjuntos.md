---
status:
references:
created: 2022-02-09 18:44
---
tags:: #Mathematics 
up:: [[40.01 Logica Matematica]]
Links: 
# Teoria de Conjuntos
Es una rama de la [[40.01 Logica Matematica]] que estudia las propiedades y relaciones de los Conjuntos.

## Conjuntos
Un conjunto es el modelo matemático para una colección de diferentes cosas; un conjunto contiene elementos o miembros, que pueden ser objetos matemáticos de cualquier tipo. Generalmente son denotados por una letra mayuscula. Los elementos de un conjunto son unicos y no estan ordenados.

Si $a$ es un elemento de $A$, se denota como $a \in A$, sino se expresa que $a \notin A$. 

### Notaciones
- Corchetes $\{ \}$ con elementos en su interior delimitados por comas. Se pueden usar $\dots$ para indicar una secuencia que se repite en el conjunto
- Corchetes $\{ \}$ con una descripción en su interior
- $A = \{x: condiciones\}$ o $A = \{x | condiciones\}$

### Conjunto Vacio
Es el conjunto sin elementos, denotado por $\emptyset$ o $\{ \}$

### Universo
Es el conjunto que contiene todos los elementos de interes, denotado por $U$

### Conjuntos Numericos
- $\mathbb{C}$ - Numeros Complejos
- $\mathbb{R}$ - [[Numeros Reales]]
- $\mathbb{Q}$ - Numeros Racionales
- $\mathbb{Z}$ - Numeros Enteros
- $\mathbb{N}$ - Numeros Naturales

[[Numeros]]

## Axiomas

### Adjuncion
En la teoría matemática de conjuntos, el axioma de adjunción establece que para dos conjuntos cualquiera $x$, $y$ existe un conjunto $w = x\cup\{y\}$ dado por "unir" el conjunto $y$ al conjunto $x$.

### Regularidad
Cada conjunto no vacío $x$ contiene un miembro $y$ tal que $x$ y $y$ son conjuntos disjuntos.

### Esquema de Especificacion
Esencialmente, dice que cualquier subclase definible de un conjunto es un conjunto.

### Emparejamiento
Si $x$ y $y$ son conjuntos, entonces existe un conjunto que contiene $x$ y $y$ como elementos.

### Union
Existe la Union entre elementos de un conjunto.

### Esquema de Reemplazo
Afirma que la imagen de un conjunto bajo cualquier función definible también caerá dentro de un conjunto.

### Infinito
Existe un conjunto $X$ que tiene infinitos miembros.

### Conjunto Potencia
Establece que para cualquier conjunto $x$, hay un conjunto $y$ que contiene todos los subconjuntos de $x$.

### Teorema del Buen Orden
Establece que todo conjunto puede ser bien ordenado.

## Operaciones

### Union
La unión de $A$ y $B$, denotada por $A \cup B$, es el conjunto de todas las cosas que son miembros de A o de B o de ambos.

#### Propiedades
- $A \cup B = B \cup A$.
- $A \cup (B \cup C) = (A \cup B) \cup C$.
- $A \subseteq (A \cup B)$.
- $A \cup A = A$.
- $A \cup \emptyset = A$.
- $A \subseteq B$ si, y solo si $A \cup B = B$
- $A \subset B$ si, y solo si $A \subseteq B$ y $|A| < |B|$

### Interseccion
La intersección de $A$ y $B$, denotada por $A \cap B$, es el conjunto de todas las cosas que son miembros tanto de $A$ como de $B$. Si $A \cap B = \emptyset$, entonces se dice que $A$ y $B$ son disjuntos.

#### Propiedades
- $A \cap B = B \cap A$.
- $A \cap (B \cap C) = (A \cap B) \cap C$.
- $A \cap B \subseteq A$.
- $A \cap A = A$.
- $A \cap \emptyset = \emptyset$.
- $A \subseteq B$. Si, y solo si $A \cap B = A$

### Complemento
El complemento relativo de $B$ en $A$, denotado por $A \setminus B$ (o $A − B$), es el conjunto de todos los elementos que son miembros de $A$, pero no miembros de $B$ .

En ciertos casos, todos los conjuntos en discusión se consideran subconjuntos de un conjunto universal dado $U$. En tales casos, $U \setminus A$ se denomina complemento absoluto o simplemente complemento de $A$, y se denota por $A^′$ o $A^c$.

Una extensión del complemento es la diferencia simétrica, definida para los conjuntos $A$, $B$ como $A \Delta B = (A \setminus B) \cup (B \setminus A)$.

#### Propiedades
- $A \setminus B \neq B \setminus A$. Para $A \neq B$
- $A \cup A^ = U$.
- $A \cap A^ = \emptyset$.
-   $(A^′)^′ = A$.
-   $\emptyset \setminus A = \emptyset$.
-   $A \setminus \emptyset = A$.
-   $A \setminus A = \emptyset$.
-   $A \setminus U = \emptyset$.
-  $A \setminus A^′ = A$ y $A^′ \setminus A = A^′$.
-  $U^′ = \emptyset$ y $\emptyset^′ = U$.
-   $A \setminus B = A \cap B^′$.
-  Si $A \subseteq B$ entonces $A \setminus B = \emptyset$.

### Producto Cartesiano
El producto cartesiano de dos conjuntos $A$ y $B$, denotado por $A × B$, es el conjunto de todos los pares ordenados $(a, b)$ tales que $a$ es miembro de $A$ y $b$ es miembro de $B$.

#### Propiedades
- $A \times \emptyset = \emptyset$.
- $A \times (B \cup C) = (A \times B) \cup (A \times C)$.
- $(A \cup B) \times C = (A \times C) \cup (B \times C)$.

## Leyes de De Morgan
Si $A$ y $B$ son dos conjuntos cualquiera, entonces
- $(A \cup B)^′=A^′ \cap B^′$
- $(A \cap B)^′=A^′ \cup B^′$

## Cardinalidad
La Cardinalidad de un conjunto $A$ es la cantidad de elementos del conjunto, denotada por $|A|$. La cardinalidad del conjunto vacio es cero

## Intervalo 
Es el conjunto de numeros que contiene todos los numeros entre dos numeros del conjunto
![[Pasted image 20220318165346.png]]
___