
# Primera parte:

Teniendo un grafo dirigido sin arcos paralelos, podemos representarlo utilizando una matriz de adyacencia, pudiendo representar
las relaciones del grafo mediante relaciones binarias.

Recordar:
	* La Fila nos indica el nodo SALIENTE.
	* La Columna el nodo ENTRANTE.

## Clausuras reflexiva:
Para operar con matrices, se puede obtener la clausura reflexiva, siendo M una matriz, de la siguiente manera:
	M v M^o (Matriz disyunción con su identidad)

## Clausuras simétrica:
Se puede obtener la matriz de adyacencia cuya clausura sea la simétrica operando de la siguiente manera:
	M v M^t (Matriz disyunción con su traspuesta)

## Clausuras transitiva:
Se puede obtener la matriz de adyacencia cuya clausura sea la transitiva operando de la siguiente manera:
	M v M^2 v M^3 v M^4... M^n

[11:05] Ejemplo de cómo se puede operar una matriz de adyacencia

Dependiendo de las dimensiones de la matriz, serán las veces que se deberán de operar para obtener el resultado deseado, es decir:
	- En el ejemplo el rango de la matriz es de 5x5, por lo tanto se deberá de operar 5 veces consigo misma para poder obtener
	  el resultado deseado. Es decir que se realiza la operación: M v M^2 v M^3 v M^4 v M^5 = R (clausura transitiva).
	- Recordar que M^n NO ES la matriz elevado a la 5, sino la cantidad de operaciones binarias (producto booleano) operadas
	  consigo mismo.

# Algoritmo de Warshall
El algoritmo lo que permite obtener a partir de una matriz de adyacencia, es su clausura transitiva.
Lo que se hace en cada iteración, es el producto booleano M consigo mismo.

[21:00] Se discute el resultado de la Clausura Transitiva R que se obtiene mediante el Algoritmo de Warshall, cómo es que se lee.
A partir de ahí se corta el video y se pasa a la segunda parte:

# Segunda parte:
Se explica cómo proceder para encontrar la relación entre ro1 y ro2.

# Practica 3 : 1
[16:40]

[30:00] Ejercicio nº 3

[50:40] Ejercicio nº 9
	a) EsCapitalDe es igual a c y p, que pertenece a ciudades por provincia tal que c es capital de p = relación de uno a uno,
	ya que a una provincia le corresponde una ciudad capital.

	b) InscriptoEn es igua a I y c, que pertenecen a Inscripto por carrera tal que el alumno que con Libreta Universitaria
	está inscripto en C = muchos a uno, ya que un alumno puede estar inscripto en varias carreras y varias materias pueden
	recibir a varios alumnos.

[56:00] Ejercicio nº 11 y 12
