---
title: "Funciones"
teaching: 15
exercises: 2
questions: 
- "Hacer uso del Software Libre en clase de Matemáticas"
objectives: 
- "Que aprendan conceptos básicos de Matemáticas en ESO"
keypoints: 
- "Trabajar con programas con licencia libre"
- "Realización de ejercicios"
---

La parte teórica de esta sección está obtenida de los apuntes elaborados por el grupo de Profesores de Matemáticas Aleph-Ronda que pueden encontrar en: http://ies.villablanca.madrid.educa.madrid.org/web/departamentos/matematicas/

Por otro lado, los enunciados de los ejercicios están tomados de: 

http://www.apuntesmareaverde.org.es/ donde se especifica que su tipo de licencia es BY-NC-SA. Mientras que las imágenes y resolución de los ejercicios, elaborados en las citadas aplicaciones de Guadalinex, han sido implementados por nosotras.


##1. Definición de función
Antes de plantear qué es una función necesitamos la siguiente definición previa.

**Variable dependiente** es la que está en función de otra que denominamos variable independiente. La variable dependiente se suele designar con la letra *y*, y la **variable independiente** con la letra *x*.

Una **función** es una relación o correspondencia entre dos magnitudes, de manera que a cada valor de la variable independiente *x* le corresponde un único valor de la variable dependiente *y*. Para indicar que una magnitud *y* depende o es función de otra *x* se utiliza la notación *y = f (x)*, que se lee "y es función de x".

A la hora de estudiar el comportamiento de una función nos encontraremos con puntos que serán de especial interés, por ejemplo:

- **Puntos de corte con el eje _Y_**. El punto de corte de una función *y = f (x)* con el eje *Y* tiene por abscisa *x = 0*. Por tanto, es el punto de coordenadas *(0, f (0))*.

- **Puntos de corte con el eje _X_**. Los puntos de corte de una función *y = f (x)* con el eje *X* tienen por ordenadas *y = 0*. Por tanto, son los puntos cuya coordenada x son soluciones de la ecuación *f (x) = 0*.

---

__Actividades propuestas:__


1. En el archivo cortesEjeY, encuentra cuál es el corte de la función indicada con el eje *Y*. Una vez hecho esto, cambia los rangos donde se dibuja la función para ver si es posible que corte al eje *Y* en otro punto, ¿es esto posible?
	
2. En el archivo cortesEjeX, encuentra cuál es el corte o los cortes de la función indicada con el eje *X*. Una vez hecho esto, cambia los rangos donde se dibuja la función para ver si es posible que corte al eje *X* en otros punto, ¿es esto posible?¿Podrías generalizar en qué tipo de puntos encontramos estos cortes?

---

##2. Dominio e imagen 
El **dominio** o campo de existencia de una función es el conjunto de valores que puede tomar la variable independiente
*x* (variable que se fija previamente). Se representa por Dom*(f)*.

La **imagen** o recorrido de una función es el conjunto de valores que toma la variable dependiente *y* (variable
que se deduce de la variable independiente). Se representa por Im*(f)*.

---

__Actividades propuestas:__

 1. En el archivo dominio, intenta deducir cuál es el dominio de la función que se presenta. Para ello presta especial atención al rango de valores en los que hemos pintado dicha función. ¿Qué ocurre en $x=-6$?
	
 2. Para el mismo ejercicios, ¿sabrías ver cuál es la imagen de esa función?

---

##3. Continuidad

Además de conocer puntos interesantes como los cortes con cada eje de coordenadas, nos interesa saber si hay puntos donde la función no esté definida, es decir, si la función es continua o si existen discontinuidades. Para ello necesitamos definir:

- Una función *y = f (x)* es **continua** si su gráfica puede dibujarse de un solo trazo continuo, es decir, sin levantar el lápiz del papel.

- Una función *y = f (x)* es **discontinua** si su gráfica no puede dibujarse de un solo trazo y, por tanto, presenta "saltos" en su trazado. Estos puntos en los que la gráfica de la función efectúa un salto se llaman puntos de discontinuidad.

---

__Actividades propuestas__


1. En el archivo continuidad, ¿sabrías ver en qué intervalos la función es continua? ¿Existe algún punto conflictivo? ¿Cómo lo sabes?
	
2. Realiza la misma deducción que en el ejercicio anterior pero usando el archivo continuidad2.


---

##4. Monotonía 

