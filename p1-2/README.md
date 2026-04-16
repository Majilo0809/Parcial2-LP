## Gramatica

<img width="444" height="814" alt="image" src="https://github.com/user-attachments/assets/f34dbd2c-7144-4e66-94f7-4e3c967291bd" />

- Compilacion y ejecucion
  - antlr4 CRUD.4
  - javac *.java
  - Java Main

La gramática define un lenguaje CRUD para bases de datos NoSQL, 
permitiendo múltiples sentencias mediante la regla programa.

Cada operación (CREATE, READ, UPDATE, DELETE) sigue una estructura uniforme 
que incluye una colección y objetos tipo JSON.

Estos objetos están formados por pares clave-valor, lo que permite 
representar documentos de manera flexible.

Además, se definen tokens para identificar cadenas, números e identificadores, 
garantizando un análisis léxico adecuado.


## PRUEBAS
- Prueba con entrada incorrecta

- prueba de error en archivo test.txt 
  <img width="511" height="201" alt="image" src="https://github.com/user-attachments/assets/858fcab9-80e4-4c9f-9e8f-14d40f51ff65" />

- salida:
<img width="801" height="59" alt="image" src="https://github.com/user-attachments/assets/898cebaf-2b90-412a-b60c-293a5c7cbb3b" />

Con esto se evidencia que el programa lee correctamente las instrucciones cuando están bien formadas y genera errores cuando la sintaxis no es válida (cancelando toda la ejecucion), cumpliendo así con el comportamiento esperado del analizador.

por otro lado se probo con una sintaxis correcta

- Archivo text.txt
<img width="488" height="104" alt="image" src="https://github.com/user-attachments/assets/1d1c457d-3cb8-476c-9eaf-9b174443e4d0" />

- Salida
  <img width="791" height="123" alt="image" src="https://github.com/user-attachments/assets/ba6af6bb-8499-4ac3-9a3f-446f8ba58dce" />

Se realizaron pruebas con entradas válidas, obteniendo como resultado la correcta ejecución de cada una de las operaciones CRUD. El sistema reconoce las instrucciones, mostrando mensajes en consola que confirman la operación realizada 
