Status:
Tags: 
Links: ,parent::[[Vectores]]
Referencias:
Creado el: 2022-04-02 19:35
___
# Producto Escalar
El producto escalar o producto punto de dos vectores es igual a un escalar definido por $\overrightarrow{A}*\overrightarrow{B}=|\overrightarrow{A}| |\overrightarrow{B}| \cos{\theta}$
o utilizando sus componentes
$$\overrightarrow{A}*\overrightarrow{B}=a_x b_x+a_y b_y+ a_z b_z$$

## Propiedades
- $$\overrightarrow{A}*\overrightarrow{B}=\overrightarrow{B}*\overrightarrow{A}$$

- $$\overrightarrow{A}*(\overrightarrow{B}+\overrightarrow{C})=\overrightarrow{A}*\overrightarrow{B}+\overrightarrow{A}*\overrightarrow{B}$$

- $$(\lambda \overrightarrow{A}) * \overrightarrow{B}= \overrightarrow{A} * (\lambda \overrightarrow{B})=\lambda (\overrightarrow{A} * \overrightarrow{B})$$


## Angulo entre Vectores
$\cos{\theta}=\frac{\overrightarrow{A}*\overrightarrow{B}}{|\overrightarrow{A}| |\overrightarrow{B}|}$ sirve para determinar la posicion relativa entre $\overrightarrow{A}$ y $\overrightarrow{B}$

## Perpendicularidad
Dos vectores son ortogonales si y solo si $\overrightarrow{A}*\overrightarrow{B}=0$

Si el producto escalar entre dos vectores es positivo el angulo entre los vectores es menor que $90°$. Si el producto escalar entre dos vectores es negativo el angulo entre los vectores es mayor que $90°$

## Proyeccion de un Vector sobre otro
La proyeccion de $\overrightarrow{A}$ sobre $\overrightarrow{B}$ denotada $\overrightarrow{A}^1$ es definida por $(\overrightarrow{A}*\overrightarrow{\mu_B})\overrightarrow{\mu_B}$

## Producto Vectorial
El producto vectorial de $\overrightarrow{A}$ por $\overrightarrow{B}$, denotado por $\overrightarrow{A} \times \overrightarrow{B}$, es una operacion que genera a un nuevo vector perpendicular a $\overrightarrow{A}$ y a $\overrightarrow{B}$ al mismo tiempo, llamado $\overrightarrow{N}$ cuyo modulo sera $|\overrightarrow{N}|=|\overrightarrow{A}| |\overrightarrow{B}| \sin{\theta}$ y $\overrightarrow{N}=(|\overrightarrow{A}| |\overrightarrow{B}| \sin{\theta}) \overrightarrow{\mu_N}$, donde $\theta$ es la medida del angulo entre $\overrightarrow{A}$ y $\overrightarrow{B}$

Usando matrices

$$\overrightarrow{A} \times \overrightarrow{B}=i \begin{vmatrix}a_y &a_z \\ b_y &b_z \end{vmatrix}-j \begin{vmatrix}a_x &a_z \\ b_x &b_z \end{vmatrix}+k \begin{vmatrix}a_x &a_y \\ b_x &b_y \end{vmatrix}$$

### Propiedades
$$\overrightarrow{A} \times \overrightarrow{A}=0$$

$$\overrightarrow{A} \times \overrightarrow{A}=-( \overrightarrow{B} \times \overrightarrow{A})$$

$$\overrightarrow{A} \times (\overrightarrow{B}+\overrightarrow{C})=(\overrightarrow{A} \times \overrightarrow{B})+(\overrightarrow{A} \times \overrightarrow{C})$$

$$(\lambda \overrightarrow{A}) \times \overrightarrow{B}= \overrightarrow{A} \times (\lambda \overrightarrow{B})=\lambda (\overrightarrow{A} \times \overrightarrow{B})$$



### Paralelismo
Si el producto vectorial entre dos vectores es igual a cero, entonces los vectores son paralelos

### Interpretacion Geometrica
El modulo del producto vectorial puede ser interpretado como el area de un paralelogramo teniendo a $\overrightarrow{A}$ y $\overrightarrow{B}$ como lados

### Producto Mixto
El producto mixto de tres vectores es definido como el producto punto de uno de los vectores con el producto escalar de los otros dos. Se obtiene al calcular el valor del siguiente determinante $(\overrightarrow{A} \times \overrightarrow{B})*\overrightarrow{C}=\begin{vmatrix} a_x &a_y &a_z \\ b_x &b_y &b_z \\ c_x &c_y &c_z \end{vmatrix}=a_x \begin{vmatrix}b_y &b_z \\ c_y &c_z \end{vmatrix}- b_x \begin{vmatrix}a_y &a_z \\ c_y &c_z \end{vmatrix}+ c_x \begin{vmatrix}a_y &a_z \\ b_y &b_z \end{vmatrix}$

#### Interpretacion Geometrica
Geometricamente, el producto mixto es el volumen del paralelepipedo definido por los tres vectores dados.

#### Propiedades
$$(\overrightarrow{A} \times \overrightarrow{B}) * \overrightarrow{C}=\overrightarrow{A} * (\overrightarrow{B} \times \overrightarrow{C})$$

$$(\overrightarrow{A} \times \overrightarrow{B}) * \overrightarrow{C}=\overrightarrow{C} * (\overrightarrow{A} \times \overrightarrow{B})$$

#### Coplanaridad
Tres vectores son coplanares si el producto mixto de los tres es igual a cero. Dos vectores siempre son coplanares

### Colinealidad
Dos vectores son colineales si y solo si su producto vectorial genera al vector nulo
___
