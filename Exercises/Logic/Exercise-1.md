# Promociones

Un Instituto de Portugués decide lanzar las siguientes promociones buscando aumentar la cantidad de alumnos:

- Si se anotan 2 amigos, cada uno obtiene un 10% de descuento sobre el valor de la cuota; mientras que si se anotan 3 o más el descuento alcanza el 20%.
- Si al momento de pagar se decide abonar 2 meses juntos se recibe un descuento del 15%; en caso de cancelar 3 o más meses a la vez la reducción es del 25%.

Las promociones son combinables, pero nunca pueden superar el 35% de descuento. El valor original de la cuota mensual es de $650.  

La administración del Instituto nos   solicitó diseñar la función monto-persona, la cual recibe la cantidad de personas que se están anotando y la cantidad de meses que abonan (para que se aplique la promoción deben pagar la misma cantidad de meses), y devuelve el monto que el Instituto debe cobrarle a cada uno. Para desarrollar monto-persona es conveniente definir ciertas  constantes, ya que los precios pueden variar con el tiempo.

Ejemplos:
- Supogamos que Pedro y Juan deciden anotarse al curso de Portugués pagando 2 meses juntos, obtendrán un descuento del 25%, debiendo pagar $975 cada uno.
- Si Pedro y Juan también invitan a Paula y cancelan 3 meses juntos, recibirán una reducción del 35%, debiendo abonar $1267.50 cada uno.
- Si José se anota solo, pero paga 5 cuotas juntas, entonces deberá abonar $2437.5