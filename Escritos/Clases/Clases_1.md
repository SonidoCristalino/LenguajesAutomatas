
# Profesor:
	Jorge Osio

# Materia:
	Lenguajes Formales y Autómatas

# Link:
	https://meet.google.com/ith-jffx-zob

# Modalidad:
	Teórico-práctico

# Método:
	El tipo de cursado es todo práctica, se requieren hacer toda la práctica.
	No toma asistencia por clase, para que haya asistencia hay que completar los cuestionarios (todos en el campus). Son
	pequeños cuestionarios por clase. Todo de la práctica, y poco de teoría.
	Los cuestionarios los abre el profesor y tienen un tiempo de una semana (se habilitan luego de dar el tema
	correspondiente).

## Sitio NO oficial:
	En caso de que se caiga el campus, se pide acceso al profesor y está todo el contenido del campus.
	Todo lo que se trabaja, se trabaja EN EL CAMPUS, en caso de que se caiga el campus, entonces se puede ir al sitio NO
	oficial.

## Laboratorio:
	Tiene dos partes. La primera parte se da cuando se presenta el tema correspondiente en el módulo y la segunda parte lo
	mismo. Se utiliza un simulador. Se programan en lenguaje C. Son grupales.

## Para resolver las prácticas, ejercicios:
	Para resolver algunos ejercicios o prácticas, se puede utilizar la calculadora de tabla de verdad siguiente (el único
	problema es que en vez de A, B, C, se utilizan letras tales como p, q, r):
	https://calculadorasonline.com/generador-de-tablas-de-verdad-logica-proposicional-algebra-booleana/

## Consultas:

¡¡Si dice PREGUNTAR es para consultarle al Profesor en clase!!

Todos los videos son Video-explicaciones son teórico-prácticas.

La cursada final se aprueba entre 4 y 6, promoción tiene que ser mayor o igual a 7, se accede a un coloquio donde se le hace un
par de preguntas que estaban en el examen.

El examen: Son preguntas para desarrollar. Se tiene un total de 2.45hs para resolver el examen. No se puede volver a la pregunta
anterior, una vez que se pasa de pregunta, ya se cierra.

# Campus:
	Ver video nº 1 - Tema nº 1

FBF = Fórmula bien formada, se considera una expresión lógica que puede estar formada por un conectivo. A eso se lo llama lógica
bien formada. No es lo mismo que una proposición.


Funciones Booleanas, se aplican sólo sobre una sola proposición. Se pueden hacer conectivos que vuevlan falsos la tabla de verdad,
la idea es preguntarse ¿Cuántos conectores se pueden crear? La cantidad de funciones diferentes serán dependiendo la cantidad de
conectivos que se tengan, en este caso son dos, P y Q, su combinación es 4.
Todas las funciones que se pueden generar a partir de una proposición genérica y se expresa de la siguiente manera: 2^(2^n)

Forma Normal Disyuntiva:
	(~P ^ ~Q) v (P ^ Q)

Forma normal Conjuntiva: se tienen que unir con una conjunción, ver que en el medio de las dos proposiciones hay una conjunción y
entre las dos, son una disyunción.
	(~P v ~Q) ^ (P v Q)

Literal es una letra o su negación.

# Videos 1 - Parte 1:
Permite explicar razonamientos lógicos, y a partir de las hipótesis, llegar a concluir si
La Lógica nos permite:
	- También permite mecanizar tareas complejas.
	- Verificar si los programas hacen lo que se espera que hagan
	- Los ordenadores al estar integrados por circuitos lógicos, estudar la lógica nos permite entender en funcionamiento del
	  ordenador.
	- La lógica formal se puede considerar un lenguaje de programación.

Utilizamos el razonamiento a la hora de aplicar la lógica en nuestra vida cotidiana. A partir de determinadas premisas y mediante
la experiencia las evaluamos y aprendemos según esos hechos. Las conclusiones se pueden obtener mediante la siguiente lista de
frases:
	- Por lo tanto
	- Se concluye que
	- Entonces
	- De esto sigue que

# Reglas:
La más conocida es la Modus Ponens:
	- A y B son sentencias.
	- A -> B es Verdadera.
	- A es Verdadera.
	- Se concluye entonces que B es Verdadera.

Ejemplo:
	- A : Llueve.
	- B : Hay nubes en el cielo.
	- Si hay nubes en el cielo entonces llueve .
	- Llueve efectivamente.
	- Por lo tanto se concluye que hay nubes en el cielo.

