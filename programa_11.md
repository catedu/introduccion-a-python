
# Programa 11

**Descripción del problema:**

Se desea realizar un programa que guarde el nombre, la edad y lo que se les recomendaba hacer, como teníamos antes, para un número de presentes que el usuario dirá. Después de preguntar la información de cada uno de ellos, el programa debe preguntar un número y dar la información referida a la persona que se introdujo en esa posición.

**Materia nueva:**

Los Diccionarios son un tipo de datos que puede guardar para una sola variable un conjunto de campos. Pongamos un ejemplo: Imaginemos un alumno. Existe un montón de información que podríamos querer guardar sobre él y hacer una tabla como:

|Nombre|Apellido 1|Apellido 2|Altura|Nº Calzado|Color de pelo|
|--|--|--|--|--|--|
Jorge|Bes|Tuán|2 m|47|Negro|

Cuando alguien nos preguntara por este alumno, lo haría diciéndonos: Dime el primer apellido del alumno, el color de pelo... Es decir, nos diría el campo que quiere. Tras esto, nosotros iríamos a la celda y responderíamos con la información allí contenida. 

Bueno, pues esto es un Diccionario para Python. Tiene unos valores que se llaman Key que en este caso sería la fila superior ( Nombre, Apellido1...) y otros que se llaman Value que serían los de la fila inferior.

Una duda que suele asaltar es: ¿Por qué sólo una fila? ¿Y si queremos guardar un conjunto de 1000 alumnos? Pues muy sencillo, se hace una lista de diccionarios, que es lo que vamos a hacer en nuestro programa. Al fin y al cabo, una lista es un conjunto de cosas, nadie ha dicho que haya algo que no se pueda meter ahí.

La sintaxis para declarar un diccionario vacío es:

diccionario **={}**

Y para guardar cualquier dato es:

diccionario[“Key1”]=datoaguardar

Aquí hay que decir que, a diferencia de las listas, donde había que añadir un nuevo componente con una orden, aquí es tan fácil como poner una nueva "Key" para que la añada al conjunto de ellas. Es decir, es como tener una tabla dinámica donde podemos añadir columnas sobre la marcha.

Un diccionario tiene muchísimas más posibilidades en Python, como se puede ver en:

[https://docs.python.org/3/library/stdtypes.html#typesmapping](https://docs.python.org/3/library/stdtypes.html#typesmapping)

No obstante, en este curso no se va sino a introducir este tipo de variable. Queda demostrada la potencia de Python y el nivel de abstracción de los datos y se anima a los alumnos a completar su formación conforme lo vayan necesitando para sus proyectos. 

NOTA: Si vas a introducir cambios en un diccionario dentro de una estructura como **for** o **while**, que los ejecutará varias veces, declara esa variable dentro de la estructura y no fuera. Más adelante se explica el por qué. 

