
# Programa 9

**Descripción del problema:**

Este programa va a solucionar el problema de visualización del programa 8 cambiando la cadena de texto progresivamente. Es decir, una variable de texto va a incluir el saludo y los nombres de cada uno de los presentes. Para hacerlo, aunque hay muchas posibilidades, se va a modificar el programa 8. Esto implica que se van a seguir guardando los nombres en una lista.

**Materia nueva:**

Aquí hay varias apreciaciones respecto a la estructura **for**. 

Si nos paramos a pensar, el conjunto de los números enteros es como una lista. Los días de la semana forman otra lista, y un largo etcétera. Tenemos un elemento inicial y otros siguientes ordenados; eso define una lista.

Pues bien, **for **puede, no sólo recorrer una lista de enteros sino también una de cualquier otra cosa.



Su sintaxis es muy parecida a la que vimos en el programa 7 pero usando la lista dentro de **range**:

**for i in range(**lista**):**<br />



Si sólo fuera cuestión de números, podríamos haber simulado una estructura for por medio de un while:

i=0

**while** i&lt;numerofinal**:**

           órdenes

            i=i+1

Si **for **se ha ganado un puesto en Python es por la potencia que otorga esta posibilidad.

 

En este programa vamos a hacer referencia a dos situaciones más que van indisolublemente unidas:

- El cambio recurrente en las variables.
- La lectura de programas.

¿Por qué van unidas? Pues muy sencillo, porque para entender bien qué estamos realizando si cambiamos una variable cada vez que se ejecuta un paso en un **for** es necesario tener las ideas muy claras, y eso lo da la lectura de programas; debemos ser capaces de seguir la traza de las diferentes variables a lo largo del programa para saber cómo van a acabar.

¿Qué es un cambio recurrente? Es un cambio que se repite, generalmente dentro de una estructura tipo **while** y **for**.



No es algo del todo nuevo, hemos realizado cambios como veces=veces+1 donde hemos cambiado veces por su siguiente. La cuestión es que ahora lo meteremos en una estructura que va a realizar ese cambio un montón de veces. No hay ningún cambio de sintaxis, esta explicación no va a parar a ninguna orden o estructura nueva, es simplemente para que tomes conciencia del paso tan grande que se va a realizar.

A continuación te presento un método para hacer una lectura de programa. No es la única forma y cada uno puede hacerlo según le parezca, eso sí, el orden es imprescindible. 

Se pone: “Situación inicial” y se escriben las variables tal y lo que valen en su inicio.

Cuando hay un cambio, se escribe debajo de la variable el nuevo valor o la salida por pantalla. Así se va realizando hasta el final.

Es necesario poner la cadena de texto entre comillas para señalar que es texto.

Se representa a continuación el del programa 7:

Situación inicial

Pantalla

Personas (entero)

i

nombre

edad

veces

Hola, ¿Cuántos estáis?

“3”











3













0



















¿Cómo te llamas?





“Jorge”

















¿Cuántos años tienes?







“27”













1











“1”









27















Te hemos preguntado 1 veces











Pon orden, Jorge



1



















¿Cómo te llamas?





“Rodrigo”

















¿Cuántos años tienes?







“asd”













1













Pon un número, que no es tan difícil







“16”













2











“2”









16















Te hemos preguntado 2 veces











Estudia, Rodrigo



2



















¿Cómo te llamas?





“Inés”

















¿Cuántos años tienes?







“14”













1











“1”









14















Te hemos preguntado 1 veces











Estudia, Inés

3

2

“Inés”

14

“1”


<td colspan="6" width="557" valign="TOP" bgcolor="#ffffff">Situación final. En el caso de que quisiéramos ver otra situación, nos moveríamos a la línea en cuestión y miraríamos el valor de cada una de ellas. Las celdas en blanco no implican que las variables no tengan valor, su valor es el del último cambio: el primero que esté subiendo por esa columna desde la fila donde se quiere saber el valor. Simplemente se ha hecho así por limpieza e identificar fácilmente cuál es la variable que está cambiando en cada momento.</td>

Se deja como ejercicio hacerlo para el presente programa.

