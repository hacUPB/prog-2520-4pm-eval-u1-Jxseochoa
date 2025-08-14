# Ejercicio 

**Registro de altitudes de vuelo**
    
    Un sistema debe registrar la altitud de vuelo cada 10 minutos durante una hora y mostrar todas las mediciones al final.

| Tipo                   | Nombre             | Descripción                                                    |
|------------------------|--------------------|----------------------------------------------------------------|
| Variable de entrada    | altitud            | Altitud de vuelo registrada en cada medición (pies)            |
| Variable intermedia    | contador           | Número de mediciones realizadas                                |
| Variable de salida     | lista_altitudes    | Lista con todas las altitudes registradas                      |
| Constante              | intervalo_medicion | Intervalo de tiempo entre mediciones (minutos)                 |
| Constante              | tiempo_total       | Duración total de la medición (minutos)                        |


## Pseudocódigo
```
Inicio
    intervalo_medicion = 10
    tiempo_total = 60
    i=0

    Mientras i <= (tiempo_total / intervalo_medicion) Hacer
        Leer altitud
        lista_altitudes[i]=altitud
        i = i + 1
    Fin Mientras

    Mostrar lista_altitudes
Fin
```