---
alias:
status:
references:
created: 2022-03-12 16:29
---
tags:: #Mathematics 
up:: [[Aritmetica]]
Links:
# Raices
Un radical es una expresión de la forma $\sqrt[n]{a}$, que denota la raiz enesima principal de $a$; [[Exponenciacion]]. El entero positivo $n$ es el **indice**, mientras que $a$ es el **radicando**. El indice se omite si $n = 2$.

Para valores pares de n, los números positivos también tienen una raíz enésima negativa, mientras que los números negativos no tienen una raíz enésima real.

Las raíces enésimas de casi todos los números son irracionales.

## Leyes y Propiedades
Las propiedades de las raices son las mismas que las propiedades de las potencias, porque $a^{1/n}=\sqrt[n]{a}$ y $a^{m/n}=\sqrt[n]{a^m}$. Entre las propiedades más usadas estan:

- $(\sqrt[n]{a})^{n}=a$, si $\sqrt[n]{a}$ es un numero real
- $\sqrt[n]{a^n}=a$, si $a\ge0$
- $\sqrt[n]{a^n}=a$, si $a\lt0$ y $n$ es impar
- $\sqrt[n]{a^n}=|a|$, si $a\lt0$ y $n$ es par

- $\sqrt[n]{ab}=\sqrt[n]{a}\sqrt[n]{b}$
- $\sqrt[n]{\frac{a}{b}}=\frac{\sqrt[n]{a}}{\sqrt[n]{b}}$
- $\sqrt[m]{\sqrt[n]{a}}=\sqrt[mn]{a}$

- si $c\gt0$ o si $c\lt0$ y $n$ es impar, entonces $\sqrt[n]{c^{n}d}=c\sqrt[n]{d}$
- si $c\lt0$ y $n$ es par, entonces $\sqrt[n]{c^{n}d}=|c|\sqrt[n]{d}$

## Simplificación
### Remoción de Potencias Enesimas Perfectas del Radicando
> [!example] Ejemplo
> $$\sqrt[3]{32} = 
> \sqrt[3]{4 * 2^3} = 
> \sqrt[3]{2^3} \sqrt[3]{4} =
>  2 \sqrt[3]{4}$$

### Reducción del Indice del Radical
> [!example] Ejemplo
> $$\sqrt[4]{64} = 
> \sqrt[4]{2^6} = 
> 2^{6/4} =
> 2^{3/2} =
> \sqrt[2]{2^3} =
> \sqrt[2]{8}$$

> [!attention] Atención
> $$\sqrt[4]{(-4)^2} = 
> (-4)^{2/4} =
> (-4)^{1/2} =
> \sqrt[2]{-4}$$
> 
> **Es Incorrecto**

### Racionalización
Cuando el denominador es un monomio raíz cuadrada, se puede racionalizar multiplicando la parte superior e inferior de la fracción por el denominador.

Los binomios radicales $\sqrt{a} + \sqrt{b}$ y $\sqrt{a} - \sqrt{b}$ son **conjugados** entre sí.

El proceso de racionalización de binomios radicales con indice $n = 2$ consiste en multiplicar la parte superior e inferior de una fracción por el conjugado del denominador para que el denominador se convierta en un número racional.

Si el binomio radical tiene la forma $\sqrt[3]{a} + \sqrt[3]{b}$ , se multiplica el numerador y denominador por $a^2 - ab + b^2$ , lo que resulta en un binomio de la forma $a + b$ . Si el binomio radical tiene la forma $\sqrt[3]{a} - \sqrt[3]{b}$ , se multiplica el numerador y denominador por $a^2 + ab + b^2$ , lo que resulta en un binomio de la forma $a - b$ .

## Operaciones
Se dice que dos o más radicales son **similares** si luego de ser reducidos a su forma más simple tienen el mismo indice y el mismo radicando

- Para sumar algebraicamente dos o más radicales, se reduce cada radical a su forma mas simple y se suman los terminos con radicales similares
- Para multiplicar dos radicales con el mismo indice, se usan las leyes de los radicales
- Para multiplicar dos radicales con indices diferentes, estos se pueden transforman en exponentes fraccionarios y luego ser simplificados usando leyes de los exponentes
___
