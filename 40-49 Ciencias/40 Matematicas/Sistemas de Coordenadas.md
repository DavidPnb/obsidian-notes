---
created: 2023-02-02 12:58
---
tags:: #Mathematics 
up:: [[Geometria Analitica]]
# Sistemas de Coordenadas
![[Sistemas de Coordenadas.canvas]]
Los **sistemas de coordenadas** permiten representar las figuras geométricas de forma analítica y explorar algebraicamente sus propiedades.

## Segmento Dirigido
El concepto de segmento en geometría elemental se extiende al agregarle un **sentido** o **dirección**. El primer punto del segmento es llamado **origen** y el segundo se llama **extremo**. 

En un segmento dirigido, las longitudes de dos segmentos con sentidos opuestos tienen signos diferentes. Por lo tanto $\overline{AB}=-\overline{BA}$  y $\overline{AB}+\overline{BC}=\overline{AC}$.

## Sistema de Coordenadas Lineal
Un **sistema de coordenadas** establece una relación biunívoca entre puntos geométricos y números reales.

![[Sistemas de Coordenadas 2023-03-26 12.01.16.excalidraw.png]]
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
## Proyecciones
La **proyección** de un punto sobre una figura geométrica es la intersección de la figura con su recta perpendicular que pasa por el punto. Las figuras sobre las que se proyecta un punto son vectores, rectas y planos.

La proyección de una figura geométrica sobre otra es el lugar geométrico formado por las proyecciones de los puntos pertenecientes a la figura. En el caso que la figura a proyectar posea una orientación, la proyección mantiene esta misma orientación.

## Sistema de Coordenadas el Plano
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
> La distancia $d$ entre los puntos $P_{1}(x_{1},y_{1})$ y $P_{2}(x_{2},y_{2})$ es dada por la formula $$d=\sqrt{ (x_{2}-x_{1})^{2}+(y_{2}-y_{1})^{2} }$$

## Sistema de Coordenadas en el Espacio
Es una extensión del sistema de coordenadas bidimensional, al cual se le añade un eje $Z$ , que intersecta al eje $Y$ y al eje $X$ en el origen y es perpendicular a ambos ejes. Tambien se puede decir que el sistema de coordenadas en el plano es un caso especial del sistema de coordenadas en el espacio, en el que el valor de la coordenada en $z$ es cero.

En este sistema estan presentes tres planos llamados **planos coordenados**, los cuales son $XY$ , $XZ$ y $YZ$ y estan formados por dos de los ejes coordenados. Los planos dividen al espacio en ocho regiones llamadas **octantes**.

Al igual que en el sistema de coordenadas cartesianas, las coordenadas de un punto esta representadas por las proyecciones sobre los ejes, que forman una **terna ordenada**.

La **distancia entre dos puntos en el espacio** es igual a la longitud del segmento entre los puntos. Esto se obtiene usando dos veces el teorema de Pitágoras.

> [!teorema]- Teorema 3.
> La distancia $d$ entre los puntos $P_{1}(x_{1},y_{1},z_{1})$ y $P_{2}(x_{2},y_{2},z_{2})$ es dada por la formula $$d=\sqrt{ (x_{2}-x_{1})^{2}+(y_{2}-y_{1})^{2}+(z_{2}-z_{1})^{2} }$$

> [!teorema]- Teorema 4.
Las coordenadas del punto que divide al segmento dirigido $\overline{P_{1}P_{2}}$ en la razón $r=P_{1}P:PP_{2}$ son $$(\frac{x_{1}+rx_{2}}{1+r},\frac{y_{1}+ry_{2}}{1+r},\frac{z_{1}+rz_{2}}{1+r})$$

Lo que se demuestra usando álgebra de vectores.
___
