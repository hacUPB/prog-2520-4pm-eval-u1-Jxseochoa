# Ejercicio 4

Un almacén de ropa tiene una promoción: por compras superiores a $250 000 se les aplicará un descuento de 15%, de caso contrario, sólo se aplicará un 8% de descuento. Realice un algoritmo para determinar el precio final que debe pagar una persona por comprar en dicho almacén y de cuánto es el descuento que obtendrá. Represéntelo mediante el pseudocódigo y el diagrama de flujo.

## Análisis


| Variable de entrada       | Descripción                        |
|----------------|-------------------------------------|
| valor_compra   | Costo parcial de las prendas        |



| Variable de salida       | Descripción                  |
|----------------|-------------------------------|
| precio_final   | Valor que hay que pagar       |



| Constantes  | Descripción                                      |
|-------------|--------------------------------------------------|
| 250000      | Valor a partir del cual se da el descuento
| 15%, 8%     | Descuentos


## Pseudocódigo

```
Inicio
Leer valor_compra
Si valor_compra > 250000
    descuento = valor_compra * 0.15
Si no 
    descuento = valor_compra * 0.08
Fin Si
precio_final = valor_compra - descuento 
Mostrar "Valor a pagar: $", precio_final
Fin
```
## Diagrama de flujo
[Ejericio4pt1](diagrama4pt1.png)

[Ejercicio4pt2](diagrama4pt2.png)