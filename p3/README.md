## Gamatica ambigua
<img width="506" height="463" alt="image" src="https://github.com/user-attachments/assets/65829f09-9b36-4825-998b-bc5ea44f5962" />

Prueba de gramatica con entrada de texto
- Entrada: if E then if E then S else S
- Salida: <img width="1197" height="48" alt="image" src="https://github.com/user-attachments/assets/8aaee4c9-1294-4ee6-be6a-6c9aacfe3cee" />

La salida obtenida del parser muestra una posible interpretación de la cadena if E then if E then S else S, en la cual el else se asocia con el segundo if. 
Pero al esta no ser la única interpretación posible, ya que la gramática también permite asociar el else con el primer if. Esto implica que la misma cadena puede generar múltiples árboles sintácticos, lo que demuestra que la gramática es ambigua.

## Gramatica correcta
<img width="506" height="463" alt="image" src="https://github.com/user-attachments/assets/6199cee7-db9d-475e-9152-6547661d461d" />

- Entrada: if E then if E then S else S
- Salida: <img width="1408" height="56" alt="image" src="https://github.com/user-attachments/assets/42ce7d99-ae37-4aad-8516-2131634ca8ef" />

La salida obtenida muestra que la cadena es interpretada de manera única por la gramática corregida. En el árbol sintáctico se observa que el primer if es una estructura no emparejada, mientras que el segundo corresponde a una estructura emparejada con su respectivo else. Esto garantiza que el else se asocia con el if más cercano, eliminando la ambigüedad en la gramática original. Como resultado, cada cadena del lenguaje posee una única derivación posible.

