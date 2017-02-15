---
title: "Ecuaciones"
teaching: 45
exercises: 20
questions:
- "Trabajar con ecuaciones y su implementación"
objectives:
- "Que los alumnos sean capaces de manejar ciertas ecuaciones con soltura"
keypoints:
- "Ecuaciones lineales"
- "Trabajar con determinados programas"
---

## 1. Concepto y características básicas

Como idea, se puede decir que una **ecuación** es una igualdad formada por dos miembros, un operador ''='' y una o varias cosas desconocidas que a priori queremos averiguar.

De manera más formal podemos decir:

- Los que está a la izquierda del igual es llamado **primer miembro** de la ecuación.

- Lo que está a la derecha del igual es llamado **segundo miembro** de la ecuación.

- Aquello que desconocemos será llamado **incógnita**.

- El **grado** de una ecuación vendrá dado por el mayor de los grados de los monomios que la conforman.

- Los **términos** son los sumandos que forman los miembros.


Un ejemplo de ecuación es la siguiente:

$$\underset{\underset {\mbox{1º miembro}}{\leftharpoonup }}{x+2}= \underset{\underset {\mbox{2º miembro}}{\leftharpoonup }}{2x+1}.$$

> 
> ## Actividades propuestas:
> 
> 1.De las siguientes ecuaciones, señala el primer miembro, el segundo miembro, la incógnita y el grado:
> 
> a) $$2x^2+4x=5x-3$$
> b) $3x+7=5x$
> c) $5a+4b=3a$
> d) $5a^4+10=\frac{a}{4}$
> 
> 2.En Cmap Tools realiza un mapa conceptual explicando los conceptos estudiados anteriormente.
> 
{: .challenge}

## 2. Ecuaciones de primer grado

Una ecuación de primer grado con una incógnita es una ecuación del tipo $ax+b=0$ con $a\neq 0$, $a,b$ valores conocidos. Se trata de hallar el valor de la incógnita $x$.

Cualquier ecuación de primer grado con una incógnita se podrá poner de la forma anterior. Para ello, se podrán ir realizando operaciones a los dos lados de la igualdad, de forma que si se realiza una operación en un lado también ha de hacerse en el otro.

Para despejar $x$ de la ecuación anterior, restamos $b$ a ambos lados de la igualdad, y, posteriormente, dividimos por $a$ también en ambos miembros. Esto hace que $x=\frac{-b}{a}$.

De forma gráfica se puede ver que la $x$ adquiere el valor del punto de corte entre las rectas $y=ax+b$ e $y=0$. Por ello, una ecuación de este tipo siempre va a tener una única solución.

> 
> ## Actividades propuestas:
> 
> 1. En el fichero *recta.ggb* encuentra la solución de la ecuación $f(x)=0$ usando sólo las herramientas de GeoGebra.
> 
{: .challenge}


## 3. Ecuaciones de segundo grado

Una ecuación de segundo grado con una incógnita es una ecuación del tipo $ax^2+bx+c=0$, con $a\neq 0$ y $a,b,c$ datos conocidos. En este caso la ecuación se resuelve mediante la siguiente fórmula:

$$x=\frac{-b\pm \sqrt{b^2-4ac}}{2a},$$

donde $b^2-4ac$ se denomina **discriminante**.

De forma gráfica se obtiene realizando el corte de la parábola $y=ax^2+bx+c$ con el eje $y=0$.

Una ecuación de segundo grado puede tener:

- 2 soluciones: Caso en el que $b^2-4ac > 0$.

- 1 solución: Caso en el que $b^2-4ac = 0$.

- Ninguna solución: Caso en el que b^2-4ac"<"0.

> 
> ## Actividades propuestas:
> 
> 1. Calcula a mano la solución de la ecuación $f(x)=g(x)$ donde $f$ y $g$ son las funciones definidas en el fichero *segundogrado.fkt*.
> 
{: .challenge}


