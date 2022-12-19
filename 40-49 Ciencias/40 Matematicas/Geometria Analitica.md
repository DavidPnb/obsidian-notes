---
created: 2022-11-02 18:20
---
tags:: #Mathematics 
up:: [[40.05 Geometria]]
# Geometría Análitica
La geometría analítica es el estudio de la [[40.05 Geometria|Geometría]] utilizando un sistema de coordenadas, lo que permite usar los métodos y herramientas del [[40.02 Algebra|Algebra]].

## Vectores
En el enfoque vectorial, varios conceptos de vectores son fundamentales, como el producto punto y el producto cruz. En este contexto, los vectores pueden ser considerados una representación algebraica de un segmento dirigido. A esto se le llama comunmente **vector geométrico**. Este concepto se usa mucho en la física, en donde un vector se usa para representar magnitudes que se comprenden mejor al pensar en ellas como una flecha con un origen y un extremo.

## Sistemas de Coordenadas
Los sistemas de coordenadas son los que permiten representar las figuras geométricas de forma analítica y explorar algebraicamente sus propiedades.

### Segmento Dirigido
El concepto de segmento en geometría elemental se extiende al agregarle un **sentido** o **dirección**. El primer punto del segmento es llamado **origen** y el segundo se llama **extremo**. En un segmento dirigido, las longitudes de dos segmentos con sentidos opuestos tienen signos diferentes. Esto significa que $\overline{AB}=-\overline{BA}$  y $\overline{AB}+\overline{BC}=\overline{AC}$.

### Sistema de Coordenadas Lineal
Un **sistema de coordenadas** establece una relación biunívoca entre puntos geométricos y números reales.

1. Siendo $X'X$ una recta cuya dirección positiva es de izquierda a derecha, y siendo $O$ un punto fijo sobre la recta
2. Se toma un punto $A$ a la derecha de $O$ como punto de referencia, y se considera a $\overline{OA}$ como unidad de longitud
	1. Si $P$ es un punto de $X'X$ situado a la derecha de $O$ tal que $OP$ contiene $x$ veces a $\overline{OA}$ , entonces $P$ corresponde a el número real $x$
	2. Si $P'$ es un punto de $X'X$ situado a la izquierda de $O$ tal que $OP$ contiene $x'$ veces a $\overline{OA}$ , entonces $P$ corresponde a el número real $-x$

En este caso, todos los puntos yacen sobre una recta, por lo que se le llama **sistema unidimensional** o **sistema de coordenadas lineal**.

La recta $X'X$ es llamada **eje** y el punto $O$ es llamado **origen** en el sistema de coordenadas. El número real $x$ que corresponde al punto $P$ es su **coordenada** y se representa como $(x)$ . De acuerdo con las convenciones adoptadas, al punto $O$ le corresponde $(0)$ y al punto $A$ le corresponde $(1)$ .

El punto $P$ y su coordenada $(x)$ es la **representación geométrica** del número real $x$. El número real $x$ es la **representación análitica** del punto $P$ . Habitualmente, un punto $P$ y su coordenada se escriben juntos como $P(x)$ .

La **longitud de un segmento dirigido** $P_{1}P_{2}$ es $x_{1}-x_{2}$ .

> [!teorema]- Teorema 1.
> En un sistema de coordenadas lineal, la longitud del segmento dirigido que une dos puntos se obtiene restando la coordenada del origen de la coordenada del extremo

> [!info]-
>  $\overline{AB}+\overline{BC}=\overline{AC}$ por Postulado
>  $x_{1}+\overline{P_{1}P_{2}}=x_{2}$ por Sustitución
>  $\overline{P_{1}P_{2}}=x_{2}-x_{1}$ por Despeje

La **distancia entre dos puntos** se define como el valor absoluto de la longitud del segmento que une los puntos. Si representamos a la distancia como $d$ , entonces $$
d=|\overline{P_{1}P_{2}}|=|x_{2}-x_{1}|
$$
### Sistema de Coordenadas en el Plano
El sistema de coordenadas bidimensional es usado en la Geometría Analítica plana y puede representar cualquier punto ubicado dentro de un plano.

El sistema de coordenadas más común que se utiliza es el sistema de coordenadas rectangulares, tambien usado en el álgebra y la trigonometría. Este sistema consta de dos rectas $X'X$ y $Y'Y$ , llamadas **ejes de coordenadas**, que son perpendiculares entre sí. La recta $X'X$ es llamada eje $X$ ; la recta $Y'Y$ es llamada eje $Y$, y su punto de intersección $O$ es el **origen**. La dirección positiva del eje $X$ es hacia la derecha y la dirección positiva del eje $Y$ es hacia arriba. Los ejes dividen al plano en cuatro regiones llamadas **cuadrantes**.
- Cuadrante $\mathrm{I}$ - Semieje $X$ positivo, Semieje $Y$ positivo
- Cuadrante $\mathrm{II}$ - Semieje $X$ negativo, Semieje $Y$ positivo
- Cuadrante $\mathrm{III}$ - Semieje $X$ negativo, Semieje $Y$ negativo
- Cuadrante $\mathrm{IV}$ - Semieje $X$ positivo, Semieje $Y$ negativo

Siendo $A$ la proyección perpendicular de $P$ sobre el eje $X$ y $B$ la proyección perpendicular de $P$ sobre el eje $Y$, la longitud del segmento dirigido $OA$ se representa por $x$ y es llamada **abscisa**. De forma similar, la longitud del segmento dirigido $OB$ se representa por $y$ y es llamada **ordenada**. Los números reales $x$ y $y$ se llaman coordenadas del punto $P$ y se representan como el par ordenado $(x, y)$ , donde $(x,y) \neq (y,x)$ siempre que $x\neq y$ .

Si se consideran solo los puntos cuyas ordenadas son cero, el sistema se reduce a un sistema lineal; por lo tanto, el sistema de coordenadas lineal es un caso especial del sistema de coordenadas bidimensionales.

Sean $P_{1}(x_{1},y_{1})$ y $P_{2}(x_{2},y_{2})$ dos puntos cualquiera, la **distancia entre los dos** es igual a $|\overline{P_{1}P_{2}}|$ .  La longitud de este segmento puede obtenerse por medio del teorema de Pitagoras.

> [!teorema]- Teorema 2.
> La distancia $d$ entre los puntos $P_{1}(x_{1},y_{2})$ y $P_{2}(x_{2},y_{2})$ es dada por la formula $$d=\sqrt{ (x_{2}-x_{1})^{2}+(y_{2}-y_{1})^{2} }$$

___
