
# Programa 8

**Descripción del problema:**

Queremos realizar un programa que modifique el número 7. Esta vez sólo queremos saludar pero, en vez de hacerlo uno a uno, lo haremos a todos a la vez, es decir, es necesario que recuerde los nombres y se dirija a ellos con un “Hola, persona1, persona2, persona3... y personaúltima”. 

**Materia nueva:**

Existe otro tipo de datos que se llama List (lista). Una lista es, tal y como se puede pensar, lo mismo que en la vida real salvo que, en Python, el primer elemento siempre es el 0. Imaginemos que queremos preparar una cena. Todo lo que se nos ocurra podemos hacerlo en Python, por ejemplo:



Vida real

Python

Contar el número de comensales:

len(lista) len es una abreviatura de length

Decir qué comensal ocupa el número 3, por ejemplo

lista[3] Siempre entre corchetes

Escoger del 7 al 14

lista[7:14] Tened en cuenta el 0!!

Añadir uno al final

lista.append(otrocomensal)

<br /><br />



Hay muchas más posibilidades, como se puede ver en:

[https://docs.python.org/3/tutorial/datastructures.html](https://docs.python.org/3/tutorial/datastructures.html)



Este tipo de datos hay que declararlos, bien para decir que están vacíos, bien porque los queremos con datos iniciales. 



Se declara nombrando la lista y poniendo:



listanueva=**[] **Si la queremos vacía para ir llenándola a lo largo del programa.



listanueva= **[**"Lunes","Martes","Miércoles","Jueves","Viernes"**] ** Si queremos los días laborables. Es decir, se introducen los elementos separados por comas.



De momento, nos conformaremos con lo expuesto y resolveremos el problema.

Ahora retomaremos a una vieja conocida: **str(**algoqueconvertiratexto**)**

Esta función también puede convertir una lista a texto. Usadlo en este programa: **str****(**lista**)**

