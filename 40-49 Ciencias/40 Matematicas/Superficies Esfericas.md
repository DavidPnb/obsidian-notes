---
status:
tags: 
references:
created: 2022-05-17 21:35
---
Links: [[]]
# Superficies Esfericas
La superficie esferica es el lugar geometrico descrito por un punto que se mueve en $\mathbb{R}3$ de tal forma que siempre su distancia a un punto fijo llamado **centro** es igual a una constante llamada **radio**

### Ecuacion Vectorial Parametrica
$SE: \overrightarrow{OP}=(h,k,l)+r(\lambda_1,\lambda_2,\sqrt{1- {\lambda_1}^2-{\lambda_2}^2})$

> [!info]+ Origen de la Ecuacion Vectorial Parametrica
> 
Usando una malla de vectores, tenemos $\overrightarrow{OC} + \overrightarrow{R} - \overrightarrow{OP}=\overrightarrow{0}$, donde $\overrightarrow{OC}$ es un vector que va desde el origen al centro, $\overrightarrow{R}$ es un vector que va desde el centro hasta un punto generico en la SE, y $\overrightarrow{OP}$ es el vector desde el origen hasta el punto generico
$\overrightarrow{OP}= \overrightarrow{OC}+ \overrightarrow{R}$
$\overrightarrow{R}=|\overrightarrow{R}| \overrightarrow{\mu}_R$, donde $|\overrightarrow{R}| =r$, y $\overrightarrow{\mu}_R=(cos{\alpha},cos{\beta},cos{\delta})$
$cos{\delta}=\sqrt{1-cos^2{\alpha}-cos^2{\delta}}$
$\overrightarrow{\mu}_R=(cos{\alpha},cos{\beta},\sqrt{1-cos^2{\alpha}+cos^2{\beta}})$
$\begin{align*} \lambda_1=cos{\alpha} \\ \lambda_2=cos{\beta} \end{align*}\; \lambda_1, \lambda_2 \in[-1,1]$
$\overrightarrow{\mu}_R=(\lambda_1, \lambda_2, \sqrt{1 - {\lambda_1}^2-{\lambda_2}^2})$
$SE:\overrightarrow{OP}=(h,k,l)+r(\lambda_1, \lambda_2, \sqrt{1 - {\lambda_1}^2-{\lambda_2}^2})$

### Ecuacion Ordinaria
$SE:(x-h)^2+(y-k)^2+(z-l)^2=r^2$

> [!info]+ Origen de la Ecuacion Ordinaria
>
Si $SE: \overrightarrow{OP}=(h,k,l)+r\overrightarrow{\mu}_R$
$\overrightarrow{R}=(x,y,z)-(h,k,l)=(x-h,y-k,z-l)$
$|\overrightarrow{R}|=|(x-h,y-k,z-l)|$
$r= \sqrt{(x-h)^2+(y-k)^2+(z-l)^2}$
$r^2= (x-h)^2+(y-k)^2+(z-l)^2$

### Ecuacion General
$SE:x^2+y^2+z^2+A+B+C+D=0$

> [!info]- Origen de la Ecuacion General
>
Partiendo de $SE:(x-h)^2+(y-k)^2+(z-l)^2=r^2$
$x^2-2hx+h^2+y^2-2ky+k^2+Z^2-2lz+l^2=r^2$
$x^2+y^2+z^2-2hx-2ky-2lz+h^2+k^2+l^2-r^2=0$
$\begin{align*} A= -2hx \\ B= -2ky \\ C= -2lz \\ D=h^2+k^2+l^2-r^2 \end{align*}$
$SE:x^2+y^2+z^2+A+B+C+D=0$

### Posiciones Relativas entre SE y Plano
1. Si $d>r$, entonces $\pi$ y SE no se tocan
2. Si $d<r$, entonces $\pi$ y SE cortan generando una circunferencia de interseccion
3. Si $d=r$, entonces $\pi$ es tangente a SE

> [!note]+ Distancia entre plano y SE
>
$d=\frac{|Ah+Bk+Cl+D|}{\sqrt{A^2+B^2+C^2}}$

### Posiciones Relativas entre SE y Recta
1. Si $d>r$, entonces $l$ y SE no se tocan
2. Si $d=r$, entonces $l$ es tangente a SE
3. Si $d<r$, entonces $l$ corta a SE

> [!note]+ Distancia entre $l$ y SE
>
$d=\frac{|\overrightarrow{P_0P_1} \times \overrightarrow{L}|}{|\overrightarrow{L}|};P_1=(h,k,l),P_0 \in l$

### Posiciones Relativas entre SE
1. Si $d_1>r_1 \wedge d_2>r_2$ y los signos de $d_1$ y $d_2$ son opuestos, entonces $SE_1$ y $SE_2$ no se tocan exteriormente
2. Si $d_1>r_1 \wedge d_2>r_2$ y los signos de $d_1$ y $d_2$ son iguales, entonces $SE_1$ y $SE_2$ no se tocan interiormente
3. Si $d_1=r_1 \wedge d_2=r_2$ y los signos de $d_1$ y $d_2$ son opuestos, entonces $SE_1$ y $SE_2$ son tangentes exteriormente 
4. Si $d_1=r_1 \wedge d_2=r_2$ y los signos de $d_1$ y $d_2$ son iguales, entonces $SE_1$ y $SE_2$ no se tocan interiormente
5. Si $d_1<r_1 \wedge d_2<r_2$ y los signos de $d_1$ y $d_2$ son opuestos, entonces $SE_1$ y $SE_2$ se cortan exteriormente
6. Si $d_1<r_1 \wedge d_2<r_2$ y los signos de $d_1$ y $d_2$ son iguales, entonces $SE_1$ y $SE_2$ se cortan interiormente

> [!note]+ Distancia entre $SE_1$ y $SE_2$
>
> Para encontrar la distancia entre $SE_1$ y $SE_2$, se utiliza el plano radical $\pi_R$, que es un plano perpendicular a la recta que une los centros de las SE y contiene los puntos comunes a ambas superficies si los hubiere. Su ecuacion se obtiene de la siguiente manera:
> $\pi_R:SE_2-SE_1=0; \overrightarrow{N_R}=(D_2-D_1,E_2-E_1,F_2-F_1$

### Familia de SE
$SE_f:SE_1 + \lambda SE_2=0;\forall \lambda \neq -1$
___
