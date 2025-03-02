# Proyecto Turborreactor
La idea del repositorio es contar como yo hice el turborreactor, quizás hayan mejores formas o quizás la forma en que lo hice es buena, pero soy malo compartiendo experiencias y no entiendan nada, anyways, nunca he sido el mejor comunicador.
## Índice
- [Primeras ideas](#Primeras-ideas)
- [Acerca del turbo GT1749S](#Acerca-del-turbo-GT1749S)
- [Análisis Ciclo Brayton](#Análisis-Ciclo-Brayton)
## Primeras ideas
La verdad es que no hice la turbina entera yo, si es que se le puede llamar así, reutilice el turbo de un auto, el GT1749S. Muchas razones hay para esto, pero la principal es que no se como manufacturar el diseño, en efecto, puedo hacer todos los calculos y simulaciones pero de nada sirve si no puedo hacerlo, otra razón es que se abaratan los costos, ya que fue un "aporte voluntario" (gracias papá) y tambien está la razón del tiempo, ya que se tienen componentes listos y solo faltaria diseñar lo que falta (camara de combustión). Siguiendo la idea, el nombre más apropiado para el preyecto debería ser "Modificación de turbo a turborreactor".<br/>
Bueno entonces ya sabemos que vamos a modificar un turbo y que se debe hacer la camara de combustión, por lo tanto primero es buscar las especificaciones de operación del turbo, hacer un par de supuestos, saber sus restricciones de operación, etc. Luego se analiza el ciclo Brayton y se podrá comenzar a diseñar la camara de combustión, ocupando para esto Inventor y ANSYS Fluent
## Acerca del turbo GT1749S
No hay mucha información disponible, o también puede ser que no busqué lo suficiente a fondo, pero lo mejor que pude encontrar fue [esto](https://www.repuestoexpress.co/turbo-gt1749s-hyundai-starex/), que es exactamente el modelo que tengo y nos entrega informacion jugosa:
- **Presión de Operación:** Hasta 2.2 bares
- **Velocidad Máxima:** Hasta 150,000 RPM
- **Temperatura de Operación:** Soporta temperaturas de escape de hasta 850°C
- **Potencia del Motor Soportada:** Compatible con motores de hasta 140 HP
- **Compatibilidad:** Sustituto directo para motores Hyundai Starex 2.5L, sin necesidad de adaptaciones adicionales.<br/>

Más adelante se verá para que sirven estos datos, pero por ahora solo se mencionan.
## Análisis Ciclo Brayton 
