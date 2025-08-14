## **Actividad 1** 

Durante la clase del dia 29 de Julio, se trataron varios aspectos, entre los cuales surgieron las siguiente preguntas cada una con su respectiva respuesta:

## **Ejercicios 1.1**
### Ejercicios

1. Convierte el número decimal 22 a binario.
2. ¿Cuál es el resultado en decimal del número binario 10110?
3. Escribe un programa en Python que convierta un número decimal introducido por el usuario a binario.

### Desarrollo 
**1. Convierte el número decimal 22 a binario**

Para convertir 22 a binario, dividimos entre 2 sucesivamente y anotamos los residuos:
22 ÷ 2 = 11, residuo 0  
11 ÷ 2 = 5,  residuo 1  
5  ÷ 2 = 2,  residuo 1  
2  ÷ 2 = 1,  residuo 0  
1  ÷ 2 = 0,  residuo 1  
Ahora leemos los residuos de abajo hacia arriba:
22 = 10110 en binario


**2. ¿Cuál es el resultado en decimal del número binario 10110?**

Descomponemos el número binario:

1×2⁴ + 0×2³ + 1×2² + 1×2¹ + 0×2⁰  
= 16 + 0 + 4 + 2 + 0  
= 22

Resultado: 22 en decimal

**3. Programa en Python para convertir un número decimal a binario
python**

**"# Programa para convertir un número decimal a binario"**

**"# Solicita al usuario un número"**

decimal = int(input("Introduce un número decimal: "))

**"# Convierte a binario usando la función bin() y elimina el prefijo '0b'"**

binario = bin(decimal)[2:]

**"# Muestra el resultado"**

print("El número en binario es:", binario)


# Ejercicios 1.2

1. ¿Qué número binario representa el carácter 'C' en ASCII?
2. Convierte el número flotante 5.75 a binario (explica los pasos).


### Desarrollo 
**1. ¿Qué número binario representa el carácter 'C' en ASCII?**

Primero, buscamos el valor ASCII del carácter 'C'.

'C' → ASCII decimal: 67

Ahora convertimos 67 a binario:

67 ÷ 2 = 33, residuo 1  
33 ÷ 2 = 16, residuo 1  
16 ÷ 2 = 8,  residuo 0  
8  ÷ 2 = 4,  residuo 0  
4  ÷ 2 = 2,  residuo 0  
2  ÷ 2 = 1,  residuo 0  
1  ÷ 2 = 0,  residuo 1


**2. Convierte el número flotante 5.75 a binario (explica los pasos)**

Un número flotante tiene parte entera y parte fraccionaria, que convertimos por separado.

**Paso 1: Parte entera (5)**

5 ÷ 2 = 2, residuo 1  
2 ÷ 2 = 1, residuo 0  
1 ÷ 2 = 0, residuo 1  
→ 5 = 101 en binario

**Paso 2: Parte fraccionaria (0.75)**

Multiplicamos por 2 y anotamos la parte entera de cada resultado:

0.75 × 2 = 1.5 → entero: 1  
0.5 × 2  = 1.0 → entero: 1  
0.0 → terminamos
→ 0.75 = .11 en binario

**Paso 3: Juntar todo**

5.75 = 101 + .11 = 101.11

Entonces, 5.75 en binario es 101.11

# Ejercicios 1.3

1. Convierte el número decimal 255 a hexadecimal.
2. ¿Cuál es el valor hexadecimal de la secuencia binaria 11010110?

### Desarrollo 

**1. Convierte el número decimal 255 a hexadecimal.**

Convierte el número decimal 255 a hexadecimal
Dividimos sucesivamente entre 16:

255 ÷ 16 = 15, residuo 15 → 15 = F
15 ÷ 16 = 0, residuo 15 → 15 = F

Leyendo los residuos de abajo hacia arriba:
255 en hexadecimal = FF

Resultado: 255₁₀ = FF₁₆

**2. ¿Cuál es el valor hexadecimal de la secuencia binaria 11010110?**

Agrupamos los bits en bloques de 4 (de derecha a izquierda):

11010110 → 1101 0110 = (13) 6 (6)

Usamos la tabla de conversión:

1101 = 13 = D

0110 = 6 = 6

Resultado: 11010110₂ = D6₁₆


# Ejercicios 1.4

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


**3. ¿Cómo se representa una imagen en formato PNG en el disco?**

El formato PNG (Portable Network Graphics) es un formato de imagen comprimido sin pérdida. Está diseñado para reemplazar al GIF, soportando transparencia y una mayor profundidad de color. Veamos cómo está estructurado:

🧱 Estructura general de un archivo PNG
Firma PNG (8 bytes):

Cada archivo PNG empieza con estos 8 bytes fijos:

**89 50 4E 47 0D 0A 1A 0A**

Esto sirve para identificar el archivo como PNG.

**Chunks (bloques de datos):**

Un archivo PNG contiene bloques (chunks) que almacenan diferentes tipos de información. Cada chunk tiene:

**Longitud** (4 bytes)

**Tipo** (4 bytes) — por ejemplo IHDR, IDAT, IEND

**Datos** (variable)

**CRC** (4 bytes) — verificación de integridad

**Los más importantes:**

**IHDR (Header):** contiene ancho, alto, profundidad de color, tipo de color, compresión, filtro, etc.

**PLTE (opcional):** paleta de colores (si es una imagen indexada).

**IDAT (Image Data):** datos de la imagen comprimidos (usualmente con zlib/deflate).

**IEND:** marca el final del archivo.

**4. ¿Qué sucede si intentas almacenar un número mayor al que puede representar un byte (por ejemplo, 300)? ¿Cómo lo maneja Python?**

 Un byte puede almacenar valores entre 0 y 255 (8 bits = 2⁸ = 256 valores).
Entonces, el número 300 no cabe en un byte, y eso genera un error si se fuerza.

**Ejemplo con 300**

 "# Intento de crear un byte con valor 300
b = bytes([300])"

ValueError: bytes must be in range(0, 256)

¿Cómo maneja Python los enteros grandes?

Python no tiene límite fijo para enteros (int puede crecer hasta donde permita la memoria).

Pero al convertir un entero a bytes, tú debes especificar cuántos bytes usar y qué hacer con valores mayores:

n = 300

"# Convertir a 2 bytes en formato big-endian"

b = n.to_bytes(2, byteorder='big')
print(b)  # b'\x01,,'  → 300 = 0x012C

**Python te obliga a manejar el número según el número de bytes disponibles. Puedes evitar el error ajustando la cantidad de bytes necesarios o validando previamente.**

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

