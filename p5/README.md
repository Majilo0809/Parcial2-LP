Se diseñó e implementó un parser descendente recursivo basado en el algoritmo de emparejamiento de tokens. La gramática definida permite representar operaciones de asignación y estructuras condicionales tipo if/then/else, incorporando además expresiones con operadores relacionales como mayor que, menor que e igualdad.
La implementación se realizó mediante funciones recursivas que representan cada regla de la gramática, junto con una función de emparejamiento (match) encargada de validar la secuencia de tokens de entrada. Este enfoque permite simular el proceso de análisis sintáctico descendente de forma directa y estructurada.

Para validar el funcionamiento del parser, se realizaron múltiples pruebas utilizando diferentes tipos de entradas, incluyendo casos válidos e inválidos. Entre las pruebas se incluyeron asignaciones simples, condicionales con operadores relacionales y estructuras incompletas o incorrectas.

<img width="949" height="438" alt="image" src="https://github.com/user-attachments/assets/a02ba167-ec7b-4852-8529-9285427516a8" />

El análisis de los resultados permite observar que el parser es adecuado para el reconocimiento de la gramatica usada en este ejercicio. Su estructura basada en funciones facilita la comprensión y la implementación de las reglas gramaticales

La implementación de estructuras condicionales permite evaluar expresiones lógicas antes de ejecutar una acción específica. En este caso, se incorporaron operadores relacionales como mayor que (>), menor que (<) e igualdad (==), lo que permite construir condiciones.
El parser evalúa primero la condición y dependiendo de su validez sintáctica, procede a analizar las sentencias correspondientes al bloque then y else, garantizando así la correcta estructura
