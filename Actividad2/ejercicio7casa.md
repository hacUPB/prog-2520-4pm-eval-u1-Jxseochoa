# Ejercicio 7

Elabore un algoritmo que solicite al usuario su fecha de nacimiento (día, mes y año) y la fecha actual (día, mes y año). El algoritmo deberá calcular y mostrar la edad actual del usuario en años completos, considerando si ya ha cumplido años en el año en curso o no.

## Pseudocódigo

```
Inicio
    Leer dia_nacimiento
    Leer mes_nacimiento
    Leer año_nacimiento

    Leer dia_actual
    Leer mes_actual
    Leer año_actual

    edad = año_actual - año_nacimiento

    Si (mes_actual = mes_nacimiento) Y (dia_actual = dia_nacimiento)
        Mostrar "La persona tiene ", edad, " años"
    Si no
        Si (mes_actual > mes_nacimiento) O (mes_actual = mes_nacimiento Y dia_actual > dia_nacimiento)
            Mostrar "La persona tiene ", edad, " años"
        Si no
            edad = edad - 1
            Mostrar "La persona tiene ", edad, " años"
        Fin Si
    Fin Si
Fin

```

## Diagrama de flujo
[Ejercicio7pt1](diagrama7pt1.png)

[Ejercicio7pt2](diagrama7pt2.png)

[Ejercicio7pt3](diagrama7pt3.png)

