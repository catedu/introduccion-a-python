
# Programa 7

**Descripción del problema:**

Se va a modificar el programa 6 para saludar a más gente, primero preguntaremos cuánta gente hay e iremos saludando uno a uno comentando su edad como hasta ahora.

**Materia nueva:**

Cuando sabemos el número de veces que tenemos que hacer algo, aunque podríamos usar **while**, se usa otra estructura:

**For** significa en inglés “por”. Lo que quiere decir es “por cada uno”. Tiene muchas sintaxis aunque sólo daremos una de momento.

**for** nombredevariableentera **in range(** númeroinicial, númerofinal):

    Órdenes



Hay que decir que, si númeroinicial =0 no hace falta ponerlo y quedaría:

**for** nombredevariableentera** in range (**númerofinal**):

¡Atención! Python empieza en el número inicial, imaginemos **range (1,5).** Cuando a cualquier persona le resulta normal contar de uno a cinco de la siguiente manera:

1, 2, 3, 4, 5 

A Python no, resulta que él cuenta los números que ha puesto y dice: "No puede ser: 5-1=4. Debo hacerlo cuatro veces" y cuenta de esta manera:

1, 2, 3, 4

He empezado en el 1 por ser **range( **1,5**) **. Si hubiera sido **range** **(**4**)**:

0, 1, 2, 3

Como se ve, el último número no lo va a tocar. **Cuidado con esto ya que ocasiona la mayor parte de problemas en los programas**.

