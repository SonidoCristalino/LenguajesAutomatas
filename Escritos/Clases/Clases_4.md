
# Tema nº 3:

## Video parte nº 1:
	https://www.youtube.com/watch?v=L1jg1-EFAFI&t=4s&ab_channel=JorgeO

## Video parte nº 2:
	https://www.youtube.com/watch?v=aX6Nrxmd0Gc&t=3s

## Video Parte nº 3:
	https://www.youtube.com/watch?v=75WZerUllKo&t=3s


# De los videos de Gerónimo:
	Clase nº 4:
	https://drive.google.com/drive/u/0/folders/1aoYaZHiWjfOpLxfIsHIHvbktgZ3D814w
	[59:50]



# Tipos de Relaciones:
[01:05:00] : Siempre conviene dibujar los conjuntos para cuando en los ejercicios pide analizar el tipo de relación.

Las mismas pueden ser como la de Bases de datos:
	* Uno a uno
	* Uno a muchos
	* Muchos a uno
	* Muchos a muchos

# Propiedades de las relaciones:

	## Propiedad reflexiva:
		Debe existir los elementos conformados por un mismo subelemento, es decir (1;1), (2;2), etc...

	## Propiedad simétrica:
		Si existe el par (1;2), entonces debe existir el par (2;1).

	## Propiedad transitiva:
		Si existe (1;3) y el par (3;2), debe existir también el par (1;2).

	## Propiedad antisimétrica:
		Propiedad Antisimétrica del Subconjunto, la cual puede ser entendida como la Ley matemática que indica que cuando
		un Conjunto A es identificado como Subconjunto de B, y a la vez el Conjunto B puede señalarse también como
		subconjunto de A, entonces se concluye que los conjuntos A y B son iguales


# Ejemplo:
	El conjunto de los Naturales, se pretende analizar la relación binaria <= (que vendría a ser la relación ro), por lo que
	se pregunta:

	- ¿Es reflexiva?
		Si, porque como la relación incluye un =, entonces se puede decir que para cualquier elemento a, se cumple que
		a <= a, es decir que a es menor o IGUAL a sí mismo. Por lo tanto es reflexiva (como que se relaciona consigo
		mismo), deben existir los pares generales (x,x)
		Ojo que si la relación a analizar fuera SOLO "<" entonces ya no se cumpliría la propiedad de reflexión.
	- ¿Es simétrica?
		Si existe (a,b) debe existir (b,a). En esta relación ro, como es <=, entonces se puede decir que NO existe la
		simétrica, porque puede existir el (1;2) pero no se cumple que para (2;1).

	- ¿Es transitiva?
		Para decidir esto, se tiene que determinar a, b y c con algún elemento del conjunto de los Naturales. Por ejemplo:
			a = 1
			b = 2
			c = 3

		Entonces:
			si 1 <= 2 ---> VERDAD
			si 2 <= 3 ---> VERDAD
			si 1 <= 3 ---> VERDAD por lo tanto es transitiva.

## Composición de relaciones:

Las relaciones se pueden descomponer en relaciones más chicas, por lo que por ejemplo, la relación "es nieto de" se puede escribir
como "es hijo de" ^ 2, dado que Emiliano es hijo de Alberto y Alberto es hijo de Alfredo, por lo tanto Emiliano es nieto de
Alfredo.
Más esquemáticamente:
	Si tenemos 	AxB = ro1
			BxC = ro2
			AxC = (ro1 * ro2) = ro3

	Recordar que ro1, ro2, y ro3 son relaciones binarias. Por lo tanto se puede decir que ro3 es una composición de ro1 y ro2.

## Composición sobre sí mismo:
Si la relación binaria es de un conjunto sobre sí mismo (AxA) denominada ro, entonces se puede definir como (ro)^2.
El ejemplo nuevamente sería "es nieto de" = ("es hijo de")^2 consigo mismo.

Se puede decir que ro^(n+1) siendo ro^n la composición consigo mismo n veces.

## Clausuras de relaciones:
Una realción binaria se dice que es clausura de S (con respecto a una propiedad P) si:
	- ro* contiene la propiedad P.
	- la relación ro está incluida en ro*.
	- ro* es un subconjunto de cualquier otra relación sobre S que incluye ro y contiene la relación P.

En síntesis: La clausura de una relación ro, con respecto a una propiedad P van a ser todos los pares que cumplen con la relación
ro, y a su vez los pares que tienen la propiedad P .

## Ejemplo de Clausuras de relaciones:
[01:20:00]
Sea el conjunto S = {1,2,3} y la relación ro = {(1;1), (1;2), (1;3), (3;1), (2;3)}

Se puede decir que NO cumplen con la propiedad reflexiva, transitiva ni simétrica, por lo que se forzará a que si la cumplan.

## Clausura de la relación Ro con respecto a la propiedad Reflexiva:

Para generar una clausura, lo que hay que hacer es hacer cumplir la propiedad reflexiva agregando todos los pares que cumplen
esto, más los pares que cumplen con la relación ro.