## 4. Ecuaciones bicuadradas

Son aquellas que mediante el cambio de variables $z=x^2$ se convierten en una ecuación de segundo grado.

Para resolverlas realizamos los siguientes pasos:

1. Realizamos el cambio de variables $$z=x^2$$

2.  Resolvemos la ecuación de segundo grado en términos de $x$

3. Deshacemos el cambio de varibles $x=\pm\sqrt{z}$ 

## 5. Ecuaciones de segundo grado incompletas

Son aquellas en las que o $b$ o $c$ son nulos.

- En caso de que $b=0$ tendremos: $ax^2+c=0$ que se resuelve como $x=\pm\sqrt{\frac{-c}{a}}$.

- En caso de que $c=0$ tendremos: $ax^2+bx=0$ que, sacando factor común tenemos $x(ax+b)=0$. De donde tenemos que $x=0$ y que $ax+b=0$.


## 6. Ecuaciones con radicales

Son aquellas en las que la incógnita aparece en el denominador. Para resolver esta ecuación tenemos que hacer el mínimo común múltiplo de los denominadores para poder quitarlos. De esta forma habremos convertido nuestra ecuación en una ecuación polinómica.

## 7. Ecuaciones logaritmicas

Son ecuaciones formadas por funciones logarítmicas. Para la resolución de éstas es muy importante conocer las propiedades de los logaritmos:

\begin{tabular}{lll}
1.$\log_a 1=0$& 2.$\log _a a=1$  & 3.$\log_a a^n=n$ \\ 
4.$\log_a(x\cdot y)= \log_a x+ \log_a y$ & 5.$\log_a\left (\dfrac{x}{y}\right)=\log_a x - \log_a y$  & 6. $\log_a x^n=n\log_a x$\\
\end{tabular}

De esta forma, el objetivo es operar los términos de cada uno de los miembros de la ecuación de forma que al final nos quede una ecuación de este tipo:

$$\log_a(f(x))=\log_a(g(x)).$$

Para que se cumpla la igualdad anterior se tiene que verificar que $f(x)=g(x)$. Por tanto, pasaremos a resolver esta última ecuación.

Una vez resuelta hay que comprobar que la solución que estamos obteniendo es realmente solución de nuestra ecuación, ya que la función logaritmo no está definida sobre todos los valores reales, sólo para aquellos que son estrictamente mayores que 0.

> 
> ## Actividades propuestas:
> 
> 1.Haz un programa en Octave donde se implementen todas las propiedades de los logaritmos.
> 
{: .challenge}

## 8. Ecuaciones exponenciales

Las ecuaciones exponenciales son aquellas en las que la incógnita aparece en el exponente. 

Recordemos las propiedades de la potencias: 

\begin{tabular}{|l|l|l|}
\hline
1.$a^0=1$ & 2.$a^1=a$ & 3.$a^{-n}= \dfrac{1}{a^n}$ \\ 
\hline
4.$a^{\frac{m}{n}}= \sqrt[n]{a^m}$ & 5.$a^m \cdot a^n = a^{m+n}$ & 6.$a^m : a^n = a^{m-n}$ \\ 
\hline
7.$(a^m)^n = a^{m \cdot n}$ & 8. $a^n \cdot b^n = (a\cdot b)^n $ & 9. $a^n : b^n = (a: b)^n $\\
\hline
\end{tabular} 

Al igual que ocurría con las ecuaciones logarítmicas, si tenemos que $a^{f(x)}=a^{g(x)}$ se tiene que $f(x)=g(x)$.

Por todo esto, para resolver una ecuación exponencial primero tendremos que aplicar propiedades para poder llegar a tener en ambos miembros de la ecuación la misma base. Una vez lleguemos a este punto, igualamos los exponentes y resolvemos la ecuación.

En caso de que no se pueda llegar a lo que ocurría anteriormente, tendremos que hacer un cambio de variables o aplicar logaritmos en ambos lados de la ecuación, para ver si se puede resolver.

