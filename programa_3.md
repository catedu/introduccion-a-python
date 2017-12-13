
# Programa 3

**Descripción del problema:**

Ahora imaginemos que queremos que queremos modificar el programa anterior para que, una vez preguntado el nombre, si el usario se llama como nosotros, los programadores, le salude de una forma especial: "Eres un figura, mengano". Si no se llama como nosotros, le saludaremos normalmente como antes.

 

**Materia nueva:**

Signos de comparación:

Si queremos ver si una variable tiene un valor determinado, mayor, menor... lo normal es usar los signos que usaríamos en matemáticas, aunque hay alguna pequeña sorpresa, y que represento a continuación:

x==y         # x es igual a y. Mucho cuidado con esta comparación, se usan dos iguales seguidos.

x!=y        # x es distinto de y

El resto son los tradicionales:

x&gt;y          # x es mayor que y

x&lt;y          # x es menor que y

x&gt;=y        # x es mayor o igual que y

x&lt;=y        # x es menor o igual que y

<br />Primera estructura de control: If

If viene del inglés y es un condicional que significa si. El lenguaje usa la siguiente sintaxis:



**if** comparación :

       órdenes

**elif** comparación:

       órdenes

**else:**

       órdenes

<br />Traduzcamos esto teniendo en cuenta que elif es la abreviatura de else if y que else significa “en otro caso”

Si *secumplelacondición*:

           Haz esto...

En otro caso, si *secumpleestaotracondición*:

           Haz esto

En el caso de no cumplirse nada de lo anterior:

           Haz esto

Hay que decir varias cosas:

<li>
Puede haber tantos elif como queramos.
</li>
<li>
Las órdenes deben ir identadas o jerarquizadas, es decir, con una tabulación. En cualquier lenguaje, esto siempre se recomendaba para facilitar la lectura del programa pero Python lo exige porque no usa otra forma de agrupar órdenes. Es decir, todo lo que esté en el mismo nivel pertenece a un mismo bloque. Por eso, en Python es común ver la línea izquierda del texto de forma sinuante.
</li>
<li>
No te olvides de los dos puntos tras cada comparación o else.
</li>
