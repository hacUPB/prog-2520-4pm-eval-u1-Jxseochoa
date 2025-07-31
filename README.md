[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/rEzvQPOM)
# Repositorio Unidad \#
## Información del estudiante
Nombre:  Jose David Ochoa Chica 
ID.:  000567707
## Descripción del repositorio
Este repositorio documenta y desarrolla la Actividad 1: Representación de Datos en el Mundo Digital, cuyo objetivo principal es comprender cómo las computadoras almacenan, procesan y representan información utilizando el sistema binario. La actividad abarca conceptos fundamentales como la conversión entre sistemas numéricos (binario, decimal, hexadecimal), el manejo de datos en lenguajes de programación como Python y la codificación de distintos tipos de archivos digitales, como imágenes.

A través de ejercicios teóricos y prácticos, se busca que el estudiante no solo entienda la base numérica que sustenta la computación moderna, sino que también sea capaz de aplicarla en contextos reales como el procesamiento de imágenes o la gestión de memoria. Este repositorio sirve como evidencia de aprendizaje y referencia para futuras actividades relacionadas con la arquitectura y funcionamiento de los sistemas digitales.

Durante la clase del dia 29 de Julio, se trataron varios aspectos, entre los cuales surgieron las siguiente preguntas cada una con su respectiva respuesta:

1. **¿Por qué es necesario que las computadoras representen los datos en binario?**

- Las computadoras representan los datos en binario porque están construidas con circuitos electrónicos que solo pueden tener dos estados: encendido (1) y apagado (0), correspondientes a la presencia o ausencia de voltaje. Esta limitación técnica hace que el sistema binario (base 2) sea ideal para almacenar y procesar información. Además, el binario es más simple, confiable y eficiente para los circuitos digitales. Todos los tipos de datos, texto, imágenes, sonido, números pueden codificarse como combinaciones de unos y ceros.

2. **Conversión del número binario 10011011 a decimal y hexadecimal**: 
**Binario: 10011011**

- Decimal:

Para convertir a decimal, multiplicamos cada bit por 2 elevado a su posición (empezando desde la derecha con la posición 0):

1×2⁷ + 0×2⁶ + 0×2⁵ + 1×2⁴ + 1×2³ + 0×2² + 1×2¹ + 1×2⁰  
= 128 + 0 + 0 + 16 + 8 + 0 + 2 + 1  
= **155**

- Hexadecimal:

El sistema hexadecimal es de base 16, lo que significa que cada dígito hexadecimal representa un número entre 0 y 15.

Si ya tienes el binario de un número, puedes agruparlo en bloques de 4 bits (de derecha a izquierda) y convertir cada grupo a su valor hexadecimal.


Binario de 155: 10011011

Agrupamos de 4 en 4: 1001 1011

Convertimos:

1001 = 9

1011 = B

 **Resultado hexadecimal: 9B**

 
 ## **Ejercicio colocado en clase para realizar**

En una carpeta hay **3 archivos**, los cuales tienen las siguientes especificaciones:

**1.** Un archivo de texto de **52794 caracteres**

**2.** Un archivo en el cual ha **76931 datos enteros**

**3.** Un archivo el cual tiene **105230** de **punto flotante**.

Se debe determinar cuantos **bytes** tiene cada archivo.

**SOLUCIÓN**

1. Un carácter  ocupa 1 byte. Por tanto, el archivo tiene 52794 **bytes**.

2. Un entero suele ocupar **4 bytes**. Por tanto debemos **multiplicar** la cantidad dada **por 4**. 

- 76,931 enteros × 4 bytes = **307,724 bytes**

3. Un número de punto flotante suele ocupar **4 bytes**. Entonces realizamos el mismo procedimiento que el anterior.

- 105,230 floats × 4 bytes = **420,920 bytes**

Para saber cuantos bytes tiene la carpeta en total, solo debemos sumar las cantidades:

52,794 +  307,724  + 420,920  
= **781,438 bytes**

Esa sería la cantidad de bytes que tiene la carpeta.


Esas serían las respuestas al ejercicio propuesto en clase.