## 9. Ecuaciones trigonométricas

Son ecuaciones en las que aparecen funciones trigonométricas. Para resolverlas haremos uso de las fórmulas trigonométricas que conocemos:
\begin{itemize}
\item $\sen^2{x}+ \cos^2{x} =1$
\item $\tg{x}= \dfrac{\sen{x}}{\cos{x}}$
\item $ \cosec{x}=\dfrac{1}{\sen{x}} $
\item $ \sec{x}=\dfrac{1}{\cos{x}} $
\item $ \cotg{x}=\dfrac{1}{\tg{x}}$
\end {itemize}

Además de las siguientes propiedades:

\begin{tabular}{lll}


$\sen(180^{\circ} -x )=\sen x $ & $ \cos( 180^{\circ} - x ) = - \cos x $ & $\tg ( 180^{\circ} - x ) = - \tg x $ \\

$\sen(180^{\circ} +x )=-\sen x$ & $\cos( 180^{\circ} + x ) = - \cos x $&$ \tg ( 180^{\circ} + x ) = \tg x $ \\

$\sen(360^{\circ} - x )=-\sen x $ & $ \cos( 360^{\circ} - x ) =  \cos x $ & $ \tg ( 360^{\circ} - x ) = -\tg x $ \\

$\sen(90^{\circ} - x )=\cos x $ & $ \cos( 90^{\circ} - x ) =  \sen x $ & $ \tg ( 90^{\circ} - x ) = \dfrac{1}{\tg x} $ \\


\end{tabular}

El objetivo, es poner la ecuación en función de una única función trigonométrica. Una vez lleguemos a este punto haremos uso de la calculadora o de la siguiente tabla. Es importante tener en cuenta que a veces hay más de una solución que verifican la ecuación y que hay que hacer una buena comprobación.

\begin{tabular}{|c|c|c|c|c|c|c|c|c|}
\hline 
Grados & 0$^{\circ}$ & 30$^{\circ}$ & 45$^{\circ}$ & 60$^{\circ}$ & 90$^{\circ}$ & 180$^{\circ}$ & 270$^{\circ}$ & 360$^{\circ}$ \\ 
\hline 
Radianes & 0 & $\dfrac{\pi}{6}$ & $\dfrac{\pi}{4}$ & $\dfrac{\pi}{3}$ & $\dfrac{\pi}{2}$ & $\pi$ & $\dfrac{3\pi}{2}$ & $2\pi$ \\ 
\hline 
Seno & 0 & $\dfrac{1}{2}$ & $\dfrac{\sqrt{2}}{2}$ & $\dfrac{\sqrt{3}}{2}$ & 1 & 0 & -1 & 0 \\ 
\hline 
Coseno & 1 & $\dfrac{\sqrt{3}}{2}$ & $\dfrac{\sqrt{2}}{2}$ & $\dfrac{1}{2}$ & 0 & -1 & 0 & 1 \\ 
\hline 
Tangente & 0 & $\dfrac{\sqrt{3}}{3}$ & 1 & $\sqrt{3}$ & no definida & 0 & no definida & 0 \\ 
\hline 
\end{tabular} 

## 10. Sistemas de 2 ecuaciones lineales con 2 incógnitas

Un sistema de ecuaciones está formado por dos ecuaciones. La **solución** al sistema será aquella que verifique las dos ecuaciones implicadas.

Dependiendo de las soluciones que tengamos tendremos tres tipos de sistemas:

- Sistema Compatible Determinado: Tiene una única solución.

- Sistema Compatible Indeterminado: Tiene infinitas soluciones.

- Sistema Incompatible: No tiene solución.


Por un lado, podemos traducir este problema a un problema gráfico y por tanto, podemos dibujar cada ecuación de forma gráfica.

 $\left\lbrace
   \begin{array}{l}
     x+4y=2\\
     3x+5y=-1 \\ 
   \end{array}
   \right.$

