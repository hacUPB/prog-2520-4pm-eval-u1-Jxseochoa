# Ejercicio 4.8 
Realice el algoritmo para determinar cuánto pagará una persona que adquiere N artículos, los cuales están de promoción. Considere que si su precio es mayor o igual a $200 se le aplica un descuento de 15%, y si su precio es mayor a $100 pero menor a $200, el descuento es de 12%; de lo contrario, solo se le aplica 10%. Se debe saber cuál es el costo y el descuento que tendrá cada uno de los artículos y finalmente cuánto se pagará por todos los artículos obtenidos. Represente la solución mediante el diagrama de flujo y el pseudocódigo.

## Pseudocódigo 
```

Inicio
Leer N
total_pagar = 0
descuento_total = 0

Para art = 1 Hasta N
  Leer precio

  Si precio >= 200
    tasa = 0.15
  Si no
    Si precio > 100 Y precio < 200
      tasa = 0.12
    Si no
      tasa = 0.10
    Fin Si
  Fin Si

  descuento = precio * tasa
  neto = precio - descuento

  descuento_total = descuento_total + descuento
  total_pagar = total_pagar + neto

  Mostrar "Artículo ", art, ": precio=", precio, " descuento=", descuento, " neto=", neto
Fin Para

Mostrar "DESCUENTO TOTAL = ", descuento_total
Mostrar "TOTAL A PAGAR = ", total_pagar
Fin

```

## Diagrama de flujo
[Ejercicio4.8pt1](diagrama48v1.png)

[Ejercicio4.8pt2](diagrama48v2.png) 

[Ejercicio4.8pt3](diagrama48v3.png)

[Ejercicio4.8pt4](diagrama48v3.png)
