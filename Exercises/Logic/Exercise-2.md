# Determinar condicion

Tomando como base los resultados obtenidos en un laboratorio de análisis clínicos, un médico determina si una persona tiene anemia o no, lo cual depende  de su nivel de hemoglobina en la sangre y de su edad. Si el nivel de hemoglobina  que tiene una persona es menor que el valor mínimo que le  corresponde de acuerdo a su edad, el resultado del análisis es "anemia positivo"  y en caso contrario es "anemia negativo".

El médico se basa en los siguientes valores mínimos para cada grupo de edades:
- edad <= 1 mes: nivel mínimo de hemoglobina normal 13 g/dl
- 1 mes < edad <= 6 meses: nivel mínimo de hemoglobina normal 10 g/dl
- 6 meses < edad <= 12 meses: nivel mínimo de hemoglobina normal 11 g/dl
- 1 año < edad <= 5 años: nivel mínimo de hemoglobina normal 11.5 g/dl
- 5 años < edad <= 10 años: nivel mínimo de hemoglobina normal 12.6 g/dl
- 10 años < edad: nivel mínimo de hemoglobina normal 13 g/dl

Diseñe una función anemia que recibiendo la edad de una persona expresada en  meses y la hemoglobina en sangre expresada en g/dl devuelva true si la persona  está anémica, false en caso contrario.