Recordar que la reflexiva es que el elemento del par, tiene que ser igual al otro (1;1), (2;2), (3;3), etc.

	Tenemos la Relación ro = {(1;1), (1;2), (1;3), (3;1), (2;3)}
		- El par (1;1) ya existe
		- Como el conjunto S = {1;2;3} entonces faltan: (2;2) y (3;3), que se agregan.

	Nueva Relación ro que cumple con la Reflexiva = {(1;1), (1;2), (1;3), (3;1), (2;3), (2;2), (3;3)}

## Clausura de la relación Ro con respecto a la propiedad Simétrica:
Recordar que la propiedad Simétrica establece que si existe el par (1;2), entonces debe existir el par (2;1).

	Tenemos la Relación ro = {(1;1), (1;2), (1;3), (3;1), (2;3)}
	Se analiza cada par y se ve que:
		(1;1) => Ya existe su simétrica (1;1)
		(1;2) => Se debe agregar el par (2;1)
		(1;3) => Ya existe su simétrica (3;1)
		(3;1) => Ya existe su simétrica (1;3)
		(2;3) => Se debe agregar el par (3;2)

	Nueva Relación ro que cumple con la Simétrica= {(1;1), (1;2), (1;3), (3;1), (2;3), (2;1), (1;3)}

## Clausura de la relación Ro con respecto a la propiedad Transitiva:
[01:31:00]

	Tenemos la Relación ro = {(1;1), (1;2), (1;3), (3;1), (2;3)}

Para poder hacer cumplir la Clausura se tienen que ordenar en 3 columnas, los pares que se tienen para saber qué pares faltan.
Ver que para el primer ejemplo lo que se tiene es a=1, b=1, por lo tanto el siguiente par a poner en la segunda columna tiene que
empezar con 1 por ser b=1, por lo se sigue con el siguiente par (1,2):

	(a,b) 		(b,c) 		-> 	(a,c)
	-----		-----		-------------
	(1,1)		(1,1)		->	(1,1) -> existe
	(1,1)		(1,2)		->	(1,2) -> existe
	(1,1)		(1,3)		->	(1,3) -> existe

	Nota: Todas las evaluaciones que hagamos con el par que contiene los elementos iguales, siempre van a estar dentro de la
	relación, ejemplo (1,1), (2,2), o (5,5), etc.

Vamos con el siguiente:
	(a,b) 		(b,c) 		-> 	(a,c)
	-----		-----		-------------
	(1,2)		(2,3)		-> 	(1,3) -> existe

Con el tercero:
	(a,b) 		(b,c) 		-> 	(a,c)
	-----		-----		-------------
	(1,3)		(3,1)		-> 	(1,1) -> existe

Con el cuarto:
	(a,b) 		(b,c) 		-> 	(a,c)
	-----		-----		-------------
	(3,1)		(1,1)		-> 	(3,1) -> existe
	(3,1)		(1,2)		-> 	(3,2) -> agregar
	(3,1)		(1,3)		-> 	(3,3) -> agregar

COn el quito:
	(a,b) 		(b,c) 		-> 	(a,c)
	-----		-----		-------------
	(2,3)		(3,1)		-> 	(2,1) -> agregar

Ahora hay que hacer la evaluación con los nuevos pares agregados: (3,2), (3,3) y (2,1)

	Nueva Relación ro = {(1;1), (1;2), (1;3), (3;1), (2;3), (3,2), (3,3), (2,1)}


El primer par nuevo:

	(a,b) 		(b,c) 		-> 	(a,c)
	-----		-----		-------------
	(3,2)		(2,3)		-> 	(3,3) -> Existe
	(3,2)		(2,1)		-> 	(3,1) -> Existe

El segundo par nuevo tiene los mismo elementos (3;3) por lo que no se hace nada porque el resultado va a estar dentro del
conjunto.

	(a,b) 		(b,c) 		-> 	(a,c)
	-----		-----		-------------
	(3,3)		No se hace por tener elementos iguales

El tercer par nuevo:

	(a,b) 		(b,c) 		-> 	(a,c)
	-----		-----		-------------
	(2,1)		(1,2)		-> 	(2,2) -> Agregar
	(2,1)		(1,3)		-> 	(2,3) -> Existe

	Nueva Relación ro = {(1;1), (1;2), (1;3), (3;1), (2;3), (3,2), (3,3), (2,1), (2,2)}

# Grafos
Es un conjunto no vacío de nodos y de arcos, cuya componente son tres:
	- N: conjunto no vacío de nodos.
	- A: conjunto de arcos
	- g: función (relación) que asocia cada arco con el par de nodos.

En la filmina "Clase3_1" en la página nº 35 se visualiza un ejemplo de cómo establecer una relación.

## Matriz de Adyacencia:
Los grafos se manipulan mediante matrices porque computacionalmente son fáciles de procesar, el procesador realizará funciones
entre matrices cuando en realidad lo que estará haciendo es dibujar grafos.
[01:46:00] Muestra el ejemplo con la matriz de adyacencia de la página nº 37

Sin arcos paralelos significa que entre dos nodos, siempre habrá un sólo arco de una dirección hacia la otra, puede haber uno más
pero en dirección contraria, pero no en la misma.

[01:51:30] Muestra un ejemplo de cómo a partir de un grafo dirigido se puede entender los pares que represetan la relación de los
arcos.
