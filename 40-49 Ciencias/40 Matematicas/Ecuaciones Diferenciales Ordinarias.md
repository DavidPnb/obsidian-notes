---
created: 2025-05-01 18:46
---
tags::
up::
# Ecuaciones Diferenciales Ordinarias
Son ecuaciones que contienen derivadas de una función con respecto a una única variable independiente. Una **solución** de una EDO es una expresión que al sustituirse en ella produce una identidad. El **orden** de una EDO es el orden de la derivada de mayor orden. El **grado** de una EDO es el grado de la derivada con mayor orden. Una **EDO lineal** tiene la forma $a_{0}y + a_{1}y′ + a_{2}y′′ + a_{3}y′′′ + · · · = b$, donde $a_{i}$ y $b$ son funciones de la variable independiente. Una EDO linear de orden $n$ tiene una solución con $n$ constantes arbitrarias que genera cualquier solución en particular. Esta es la **solución general**.

## Variables Separables
Tienen la forma $f_{1}(x)g_{1}(y)dx+f_{2}(x)g_{2}(y)dy=0$ y pueden resolverse con manipulación algebraica e integración. La **ecuación reducible a separable** tiene la forma $yf(xy)dx+xg(xy)dy=0$ y se resuelve con la sustitución $v=xy$. Estas ecuaciones son no lineales, por lo tanto su solución general no expresa todas las soluciones de la ecuación.

### Trayectorias
Dos familias de curvas son trayectorias si estas se intersectan en ángulos iguales. Para determinar la trayectoria de una familia de curvas con ángulo de corte $\omega$ se usa la ecuación diferencial de la familia de curvas. Se sustituye $y'=\frac{y'-tg\omega}{1+y'tg\omega}$ si $\omega \neq90°$ o $y'=-\frac{1}{y'}$ si $\omega \neq 90°$.

## Ecuaciones Lineales de Primer Orden
Tienen la forma $y'+P(x)y=Q(x)$ y se resuelve por el factor integrante $e^{\int P(x) \, dx}$ multiplicando a ambos miembros. Esto resulta en la expresión $ye^{\int P(x) \, dx}=\int e^{\int P(x) \, dx} \, Q(x)dx$.

## Otros Métodos
### EDO Exacta
Tiene la forma $P(x,y)dx+Q(x,y)dy=0$ donde $\frac{ \partial P }{ \partial y }=\frac{ \partial Q }{ \partial x }$. Esta expresión es un diferencial exacto. La ecuación se resuelve encontrando una función $U(x,y)$ tal que  $\frac{ \partial U }{ \partial x }=P$ y $\frac{ \partial U }{ \partial y }=Q$. La solución general es $U(x,y)=C$. Una EDO **reducible a exacta** acepta un factor integrante $u(x,y)$ tal que $\frac{ \partial uP }{ \partial y }=\frac{ \partial uQ }{ \partial x }$.

### Bernoulli
Tiene la forma $y'+P(x)y=Q(x)y^{n}$ y se reduce a una ecuación lineal con el cambio de variable $z=y^{1-n}$.

### EDO Homogenea
Una función $f(x,y)$ es **homogenea de grado $n$** si $f(tx,ty)=t^{n}f(x,y)$. Una función homogenea de grado $n$ puede expresarse como $f(x,y)=x^{n}f(1,y/x)$. Una EDO homogenea tiene la forma $f(x,y)dx +g(x,y)dy=0$, siendo $f$ y $g$ funciones homogeneas del mismo grado. Se resuelve con el cambio de variable $v=\frac{x}{y}$. Una EDO **reducible a homogenea** tiene la forma $y'= \frac{l_{1}}{l_{2}}=\frac{Ax+BY+C}{\alpha x+\beta y+\gamma}$. En caso de que las rectas se intersecten, se usa el cambio de variable $\overline{x}=x+x_{i}\: , \: \overline{y}=y+y_{i}$. De lo contrario una recta puede ser expresada como multiplo de la otra.
___
