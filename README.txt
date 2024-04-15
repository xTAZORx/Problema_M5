# Problema_M5
Lee el documento txt y adjunta, en código Java, la solución al enunciado

Jaimito es un gran aficionado de Moto GP y su ídolo es Valentino Rossi, a quien considera el mejor piloto de la historia. Sin embargo, Jaimito también es un poco rencoroso, ya que aún no ha superado el hecho de que Marc Márquez le fastidiase el décimo mundial a su ídolo aún sin opciones de ganarlo él. Por ello, Jaimito quiere escribir un programa para calcular cuántas veces se ha caído Márquez en una temporada, y así aliviar su rencor viendo a su enemigo morder el polvo (Y nunca mejor dicho)!

Para ello, Jaimito ha recopilado una serie de números del 0 al 9, donde cada número representa las caídas en un gran premio (desde los entrenamientos hasta la carrera). Sin embargo, Jaimito es un poco despistado y a veces escribe cosas que no tienen sentido. Necesitamos ayudarlo a calcular el total de caídas de Márquez en una temporada, asegurándonos de manejar cualquier error que pueda surgir.

Necesitamos un programa en Java que cumpla las siguientes condiciones:

Entrada: Una cadena (String) que representa la temporada de Moto GP de Marc Márquez. Cada carácter en el string es un número del 0 al 9 o la letra "A". Cada número representa las caídas en un gran premio y la letra "A" representa ausencia en un gran premio y no suma caídas. No puede haber más de 20 grandes premios. Hay que manejar las excepciones con mensajes de error.
Ej:
0200451203020104AAAa
12345670j
000000000000000000000000
Salida: El total de caídas de Marc Márquez en la temporada.
ej:
24
Jaimito, has introducido un valor no válido!
Jaimito, la temporada no puede tener más de 20 grandes premios!

Restricciones:
Si algún carácter no es un número del 0 al 9 ni la letra "A", mostrar un mensaje de error indicando que se ha introducido un valor no válido en la temporada.
No puede haber más de 20 caracteres en la cadena, ya que como máximo hay 20 grandes premios.