Modus Tollens:
	- A y B son sentencias.
	- A -> B es Verdadera.
	- B es Falsa.
	- Se puede concluir que A es Falsa.

Ejemplo:
	- A : Llueve.
	- B : Hay nubes en el cielo.
	- Si hay nubes en el cielo entonces llueve.
	- B : Hay nubes en el cielo es falso.
	- A : Llueve es falso.


# Falacias:
	Son expresiones que son inconsistentes:

Ejemplo:
	- Todo lo que brilla es de oro
	- Esta daga brilla.
	- Entonces es de oro

	No se puede inferir la verdad de esto ya que no todo lo que brilla es oro

# Cálculo proposicional:
Una oración sin importar que sea verdadera o falsa se la denomina proposición. Se utilizan conectivos lógicos tales como:
	* ~   [Negación]
	* ^   [Conjunción]
	* v   [Disyunción]
	* ->  [Implicación]
	* <-> [Equivalencia]

Sintáxis: Se alude a la gramatica, si está bien sentenciada gramaticalmente. Es decir, si hablamos de un lenguaje de programación,
lo que hacemos referencia cuando hablamos de sintaxis, es si las instrucciones que se utilizaron para programar forman parte del
set de palabras de ese lenguaje de programación.
Ejemplo de la sintáxis en lógica:
	- Símbolos de verdad: V o F
	- Conectivos: ~, ^, v, ->
	- Variables proposicionales: P, Q y R
	- Símbolos de puntuación (,)

Semántica: Se alude al significado de la expresión. Si hablamos de un lenguaje de programación, entonces si hace referencia con
ello a si el conjunto de instrucciones cumple con las tareas requeridas por el código o no.

Se puede dar el caso que el conjunto de instrucciones sea sintácticamente correcto (es decir que las palabras empleadas forman
parte del set de palabras del lenguaje) pero que no cumpla con el propósito primero del programa, no cumple con el significado.

Una Fórmula Bien Formada (FBF) es una sentencia que cumple con lo siguiente:
	- Un símbolo de verdad
	- Una letra proposicional
	- La negación de una FBF
	- La conjunción de dos FBF
	- La disyunción de dos FBF
	- La implicación de una FBF a otra FBF
	- Una FBF rodeada de un paréntesis

Ejemplo:
	- Verdadero
	- Falso
	- P -> Q
	- ~P
	- (PvQ) ^ R
	- P ^ Q -> R


Para establecer una tabla de verdad para una FBF se debe primero establecer un orden de jerarquía. Teniendo en cuenta lo
siguiente:
	- ~ : Tiene mayor precedencia
	- ^
	- v
	- -> : Menor precedencia, se aplicaría a lo último

Por ejemplo:
	- P v Q ^ R  	Se debería de resolver de la siguiente manera: P v (Q ^ R)
	- p -> Q -> R 	Como se tienen dos implicaciones, entonces se resuelve de izquierda a derecha: (P -> Q) -> R
	- ~~P 		Aplicamos el mismo criterio que antes, por lo que quedaría: ~(~P)

# Errores lógicos:

	Tautología:
	Se denomina así cuando los valore de verdad de una FBF son siempre verdaderos.

	Contradicción:
	Se denomina así cuando los valore de verdad de una FBF son siempre falsos.

	Contingencias:
	Se denomina así cuando los valore de verdad de una FBF son a veces vedaderos y a veces falsos.

Equivalencias:
Dos FBF son equivalentes cuando tienen la misma tabla de verdad. Se puede escribir: A <-> B

En semántica, existen algunas equivalencias y conversiones también. Para ello revisar la filmina nº 1 donde se encuentran todas
las leyes.
En cualquier sub expresión de una FBF, se puede escribir una FBF equivalente SIN CAMBIAR el valor de verdad de la sub-expresión
original.

# Funciones Booleanas
Existen tantos conectivos unarios como cantidad de proposiciones existan, si tenemos dos como en el caso de las filminas, entonces
podrán existir 4:
	- Una negación (como ya vimos que existe).
	- Un conectivo que haga todo verdadero.
	- Un conectivo que haga todo falso.
	- Un Conectivo que no haga nada.

Se pueden definir tantos valores de verdad siguiendo la fórmula 2 a la 2^n, donde n es la cantidad de variables que estén en
juego: En el ejmplo de las filminas con dos proposiciones podemos definir 16 conectivos diferentes.

# Video nº 1 - Parte nº 2:

## Conjunto completo de Conectivos:
Dado que se puede expresar cualquier función de verdad utilizando sólo los conectivos estudiados {v, ^, ~, ->} se dice que el
conjunto es completo.

