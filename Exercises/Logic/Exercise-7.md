# Casas en venta

Representaremos una casa con una estructura con los siguientes campos:

- 1er campo: propietario.
- 2do campo: dirección.
- 3er campo: superficie en metros cuadrados.
- 4to campo: zona.

Teniendo en cuenta esto se pide:

- Diseñe una estructura Casa que contenga los campos descriptos más arriba.
- Diseñe una función venta que tome como entrada un valor de tipo Casa y  devuelva un mensaje sobre los datos de la venta de dicha propiedad. Dicho   mensaje deberá dar los datos sobre el propietario que vende, en qué dirección se encuentra y el monto de dinero que recibe el propietario por dicha venta, luego  de realizados los descuentos correspondientes por el sellado de la escritura.  Para realizar los cálculos se deben tener en cuenta las siguientes cuestiones:

- Existen 4 zonas:
    - Zona A: el metro cuadrado en esta zona tiene un valor de 20000 pesos
    - Zona B: el metro cuadrado en esta zona tiene un valor de 15000 pesos
    - Zona C: el metro cuadrado en esta zona tiene un valor de 10000 pesos
    - Zona D: el metro cuadrado en esta zona tiene un valor de 5000 pesos

- El propietario debe pagar un sellado que se descontará del precio de la venta. Si el precio de la venta supera el millón de pesos el sellado tiene un costo del 5 % del valor y si no lo supera se debe abonar el 3% del valor de la propiedad.

Ejemplo:
- Supogamos que el señor José Romero vende una propiedad que se encuentra en la calle Rueda 3456. Dicha propiedad posee una superficie de 120 metros cuadrados  y, por la dirección en que se encuentra, pertenece a la zona C. El monto de  dinero que José recibe por dicha venta es de 1140000 pesos. Si aplicáramos la  función venta en este caso desearíamos que esta función nos devolviera el  siguiente mensaje: "El señor José Romero recibirá 1140000 pesos por la venta de su propiedad ubicada en la calle Rueda 3456."

En caso que la función venta reciba como entrada un dato que no sea de tipo Casa deberá mostrar el mensaje "Tipo de dato incorrecto".

En caso que la función venta reciba como entrada un dato de tipo Casa con una  zona distinta a A, B, C o D deberá mostrar el mensaje "No se puede calcular el  precio de venta por no disponer de los valores del metro cuadrado para la zona solicitada".