# Ejercicio 6

Una tienda de ropa tiene la siguiente promoción: por la compra de tres productos, la prenda de menor valor tiene un 70% de descuento. Calcular cuál fue el descuento aplicado y cuánto tiene que pagar la persona.

## Pseudocódigo

```
Inicio
Leer producto1
Leer producto2
Leer producto3

 Si producto1 <= producto2 Y producto1 <= producto3
    menor = producto1
  Si no 
    producto2 <= producto1 Y producto2 <= producto3
    menor = producto2
  Si no
    menor = producto3
  Fin si

  descuento = menor * 0.70
  total_sin_descuento = producto1 + producto2 + producto3
  total_pagar = total_sin_descuento - descuento

  Escribir "Descuento aplicado: ", descuento
  Escribir "Total a pagar: ", total_pagar

  Fin
```


## Diagrama de flujo
[Ejercicio6pt1](diagrama6pt1.png)

[Ejercicio6pt2](diagrama6pt2.png)

[Ejercicio6pt3](diagrama6pt3.png)