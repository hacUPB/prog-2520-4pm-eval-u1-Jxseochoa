# Ejercicio 
**Simulación de conteo de pasajeros**
    
    Durante el abordaje, un sistema cuenta a los pasajeros que ingresan. Si el número total supera la capacidad máxima, el sistema debe detener el conteo y mostrar un mensaje de alerta.

Tipo                  | Nombre             | Descripción
----------------------|--------------------|------------------------------------------------------
Variable de entrada   | pasajeros_ingresan | Número de pasajeros que ingresan en una iteración
Variable intermedia   | pasajeros_totales  | Acumulador de pasajeros que han ingresado
Variable de salida    | mensaje_alerta     | Mensaje que indica si se superó la capacidad máxima
Constante             | capacidad_maxima   | Número máximo de pasajeros permitido

## Pseudocódigo

```
Inicio
 capacidad_maxima = 180 
 pasajeros_totales = 0
 i = 0

 
    Mientras pasajeros_totales < capacidad_maxima 
        pasajeros_totales + pasajeros_ingresan[i]
        i <- i + 1
    Fin Mientras
    