En este ejercicio representaremos una persona mediante una estructura con 5 campos:
- 1er campo: el nombre y apellido.
- 2do campo: el valor numérico de su peso.
- 3er campo: un string que representa la unidad en la cual está dado el peso   (valores posibles: "g" o "kg").
- 4to campo: el valor numérico de la estatura.
- 5to campo: un string que representa la unidad en la cual está dada la estatura (valores posibles: "m" o "cm").

Teniendo en cuenta esto se pide:

- Diseñe una estructura Persona que le permita representar a cualquier persona  con su peso y estatura.

- Diseñe una función IMC que tome como entrada un valor de tipo Persona y calcule su índice de masa corporal. En caso que no reciba como entrada una  estructura de tipo Persona deberá mostrar el siguiente mensaje de error: "Tipo de dato inválido".

Ayuda: Por si no lo sabe, el índice de masa corporal (IMC) de una persona se calcula según la siguiente fórmula:

```
IMC = PESO(Kg) / (ESTATURA (Mts))^2
```
Ayuda: Le puede servir conocer las siguientes equivalencias:

- 1 kg = 1000 g
- 1 m = 100 cm