Por la propiedad de la sustitución, dado que el conjunto anteriormente mencionado es completo, también lo son los conectivos {~,
v},{~, ^}.

## Forma Normal Disyuntiva (FND):
Mediante una tabla de verdad es posible obtener de una FBF una forma normal disyuntiva; esta de define como la expresión que tiene
los términos relacionados con una disyunción (v) y dentro de cada término, las proposiciones están relacionadas por una
conjunción.

Para esto, se debe hacer la tabla de verdad de las proposiciones de la Disyunción Exclusiva (XOR : <->), y observar los valores
VERDADEROS. Por cada valor verdadero, vamos a tener un término de la expresión en la forma normal disyuntiva.

[2:50] Para formar estas expresiones, se deben basar en los resultados VERDADEROS como se dijo anteriormente. Entonces a partir
del resultado se leen los valores para cada proposicion. Podemos ver que en el primer caso es:
	- V | F -> V
	Por lo tanto se considera a P como verdadero y a Q como Falso (~Q), siendo la expresión:
		* P ^ ~Q

	- F | V -> V
	Por lo tanto se considera a P como falso (~P) y a Q como verdadero Q, siendo la expresión:
		* ~P ^ Q

	- Luego se unen cada término mediante la disyunción y ya se tiene la Forma Normal Disyuntiva.

Hay que recordar que toda FBF será equivalente a una Forma Normal Disyuntiva.

## Forma Normal Conjuntiva (FNC):
Se siguen los mismos pasos que en la Forma Normal Disyuntiva, sólo que acá nos interesan los *resultados falsos*. Se tiene que
poner mucha atención en ver que operandos se consideran FALSAS, en contraposición a lo que se considera en la Forma Normal
Disyuntiva.

[4:09] Para formar estas expresiones se tiene que hacer la tabla de verdad de los operandos implicadas de la Disyunción
Exclusiva (XOR : <->). Nos interesan los resultados FALSOS. En la primera línea de la tabla, como el resultado es Falso, entonces
razonamos que será necesario que los operandos sean falsos para poder obtener ese resultado por lo tanto se niegan ambas (Para
que dos operandos verdaderos sean falsas, es necesario entonces que las dos estén negadas).

En la cuarta línea de la tabla, cuyo resultado también es falso, vemos que los dos operandos son falsas, por lo que no se niegan.

## Funciones de verdad y Formas Normales
Si queremos obtener una FNC o FND a partir de una tabla que no tiene ningún valor verdadero, es decir que es falso, se puede
recordar las siguientes equivalencias:
	* P ^ ~P = Falso ( en caso de ser P = verdadero )
	* P ^ ~P = Verdadero ( en caso de ser P = falso )

## Terminología:
Un literal es una letra proposicional o su negación: P, ~P, etc.

[8.40] Conjunción fundamental es o bien un literal o una conjunción de dos o más literales: P, P ^ Q, etc.

Ejemplo:
	* P V (Q ^ P),
	* ~P, ~P V ~Q,
	* (P ^ Q ^ R) V ( Q ^ R ^ P), etc.

Estos ejemplos también se pueden considerar como FND por definición, ya que cada uno de ellos es una Conjunción Fundamental.

## Formas de obtener FND:
Otra manera es el uso de equivalencias que permitan transformar una FBF en FND.

Los pasos son los siguientes:
	* Se sustituyen todas las implicaciones (->) por una disyunción y un literal negado:
	  	- A -> B = ~A V B
	* Luego se debe aplicar las leyes de De Morgan, por ejemplo:
	  	- ~(A ^ B) = ~A V ~B
		- ~(A V B) = ~A ^ ~B
	* Aplicamos las leyes distributivas para obtener una FND:
	  	- A ^ (B V C) = (A ^ B) V (A ^ B)
	  	- A V (B ^ C) = (A V B) ^ (A V B)

## Formas de Obtener una FNC:
Una FNC es una disyunción fundamental o la conjunción de una o dos disyunciones fundamentales. Como por ejemplo:
	* P ^ (~P V Q)
	* (P V Q) ^ (~P V Q)
	* P
	* ~P
	* P ^ ~P

Se puede obtener una equivalencia como se hizo con la FND, aplicando los mismos procedimientos.

# Forma Completa
Una Forma Completa se denomina Forma Normal Disyuntiva completa a una FBF si cada conjunción fundamental tiene exactamente N
literales. Por ejemplo:
	* ( P ^ Q ^ R) V ( ~P ^ Q ^ R) = Es una Forma Normal Disyuntiva porque tiene cada uno de sus literales en cada una de sus
	  preposiciones.
	* P V (~P ^ R) = es una FND pero NO es una FND Completa ya que NO tiene todos sus literales en cada una de las
	  preposiciones que la conforman.

