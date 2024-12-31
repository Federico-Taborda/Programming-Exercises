# Costo de viaje

En este ejercicio representaremos un auto con una estructura con los siguientes  campos:

- 1er campo: Modelo.
- 2do campo: Año.
- 3to campo: Tipo de combustible (diesel o nafta).
- 4to campo: Rendimiento óptimo, expresado en kilómetros por litro. 

Teniendo en cuenta esto se pide que:

- Diseñe una estructura Auto que contenga los campos descriptos más arriba.
- Diseñe una función costo-viaje que tome como entrada un valor de tipo Auto y  un número de kilómetros a recorrer y calcule el costo del viaje. Para esto debe tener en cuenta: 

    - Cantidad de combustible: el número de litros necesarios para recorrer m kilómetros con un auto nuevo está determinado por su rendimiento óptimo. Sin  embargo, con el correr de los años, el rendimiento disminuye. Se estima que si el auto tiene:

        - Entre 1 y 5 años, el rendimiento disminuye 2%.
        - Entre 6 y 10 años, el rendimiento disminuye 6%.
        - Entre 10 y 15 años, el rendimiento disminuye 10%.
        - Más de 15 años, el rendimiento disminuye 15%.

        Es decir, si un auto 0km rinde 13km/litro, después de un año rendirá 12.74  km/litro, y después de 12 años 11,7 km/litro.

    - Peajes: por cada 100 kilómetros recorridos, se debe pagar un peaje de $50.
    - Precio combustible: el precio actual del litro de nafta es $19 y el litro  de diesel $17.

    Ejemplo: Un gol naftero 2016 de rendimiento óptimo 13km/litro, debido a sus  4 años de antigüedad tendrá un rendimiento de 12,74 km/litros. Por lo tanto,  recorrer 450 kms tendrá un costo de: (450 / 12,74) * $19 + $200