
# Ejercicios de autoevaluación

Felicidades por haber terminado el Módulo 1.

Ahora toca practicar lo aprendido con varios ejercicios que deben resolverse con lo aprendido. Se recomienda encarecidamente emplear tiempo en resolverlo en vez de ir a ver la solución directamente.



**1.- Realiza un programa donde se pida dos números y la operación a realizar (a elegir entre suma, resta, multiplicación y división). Posteriormente debe dar el resultado y preguntar si queremos hacer otra operación. Identificar si se quiere realizar una división por 0.**

Ten en cuenta que los operadores matemáticos simples son:" + " para la suma," - " para la resta," * " para la multiplicación y " / " para la división. En este programa se recomienda convertir el texto que devuelve **input **a un número tipo **float.**



**2.- Realiza un programa donde el usuario piense un número entre 1 y 100 y el ordenador, preguntando si es mayor o menor que otro, debe averiguarlo.**

Ten en cuenta que la mejor estrategia es preguntar cada vez por la mitad del rango disponible para eliminar la mayor cantidad posible de números:



 Primero preguntaré por 50 y, así elimino a 50 de golpe, una vez ahí, si es mayor, preguntaré por 75...

Información extra: El cociente de la división (o, lo que es lo mismo, el resultado entero de la división) se realiza mediante el operador "//" 

5//2 nos dará 2.

Sé muy cuidadoso a la hora de hacer el algoritmo y elegir las variables. Ten en cuenta que los límites superior e inferior deberán cambiar a lo largo de la ejecución del programa.

Este programa puede requerir el uso de una variable booleana. Se declara como sigue:

**variable=True** o, alternativamente:  **variable=False**



**3.- Realiza un programa donde se le pidan números al usuario hasta que introduzca 3 impares. Si son pares, seguirá pidiendo indefinidamente. Cada vez que se introduce un impar, el programa nos dice cuántas oportunidades nos quedan antes de terminar salvo al llegar a la tercera vez, debe decir que se termina el programa.**

En este caso, diferenciar si es par o impar lo podemos hacer con la operación que nos da el resto de una división. Su sintaxis es: **%**

4 **%** 2 = 0

5 **% **2 = 1

Se le llama módulo. Nada que ver con el módulo de un vector en matemáticas.

**4.- Realiza un programa donde pida números indefinidamente y pare cuando el número que se ha introducido sea menor a la suma de los dos anteriores.**

Es un problema donde te van a hacer falta variables que guarden esos números e ir actualizándolos cada vez que incluya uno. Va muy bien cara a practicar el diseño de algoritmos y a empezar a "leer" los programas, algo que se enseñará en el segundo módulo.





**** ****

****NOTA: Las soluciones no son únicas. Los programas que realices pueden ser igualmente correctos aunque sean más largos, usen más variables, etc. ****

**** ****