La Forma Normal Conjuntiva Completa es análoga a FNDC anteriormente descripta.

[17:00] Ver el ejemplo que se pone para poder obtener una Fórmula Normal Disyuntiva Completa. La idea es que para que aparezcan en
cada término todas las letras hace falta ingresar términos que contengan ese literal faltante para luego llegar a una forma
completa, por ejemplo:
	* P V (~P ^ R) = Es una FND pero sabemos que no es Completa porque le falta uno de sus literales. Por ende habría que
	  completarla en el primero de sus términos.

	1. P V (~P ^ R) : Vemos que en la primer preposición, hace falta uno de los literales, R.
	2. (P ^ (~R ^ R )) V (~P ^ R) : Se agrega un nuevo término que NO modifica el valor de verdad de toda la expresión.
	3. (P ^ R) V (~P ^ R) : Podemos ahora ver que en ambas preposiciones, han quedado los mismos literales. Por lo que se
	   puede concluir que termina siendo una FND Completa. PREGUNTAR

## Razonamiento Formal:
Ya que realizar lo anterior sería muy engorroso a la hora de manejar muchas preposiciones con muchos literales, lo que se
establece para poder salvar esta problemática es el Razonamiento Formal.

## Reglas de inferencia
Patrón sintáctico que establece que a partir de un conjunto de premisas (hipótesis o antecedentes) podemos derivar en una
conclusión. Se sobrentiende que las premisas son verdaderas, por lo tanto con esta regla, se puede inferir que la conclusión será
verdadera también.

Lo que se desea es que las reglas de inferencia preserven la verdad. ¡Lo que se busca es nuestras expresiones sean una tautología!,
lo que significa que P1 ^ P2.. ^ Pk -> C será también verdadera.

### Modus Ponens
Si A es verdadera, y A -> B también es verdero, entonces se concluye que B es verdadera. Por ejemplo una tautología de este tipo
podría ser:
	* ( A -> B ) ^ ~B -> ~A 	= Esto supuestamente es una tautología y da todo verdadero, pero no se entiende cómo es
	  que llega a definir eso. PREGUNTAR

### Otras reglas básicas:

## Regla de la Conjunción:
	- Si A es verdadera
	- Si B es verdadera
	- Entonces A ^ B será verdadera

## Regla de la Simplificación:
	- Si A ^ B es verdadera
	- Entonces A será verdadera

## Regla de Adicción:
	- Si A es verdera
	- Entonces A V B será verdadera.

## Silogismo Disyuntivo (SD):
	- Si A V B es verdadero
	- Si ~A es verdadero
	- Entonces B será verdadero

## Silogismo Hipotético (SH):
	- Si A -> B es verdadero
	- Si B -> C es verdadero
	- Entonces A -> C será verdadero.

# AXIOMA
Un acciona es una FBF que se usa como base a partir de la cual se utilizará para razonar. Un accioma es usualmente una FBF que
conocemos como verdadera. Un axioma es algo que queremos que sea verdadero.

## Prueba
Una prueba es una secuencia finita de FBF con la propiedad de que cada una de estas FBF es un axioma, es decir, que contiene un
valor de verdad a partir del cual se puede razonar. La última FBF en la secuencia, es lo que se denomina *Teorema*.

Estas pruebas se escriben en forma de tablas, en donde cada línea (columna número 1) está enumerada y contiene una FBF (columna nº
2) junto con la razón por la cual fue incluída.

Un ejemplo de prueba sería:
	1. W			Razón por la cual W fue incluida
	2. X			Razón por la cual X fue incluida
	3. Z			Razón por la cual Z fue incluida
	4. ...

# Prueba condicional directa (PCD):
Se tiene una tabla donde la primer columna es la FBF y la siguiente columna es su justificación:

	1. A 				Premisa
	2. B 				Premisa
	3. C 				Premisa
	4. ...
	N. D				...
	N + 1. A ^ B ^ C -> D 		1, 2, 3,...,N, Prueba condicional.

[13:20] Explica cómo proceder con las Pruebas Condicionales. ¡Tener cuidado! Porque cuando se realiza una sub-prueba, no se puede
justificar un paso LUEGO de la sub-prueba refiriéndose a alguno de los pasos que se hicieron en la sub prueba, sino que de la
sub-prueba SOLO se puede utilizar la conclusión [21:00].

