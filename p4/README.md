Se implementaron dos tipos de analizadores sintácticos para una calculadora: uno basado en el algoritmo CYK y otro utilizando un enfoque predictivo descendente. Se realizaron pruebas con múltiples expresiones, tanto válidas como inválidas, con el objetivo de evaluar el comportamiento de cada parser y comparar sus resultados.

- Salida:
<img width="891" height="754" alt="image" src="https://github.com/user-attachments/assets/77c08760-6c76-47e4-87a7-829ba71c54d1" />

Al analizar los tiempos de ejecución, se observó que el parser predictivo es significativamente más rápido que el algoritmo CYK. Esto se debe a que el CYK tiene una complejidad cúbica O(n3), mientras que el parser predictivo opera en tiempo lineal O(n). Sin embargo, el algoritmo CYK es más general, ya que puede trabajar con cualquier gramática en forma normal de Chomsky.

La implementación y pruebas realizadas permiten concluir que ambos parsers cumplen correctamente su función al validar expresiones aritméticas. No obstante, el parser predictivo presenta un mejor rendimiento, mientras que el algoritmo CYK destaca por su generalidad. Esta comparación evidencia las ventajas y desventajas de cada enfoque en el análisis sintáctico.
