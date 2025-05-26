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
___
