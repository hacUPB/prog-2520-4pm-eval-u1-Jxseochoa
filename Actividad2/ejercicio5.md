# Ejercicio 5 

El director de una escuela está organizando un viaje de estudios, y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar a la compañía de viajes por el servicio. La forma de cobrar es la siguiente: si son 100 alumnos o más, el costo por cada alumno es de $65.00; de 50 a 99 alumnos, el costo es de $70.00, de 30 a 49, de $95.00, y si son menos de 30, el costo de la renta del autobús es de $4000.00, sin importar el número de alumnos.

## Pseudocódigo

```
Inicio
Leer alumnos
Si alumnos >=100
    costo_alumno = 65
Si no
    Si alumnos = 65
Si no
    Si alumnos >= 50
        costo_alumno = 70
    Si no
        costo_alumno = 95
    Fin Si
Fin Si