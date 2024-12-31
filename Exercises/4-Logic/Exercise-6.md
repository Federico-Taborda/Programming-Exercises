# Condicion de asignatura

En este ejercicio representaremos un Alumno con una estructura con los siguientes
campos:

- 1er campo: Nombre del alumno.
- 2do campo: Promedio de sus calificaciones (un valor entre 0 y 10).
- 3er campo: Porcentaje de asistencia a clases (un valor entre 0 y 100).

Teniendo en cuenta esto se pide:

- Diseñe una estructura Alumno que contenga los campos descriptos más arriba.
- Diseñe una función condicion que tome como entrada un valor de tipo Alumno y  devuelva un string indicando su condición. Condiciones posibles: "Libre",  "Regular" y "Promovido".

Para calcular la condición del alumno deben tenerse en cuenta las siguientes   reglas:
- Si el alumno tiene un porcentaje de inasistencia mayor al 40% queda automáticamente libre, sin importar el promedio de sus calificaciones.

- Si el alumno tiene una asistencia mayor o igual al 60%:
    - y tiene una nota inferior a 6, también se considera libre.
    - y tiene una nota mayor o igual a 6 y menor estricta que 8, se considera regular.
    - y una nota mayor o igual a 8, se considera promovido.

En caso en que la función condicion reciba como entrada un dato que no  corresponda a una estructura Alumno deberá responder con un mensaje de error  (como por ejemplo: "Tipo de dato inválido").