Dibujamos entonces las gráficas de las dos retas anteriores. Se tiene que:

- Si las rectas se cortan en un punto tenemos una única solución.

- Si las rectas son coincidentes tenemos infinitas soluciones.

- Si las rectas son paralelas no tenemos solución.

De forma analítica tenemos tres métodos para resolver un sistema del tipo anterior:

- **Sustitución**. Se trata de despejar una de las incógnitas de una ecuación para sustituir de esta forma su valor en la otra ecuación. Tendremos así una ecuación en función de una sóla incógnita y por tanto ya sabemos resolverla.

- **Reducción**. Se trata de hacer operaciones con las dos ecuaciones para que, al restarlas, se vayan los términos que están en función de una de las dos incógnitas. De nuevo nos quedaremos con una ecuación en función de una única incógnita.

- **Igualación**. Despejaremos de las dos ecuaciones la misma incógnita para así poder igualar el segundo miembro de ambas ecuaciones y obtener de nuevo un ecuación con una incógnita.

> 
> ## Actividades propuestas:
> 
> 1.En el archivo *rectas1.ggb* encontramos dos rectas. En función de sus soluciones ¿qué tipo de sistema forman?
> 
> 2. En caso de que exista, ¿cuál es la solución del sistema anterior?
> 
> 3. En el archivo *rectas2.kig* encontramos otras dos rectas. ¿Qué tipo de sistema forman?
> 
> 4. En caso de que tenga solución, ¿cuál es ésta?
> 
{: .challenge}

## 11. Sistemas de 2 ecuaciones no lineales con 2 incógnitas

Los sistemas de ecuaciones no lineales son aquellas en las que al menos una de las ecuaciones no es del tipo $ax+by+c=0$ o equivalente. 

Para resolver este tipo de ecuaciones, usamos por lo general el método de sustitución. Para ello, despejamos una de las incógnitas de una de las ecuaciones (la que parezca más sencilla de despejar) y la sustituimos en la otra.

Otra forma de resolver estas ecuaciones es por cambio de variables.

Una última forma de resolver las ecuaciones no lineales es por el método gráfico. Este método se utiliza de igual forma que en el caso de los sistemas lineales. El único inconveniente es que puede ser que algunas de las funciones sean más difíciles de dibujar gráficamente. Para ello, podremos ayudarnos de algún programa con licencia libre, como los que mencionabamos en el capítulo 1 de este trabajo.

> 
> ## Actividades propuestas:
> 
> 1. En el archivo *nolineal.wxmx* están definidas las funciones $f$ y $g$. Resuelve el sistema formado por las ecuaciones $f(x)=0$ y $g(x)=0$ en Maxima.
> 
{: .challenge}

## 12. Sistemas de ecuaciones lineales, en general

Si tenemos un sistema de ecuaciones lineales con más de dos ecuaciones y dos incógnitas tenemos dos formas de resolverlo:

- Aplicando sustitución varias veces para que se verifiquen todas las ecuaciones.

- Aplicando el método conocido como método de Gauss.

El **método de Gauss** consiste en transformar un sistema de ecuaciones en otro escalonado. Para ello, hacemos ''ceros''  sometiendo las ecuaciones a transformaciones elementales. El proceso será más cómodo si, en lugar de las ecuaciones, utilizamos exclusivamente los números (coeficientes y términos independientes) estructurados en matrices. 

Al finalizar el proceso, o en algún paso intermedio, podemos encontrarnos con uno de los siguientes casos:

1. **Una fila de ceros**. Corresponde a una ecuación trivial y podemos prescindir de ella. 

2. **Dos filas iguales o proporcionales**. Corresponden a ecuaciones equivalentes y podemos prescindir de una de ellas.
 
3. **Una fila de ceros, salvo el último número (el término independiente) distinto de cero**. Evidentemente, se trata de una ecuación imposible. En tal caso, reconocemos de inmediato que el sistema es incompatible.


