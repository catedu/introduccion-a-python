
# Programa 10

**Descripción del problema:**

Se va a modificar el problema 8 pero usando una lista y recorriéndola sólo una vez. Es decir, deberemos encontrar una forma de pasar de la lista a una Cadena de caracteres. 

**Materia nueva:**

Una Cadena de caracteres es, sin lugar a dudas, una lista: Tiene un carácter inicial y el resto van ordenados. Es como una lista de caracteres.

Python, debido a lo mucho que se utilizan las Cadenas de caracteres, les ha reservado un tipo de variable especial, como hemos visto a lo largo del curso, y no nos hace trabajar todo el rato con listas para escribir algo, por suerte. Sin embargo, no las ha separado del todo y mantienen varias órdenes en común con las listas. Este programa está hecho sólo para sensibilizar sobre las Cadenas de caracteres y abrir una ventana en algo que se había dado como acotado.

A continuación, se va a presentar una orden referida a las Cadenas de caracteres, necesaria para solucionar el problema que tenemos entre manos, y aprovecharemos para practicar la lectura de la documentación de Python. Tal y como se puede leer  [https://docs.python.org/3.1/library/stdtypes.html#string-methods](https://docs.python.org/3.1/library/stdtypes.html#string-methods):  

**str.join** (**iterable**)

Return a string which is the concatenation of the strings in the **iterable**. A Type error will be raised if there are any non-string values in **seq**, including bytes objects. The separator between elements is the string providing this method.

Si se ha abierto el enlace, vemos que algunas de las palabras son enlaces que nos llevan a la página donde se explica lo que es. De momento, lo que con este curso se puede leer es poco pero haremos el intento y te pido que lo hagas con **.isdigit() **que también está en ese enlace.

Si traducimos casi literalmente: Devuelve una Cadena que es la concatenación de cadenas presentes en el "iterable" (quiere decir: A container object capable of returning its members one at a time. Un objeto contenedor capaz de devolver sus miembros de uno en uno). Se lanzará un error de tipo (ya vimos uno en los primeros programas antes de introducir **str()**) si no hay valores tipo Cadena en la secuencia, incluyendo Cadenas de bytes (fuera del alcance de este curso y novedad en Python 3.0). El separador entre elementos es la Cadena sobre la que se le aplica el método (lo primero que se pone antes del punto: **str**).

Lo que, traducido, viene a decir:

separador **.join(**cadenasaañadir**)** Esta orden junta las cadenas que tenga la variable **cadenasaañadir** separándolas con la cadena **separador**.

¿Qué puede ser **cadenasaañadir**? Como se ha visto, cualquier cosa que tenga cadenas, en nuestro caso será una lista pero hay muchas más posibilidades.



De momento, no hay que preocuparse porque la orden la he traducido y no se te va a pedir que uses ninguna otra sin explicarla. De todas formas, era necesario abrir el campo a un aprendizaje posterior, aunque quede sólo para los más osados ya que hay más posibilidades para aprender sin lidiar con semejante redacción, lo normal es que sólo aquellos que tengan un conocimiento avanzado se atrevan.

En los ejercicios de autoevaluación se seguirá trabajando con Cadenas de caracteres. Es un tema muy extenso y es muy necesario trabajarlo.

