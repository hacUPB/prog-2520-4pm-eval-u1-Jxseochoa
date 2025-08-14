# Ejercicio

**Control de temperatura del motor**:

- Durante una inspección de rutina, se mide la temperatura de un motor de turbina. Si la temperatura es mayor a un valor crítico, se debe indicar "Peligro: sobrecalentamiento". Si está dentro del rango seguro, indicar "Operación normal". Si es demasiado baja, indicar "Motor frío – Calentar antes de operar".

| Tipo                   | Nombre               | Descripción                                                                 |
|------------------------|----------------------|----------------------------------------------------------------------------|
| Variable de entrada    | temperatura_motor    | Temperatura medida del motor durante la inspección (°C)                    |
| Variable intermedia    | Ninguna              | No se realizan cálculos intermedios, solo comparaciones                    |
| Variable de salida     | estado_motor         | Mensaje que indica la condición del motor (Texto)                          |
| Constante              | temp_critica         | Límite superior de temperatura segura antes de sobrecalentamiento (°C)     |
| Constante              | temp_minima_segura   | Límite inferior de temperatura para operación segura (°C)                  |

## Pseudocódigo
```
Inicio
    temp_critica = 700
    temp_minima_segura = 200

    Leer temperatura_motor

    Si temperatura_motor > temp_critica Entonces
        estado_motor = "Peligro: sobrecalentamiento"
    Si no
        Si temperatura_motor >= temp_minima_segura Entonces
            estado_motor = "Operación normal"
        Si no
            estado_motor = "Motor frío – Calentar antes de operar"
        Fin Si
    Fin Si

    Mostrar estado_motor
Fin
```

    