---
created: 2025-05-24 11:41
---
tags::
up::
# Funciones Vectoriales
Una **función vectorial** es una función $F:R^n\to R^m$. Una **función real** es una función $F:R^n\to R$. El **dominio natural** de una función vectorial es el conjunto $A \subseteq R^n$ para el que todos los valores de $F$ estan definidos. Una función vectorial puede representarse por medio de sus **funciones componentes** como $F(\mathrm{X})=[f_{1}(\mathrm{X}),f_{2}(\mathrm{X}),\dots,f_{m}(\mathrm{X})]$, donde $f_{i}$ es una función real y $\mathrm{X}$ es un vector perteneciente a $\mathrm{R^n}$. El dominio natural de una función vectorial puede obtenerse por medio de sus componentes como $D_{F}=D_{f_{1}} \cap D_{f_{2}}\cap\dots \cap D_{f_{m}}$.

### Superficies de Nivel
Sea una función $F:\mathrm{R_{2}}\to \mathrm{R}$, una **curva de nivel** $F$ es un lugar geométrico definido por $F(x,y)=k$ donde $k$ es un número real. Sea una función $F:\mathrm{R_{3}}\to \mathrm{R}$, una **superficie de nivel** $F$ es un lugar geométrico definido por $F(x,y,z)=k$ donde $k$ es un número real. Estas ayudan en la representación de una función vectorial.

## Límites y Continuidad
Dado $\mathrm{X_{0}} \in \mathrm{R^n}$ y $r>0$, la **esfera abierta** de centro en $\mathrm{X_{0}}$ y radio $r$ es el conjunto $$
S_{e}(\mathrm{X_{0}},r)=\left\{ \mathrm{X}/\mathrm{d}(\mathrm{X},\mathrm{X_{0}})<0 \right\} 
$$
$\mathrm{X}$ es un **punto de acumulación** de $A \subset \mathrm{R^n}$ si toda esfera abierta con centro en $\mathrm{X}$ contiene infinitos puntos de $A$.

Si $\mathrm{X_{0}}$ es un punto de acumulación del dominio de la función vectorial $F$, se dice que $$
\lim_{ \mathrm{X} \to \mathrm{X_{0}} } F(\mathrm{X})=L
$$ si dado $\epsilon>0$ existe $\delta>0$ tal que $$
\mathrm{X} \in S_{e}(\mathrm{X_{0}},\delta) \implies F(\mathrm{X})\in S_{e}(L,\epsilon)
$$
Si este límite existe, es único para $F$. $F$ es **continua** si $$
F(\mathrm{X_{0}})=\lim_{ \mathrm{X} \to \mathrm{X_{0}} } F(\mathrm{X})=L
$$

### Propiedades
Sean $F$ y $G$ funciones vectoriales y $\mathrm{X_{0}} \in\mathrm{R^n}$ tal que $$
\lim_{ \mathrm{X} \to \mathrm{X_{0}} } F(\mathrm{X})=L_{1} 
$$
$$
\lim_{ \mathrm{X} \to \mathrm{X_{0}} } G(\mathrm{X})=L_{2}
$$
entonces
$$
\lim_{ \mathrm{X} \to \mathrm{X_{0}} } kF(\mathrm{X})=kL_{1}
$$
$$
\lim_{ \mathrm{X} \to \mathrm{X_{0}} } F(\mathrm{X}) \pm G(\mathrm{X}) =L_{1} \pm L_{2}
$$
Si $F$ y $G$ son funciones reales, entonces
$$
\lim_{ \mathrm{X} \to \mathrm{X_{0}} } F(\mathrm{X}) \cdot G(\mathrm{X})=L_{1}\cdot L_{2}
$$
$$
\lim_{ \mathrm{X} \to \mathrm{X_{0}} } \frac{F(\mathrm{X})}{G(\mathrm{X})}=\frac{L_{1}}{L_{2}}, L_{2}\neq{0}
$$
$$
\lim_{ \mathrm{X} \to \mathrm{X_{0}} } F(\mathrm{X})^{k}=L^{k},k\in \mathrm{N}
$$

## Derivadas Parciales
Si $F:\mathrm{R^{n}}\to\mathrm{R^{m}}$ es una función vectorial, su **derivada parcial con respecto a $x_{k}$** en un punto $P(a_{1},a_{2},\dots,a_{n})$ es $$
F_{x_{k}}=\frac{ \partial F }{ \partial x_{k} }=\lim_{ h \to 0}  \frac{F(x_{1},x_{2},\dots,x_{k}+h,\dots,x_{n})-F(a_{1},a_{2},\dots,a_{n})}{h}
$$
La derivada parcial es la tasa de cambio de una función respecto a una variable si se toman las demás como constantes. En $\mathrm{R^{2}}$, la derivada parcial de una función $z=f(x,y)$ es la pendiente de la recta tangente a la intersección de $z$ con el plano transversal a $x$ o $y$. Las **derivadas parciales de orden superior** son derivadas parciales evaluadas de forma sucesiva. El **teorema de las derivadas cruzadas** concluye que $f_{xy}(x_{0},y_{0})=f_{yx}(x_{0},y_{0})$ si $f$ es continua en el entorno de $(x_{0},y_{0})$.

## Transformación Afín
La **matriz jacobiana** $J_{F}$ de una función $F:\mathbb{R^{n}\to\mathbb{R^{m}}}$ en $\mathbf{X_{0}}$ se define como
$$
\left.  {\begin{pmatrix}
\frac{ \partial f_{1} }{ \partial x_{1} }  & \frac{ \partial f_{1} }{ \partial x_{2} } & \cdots & \frac{ \partial f_{1} }{ \partial x_{n} }  \\
\frac{ \partial f_{2} }{ \partial x_{1} } & \frac{ \partial f_{2} }{ \partial x_{2} } & \cdots & \frac{ \partial f_{2} }{ \partial x_{n} }  \\
\vdots & \vdots &  & \vdots \\
\frac{ \partial f_{m} }{ \partial x_{1} }  & \frac{ \partial f_{m} }{ \partial x_{2} }  & \cdots & \frac{ \partial f_{m} }{ \partial x_{n} } 
\end{pmatrix}} \right |_{\mathbf{X_{0}}}
$$
La **transformación afín** de $F$ se define como $$
A(\mathbf{X_{0}})=F(\mathbf{X_{0}})+J_{F}(\mathbf{X}-\mathbf{X_{0}})
$$
$F$ es **diferenciable** si $$
\lim_{ \mathbf{X} \to \mathbf{X_{0}} } \frac{\|F(\mathbf{X})-A(\mathbf{X})\|}{\|\mathbf{X}-\mathbf{X_{0}}\|}=0
$$
En este caso, se dice que $J_{F}$ es **transformación afín aproximante** y es buena aproximación de $F$ en puntos cercanos a $\mathbf{X_{0}}$. Si $F:R^{2}\to R$, $A(\mathbf{X_{0}})$ es el **plano tangente** a $F$ en el punto. Si las derivadas parciales de $F$ son continuas en $\mathbf{X_{0}}$ entonces la función es diferenciable en $\mathbf{X_{0}}$. El **diferencial** de $F$ se define como $F_{x_{1}}dx_{1}+Fx_{2}dx_{2}+\dots+F_{x_{n}}dx_{n}$.
___
