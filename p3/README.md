
Prueba de gramatica con entrada de texto
- entrada: if E then if E then S else S
- salida: <img width="1197" height="48" alt="image" src="https://github.com/user-attachments/assets/8aaee4c9-1294-4ee6-be6a-6c9aacfe3cee" />

La salida obtenida del parser muestra una posible interpretación de la cadena if E then if E then S else S, en la cual el else se asocia con el segundo if. 
Pero al esta no ser la única interpretación posible, ya que la gramática también permite asociar el else con el primer if. Esto implica que la misma cadena puede generar múltiples árboles sintácticos, lo que demuestra que la gramática es ambigua.

## Gramatica correcta

<img width="506" height="463" alt="image" src="https://github.com/user-attachments/assets/6199cee7-db9d-475e-9152-6547661d461d" />


