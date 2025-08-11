# Ejercicio 5 

El director de una escuela está organizando un viaje de estudios, y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar a la compañía de viajes por el servicio. La forma de cobrar es la siguiente: si son 100 alumnos o más, el costo por cada alumno es de $65.00; de 50 a 99 alumnos, el costo es de $70.00, de 30 a 49, de $95.00, y si son menos de 30, el costo de la renta del autobús es de $4000.00, sin importar el número de alumnos.

## Pseudocódigo
```
Inicio
    Leer alumnos
    Si alumnos >= 100
        costo_alumno = 65
        total_pagar = alumnos * costo_alumno
    Si no
        Si alumnos >= 50
            costo_alumno = 70
            total_pagar = alumnos * costo_alumno
        Si no
            Si alumnos >= 30
                costo_alumno = 95
                total_pagar = alumnos * costo_alumno
            Si no
                costo_alumno = 4000 / alumnos
                total_pagar = 4000
            Fin Si
        Fin Si
    Fin Si

    Mostrar "Costo por alumno: ", costo_alumno
    Mostrar "Total a pagar a la compañía: ", total_pagar
Fin
```
## Diagrama de flujo
[Ejercicio5](diagrama5.png)