- Una función *y = f (x)* es **creciente** cuando al aumentar la variable independiente aumenta también la variable dependiente,  *x1 < x2 => f (x1) < f (x2)*. 

- Una función *y = f (x)* es **decreciente** cuando al aumentar la variable independiente disminuye la variable dependiente, *x1 < x2 => f (x1) > f (x2)*.

- Una función *y = f (x)* es **constante** cuando al aumentar la variable independiente la variable dependiente
no varía, *x1 < x2 => f (x1) = f (x2)*.

- Una función *y = f (x)* tiene un **máximo** en un punto *x = x_0* si, en valores próximos a él, a la izquierda de ese punto la función es creciente y a la derecha de ese punto la función es decreciente; esto es, si los valores próximos a él que toma la función son menores.

- Una función *y = f (x)* tiene un **mínimo** en un punto *x = x_0* si, en valores próximos a él, a la izquierda de ese punto la función es decreciente y a la derecha de ese punto la función es creciente; esto es, si los valores próximos a él que toma la función son mayores.

---

__Actividades propuestas:__

1. Observa la función representada en el archivo monotonía1 para poder concluir cuáles son los intervalos de crecimiento y decrecimiento de dicha función.
	
2. Utiliza el archivo monotonía2 para calcular los máximos y mínimos de la función que se muestra. Una vez los hayas encontrado, compruébalo utilizando el botón \textit{advanced}.

---

##5. Funciones constantes

Una función **constante** es aquella en la cual el valor de la variable dependiente siempre es el mismo sea cual sea el valor de la variable independiente. Su gráfica es una recta paralela al eje de abscisas *X* y su expresión algebraica es *y = n*.


##6. Funciones lineales

Las funciones **lineales** son aquellas cuya gráfica es una línea recta que pasa por el origen de coordenadas; su expresión algebraica es *y = mx*.

En la función lineal *y = mx*, al coeficiente *m* se le llama **pendiente** de la recta y se halla dividiendo el valor de la variable dependiente por el correspondiente valor de la variable
independiente; *m=y/x*.
Su valor es la medida del crecimiento o decrecimiento de la recta de ecuación *y = mx*.

##7. Funciones afines

Las funciones **afines** son aquellas cuya gráfica es una línea recta que no pasa por el origen de coordenadas; su expresión algebraica es *y = mx + n* donde *m* es la pendiente de la recta y *n* es la ordenada en el origen.

En este caso la pendiente se calcula del siguiente modo: * m=\dfrac{\mbox{incremento de la variable} \ y}{\mbox{incremento de la variable}\  x}=\dfrac{\bigtriangleup y}{\bigtriangleup x} *.

---

__Actividades propuestas:__

1. En el archivo tipo1 encontrarás una función que corresponde a uno de los tipos visto hasta ahora, ¿a cuál de ellos corresponde?¿Cuál es la pendiente de dicha función? 
	
2. Utiliza la aplicación \textit{KmPlot} para dibujar una función que sea lineal, decreciente y que tenga un corte con el eje $X$ en $x=2$.

---

##8. Funciones cuadráticas
Las funciones **cuadráticas** son aquellas cuya expresión es un polinomio de segundo grado, esto es, funciones de la forma *y=f(x)= ax^2+ bx + c*. Sus gráficas reciben el nombre de parábolas.

Este tipo de función presenta ciertas propiedades interesantes en su representación gráfica.

Sea *f(x)=ax^2+bx+c*, entonces:

- Si _a>0_ las ramas de la parábola se situan hacia arriba y diremos que la gráfica es convexa.
- Si _a<0_ las ramas de la parábola se situan hacia abajo y diremos que la gráfica es cóncava.
- Si aumentamos *c* la parábola se desplaza verticalmente hacia arriba.
- Si disminuye *c* la parábola se desplaza verticalmente hacia abajo.
- El vértice de la parábola se encuentra en el punto *\left( \dfrac{-b}{2a}, f\left( \dfrac{-b}{2a}\right) \right) *

---

__Actividades propuestas:__

1. En el archivo tipo2, encontrarás una función cuadrática. ¿Cuál es su vértice?
	
2. Utiliza el archivo del ejercicio anterior para contestar a las siguientes preguntas:

 a) ¿Qué ocurre si aumentas el parámetro $a$?

 b) Escoge un valor para $a$ negativo y luego aumenta su valor, ¿cuál es la diferencia con el caso anterior?


---