# Prueba condicional indirecta (PCI):
Consiste en tomar las premisas (que son las del lado izquierdo de la implicación) pero a su vez, tomar como premisa NEGADA el lado
derecho de la implicación. Siempre en la prueba indirecta se niega el consecuente. En algún punto se debería de llegar a un falso.
Cuando se llega a eso, se puede concluir que la expresión es verdadera.

[26:30] Explica un poco cómo realizar las pruebas estas.

# Sensatez:
Lo que se quiere explicar con sensatez es que se quiere que todas las pruebas de los teoremas devuelvan una tautología.

# Completitud:
Lo que se quiere es que todas las tautologías sean probadas como teoremas.

## Ejercicio nº 6:
	Para resolver el ejercicio nº 6, hay que ver las tablas de equivalencias, De Morgan, etc.
	Ver las propiedades a aplicar [ver las fotos]
	Hay que ir reemplazando hasta que queda simplificado, según el profesor se resuelve todo utilizando las equivalencias que
	están listadas en las filminas (absorción, De Morgan, etc).

## Ejercicio nº 7:
	Una es con la tabla de verdad, armarla y en función de los resultados nos quedamos con los resultados verdaderos o falsos
	(dependiendo qué método utilicemos). POr la tabla de verdad permite la Forma Normal.
	El b) ya está en forma normal conjuntiva, si se quiere obtener la disyuntiva, se aplica distribuitva entre R (ver
	imágenes), hay que operar hasta que quede de alguna FND o FNC

	a) es una implicación, hay que tener ojo con los términos para saber que se resuelve último la implicación, quedando:
		(Q^~P) -> P
	Recién ahí se pone la Equivalencia de la implicación (ver los pasos que se deben seguir):
		~(Q^~P) v P
	Se aplican De Morgan:
		(~Q v P) v P
		~Q v P 			-> Es una disyunción fundamental, y por definición es FNC porque es una disyunción
		fundamental [Imagen]

	También se puede ver de la siguiente manera (para que exista una conjunción):
		(~Q ^ P) ^ Verdadero	-> Ahora se puede ver que es una FNC.

	También se puede ver de la siguiente manera:
		~Q v P 			-> FND por ser una disyunción fundamental

	Básicamente hay que :
		- Sacarse de encima la implicación
		- En caso de que haya una negación, aplicación de De Morgan
		- En algunos casos hay que hacer distributiva

## Ejercicio 17:

Inciso b) prueba condicional directa.
Como está separado por paréntesis, La implicación es lo que hay que terminar resolviendo.
Hay que definir las premisas, la parte izquierda recordar que se toma como verdadero.
1. (A v B -> C ^ D) 	=  Premisa

	2 posibilidades:
		- Hago una subprueba con B -> D
		- La premisa se puede expresar de una forma más amigable, buscarle una equivalencia. Este es el mejor camino para
		  no ir directamente con una subprueba. Hacemos este segundo camino:

2. ~(A v B) v (C ^ D) 	= por 1 y equivalencia

	Se aplica De Morgan en el primer término:
		~A ^ ~B

	Se obtiene entonces:
		(~A ^ ~B) v (C ^ D )	= Por dos y De Morgan

	Lo único que se sabe es la disyunción es verdadera, pero la disyunción no permite sacar una conclusión ya que tiene 3 valores
	posibles para que sea verdadero. Entonces en este punto se debería de aplicar la Sub-prueba.

3. B es verdadero = premisa para Sub-prueba. Si se llega a probar B -> D como verdadero, entonces se llega a que toda la ecuación
	demostrada.

	(~A ^ ~B) Hay que probar que todo esto es FAlso

4. Se puede decir que A v B será verdadero por 4 y por disyunción [Imagen]
5. C ^ D es verdadero por 2, 5, y Silogismo Disyuntivo.
6. D es verdadero pro el paso 6 y la propiedad conjunción.
7. Se puede decir que (B -> D) es verdadero por 4, 7 y Prueba Condicional - Fin de la sub-prueba
8. (A v B -> C ^ D) -> (B -> D) es verdadero por 1, 8 y Prueba Condicional

Otro Camino posible hubiera sido:
(A v B -> C ^ D) -> (B -> D)
1. (A v B -> C ^ D) 	es verdadera por premisa
2. B	es verdadero por premisa de la subprueba (B -> D)
3. (A v B) es verdadero por 2 y Disyunción
4. Si la implicación es verdadera y el lado derecho era verdadero entonces el lado izquierdo será verdero. Entonces (C ^ D) será
   verdadero por 1, 2, y MP
