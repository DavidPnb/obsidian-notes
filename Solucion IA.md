### Solución del Ejercicio 26

#### Parte (a): Evaluar la integral de línea

Se nos pide evaluar la integral de línea:

$$
\oint_C (2x^3 - y^3)dx + (x^3 + y^3)dy
$$

alrededor del círculo $x^2 + y^2 \leq 1$. El círculo es la región $D$ y el contorno $C$ es el borde de $D$. Podemos usar el **Teorema de Green** para resolver esta integral.

El Teorema de Green establece que:

$$
\oint_C Pdx + Qdy = \iint_D \left( \frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y} \right)dA
$$

En nuestro caso, $P = 2x^3 - y^3$ y $Q = x^3 + y^3$.

Primero, calculamos las derivadas parciales:

$$
\frac{\partial Q}{\partial x} = \frac{\partial}{\partial x}(x^3 + y^3) = 3x^2
$$

$$
\frac{\partial P}{\partial y} = \frac{\partial}{\partial y}(2x^3 - y^3) = -3y^2
$$

Ahora, sustituimos en la fórmula del Teorema de Green:

$$
\oint_C (2x^3 - y^3)dx + (x^3 + y^3)dy = \iint_D 3(x^2 + y^2)dA
$$

La región de integración $D$ es el círculo unitario, lo que sugiere el uso de **coordenadas polares** para la doble integral. Las transformaciones son $x = r\cos\theta$, $y = r\sin\theta$, y $x^2 + y^2 = r^2$. El elemento de área es $dA = r\,dr\,d\theta$.

Los límites de integración para un círculo de radio 1 centrado en el origen son:

* Radio $r$: de 0 a 1

* Ángulo $\theta$: de 0 a $2\pi$

Sustituyendo en la integral:

$$
\iint_D 3(x^2 + y^2)dA = \int_0^{2\pi} \int_0^1 3(r^2) r\,dr\,d\theta = \int_0^{2\pi} \int_0^1 3r^3\,dr\,d\theta
$$

Primero, resolvemos la integral con respecto a $r$:

$$
\int_0^1 3r^3\,dr = 3 \left[ \frac{r^4}{4} \right]_0^1 = 3 \left( \frac{1^4}{4} - \frac{0^4}{4} \right) = \frac{3}{4}
$$

Ahora, resolvemos la integral con respecto a $\theta$:

$$
\int_0^{2\pi} \frac{3}{4}\,d\theta = \frac{3}{4} [\theta]_0^{2\pi} = \frac{3}{4}(2\pi - 0) = \frac{3\pi}{2}
$$

Por lo tanto, el valor de la integral de línea es $\frac{3\pi}{2}$.

#### Parte (b): Hallar el área de la región

El área de una región plana $D$ se puede calcular de varias maneras. Una de las más comunes es usando el Teorema de Green con un integrando de 1. Es decir, si elegimos $P$ y $Q$ tales que $\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y} = 1$, entonces la integral doble del Teorema de Green nos dará el área de la región.

Una elección común para $P$ y $Q$ es:

* $P = 0$, $Q = x \implies \frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y} = 1 - 0 = 1$

* $P = -y$, $Q = 0 \implies \frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y} = 0 - (-1) = 1$

* $P = -\frac{y}{2}$, $Q = \frac{x}{2} \implies \frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y} = \frac{1}{2} - (-\frac{1}{2}) = 1$

Usaremos la tercera opción para calcular el área de la región, que es el círculo unitario $x^2+y^2 \leq 1$. El área $A$ es:

$$
A = \oint_C -\frac{y}{2}dx + \frac{x}{2}dy
$$

Para evaluar esta integral de línea, parametrizamos el círculo $C$ de radio 1:

* $x = \cos(t)$

* $y = \sin(t)$

* $dx = -\sin(t)dt$

* $dy = \cos(t)dt$

* Los límites de $t$ son de 0 a $2\pi$.

Sustituyendo en la integral:

$$
A = \int_0^{2\pi} \left( -\frac{\sin(t)}{2} (-\sin(t)dt) + \frac{\cos(t)}{2} (\cos(t)dt) \right)
$$

$$
A = \int_0^{2\pi} \left( \frac{\sin^2(t)}{2} + \frac{\cos^2(t)}{2} \right) dt
$$

Usando la identidad trigonométrica fundamental $\sin^2(t) + \cos^2(t) = 1$:

$$
A = \int_0^{2\pi} \frac{1}{2} dt = \frac{1}{2} [t]_0^{2\pi} = \frac{1}{2}(2\pi - 0) = \pi
$$

El área de la región encerrada es $\pi$. Esto coincide con la fórmula del área de un círculo de radio 1, que es $A = \pi r^2 = \pi(1)^2 = \pi$.