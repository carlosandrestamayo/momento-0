# 🧠 Plan de Mejoramiento en Programación

## 🎯 Propósito

Este taller tiene como finalidad fortalecer el pensamiento computacional y las bases del razonamiento algorítmico en estudiantes que presentan dificultades en la prueba diagnóstica inicial (Momento 0).

Se desarrolla como una estrategia de mejoramiento académico que permite preparar al estudiante para una evaluación final.

## 🧠 📘 MÓDULO 1: PENSAMIENTO LÓGICO Y ALGORÍTMICO

---

## 🎯 Objetivo
Comprender cómo estructurar soluciones a problemas mediante algoritmos, identificando claramente **entrada, proceso y salida**.

---

## 📖 🔑 Conceptos clave

### 🔹 Lenguaje de programación
Es un conjunto de reglas y símbolos que permiten escribir instrucciones para que una computadora realice tareas específicas.

---

### 🔹 Ejemplos de lenguajes de programación

- Python  
- Java  
- C++  
- JavaScript  

---

### 🔹 No son lenguajes de programación

- Excel  
- Windows  
- Google Chrome  
- Word  

---

## 🧩 Ejemplo

Un programa en Python:

```text
print("Hola mundo")
```
---

### 🔹 Algoritmo
Es un conjunto de **pasos ordenados, finitos y lógicos** que permiten resolver un problema.

---

### 🔹 Estructura de un algoritmo

Todo algoritmo se compone de:

- **Entrada:** Datos que se reciben  
- **Proceso:** Operaciones que se realizan  
- **Salida:** Resultado obtenido  

---

### 🔹 Secuencia
Las instrucciones deben ejecutarse en **orden**, ya que cambiar el orden puede alterar el resultado.

---

### 🔹 Prueba de escritorio
Es una técnica que consiste en **simular paso a paso la ejecución del algoritmo** para verificar su correcto funcionamiento.

---

## 🧩 Ejemplo resuelto 1

### 📌 Problema
Convertir horas a minutos.

---

### 🔍 Análisis

- **Entrada:** horas  
- **Proceso:** horas × 60  
- **Salida:** minutos  

---

### 💻 Seudocódigo

```text
Leer horas
minutos ← horas * 60
Escribir minutos
```

---

## 🧠 Prueba de escritorio

Si horas = 3:

| Variable | Valor |
|----------|------|
| horas    | 3    |
| minutos  | 180  |

✔ **Salida:** 180

---

## 🧩 Ejemplo resuelto 2

### 📌 Problema
Calcular el doble de un número y luego sumarle 5.

---

### 🔍 Análisis

- **Entrada:** número  

- **Proceso:**
  - Multiplicar por 2  
  - Sumar 5  

- **Salida:** resultado  

---

### 💻 Seudocódigo

```text
Leer num
doble ← num * 2
resultado ← doble + 5
Escribir resultado
```

---

## 🧠 Prueba de escritorio

Si num = `4`:

| Variable  | Valor |
|-----------|------|
| num       | 4    |
| doble     | 8    |
| resultado | 13   |

✔ **Salida:** 13

---

## ⚠️ Observaciones importantes

- El orden de las operaciones es fundamental  
- Cada paso debe ser claro y sin ambigüedad  
- Las variables deben representar correctamente el problema  
- Siempre se debe poder verificar con prueba de escritorio  

---

## 🔢 📘 MÓDULO 2: TIPOS DE DATOS Y VARIABLES

---

## 🎯 Objetivo
Comprender los diferentes tipos de datos y el uso de variables para almacenar información dentro de un algoritmo.

---

## 📖 🔑 Conceptos clave

### 🔹 Variable
Es un espacio en memoria que permite **almacenar un dato** que puede cambiar durante la ejecución del programa.

---

### 🔹 Tipos de datos

#### 🟢 Entero (int)
Representa números sin decimales  
Ejemplo: `1`, `25`, `-10`  

---

#### 🔵 Decimal (float)
Representa números con decimales  
Ejemplo: `3.5`, `2.75`, `-0.8`  

---

#### 🟡 Cadena (string)
Representa texto  
Ejemplo: `"Hola"`, `"Carlos"`  

---

#### 🔴 Booleano (boolean)
Representa valores lógicos  
Ejemplo: `true`, `false`  

---

### 🔹 Asignación
Es el proceso de **guardar un valor en una variable**.

Ejemplo:
```text
edad ← 20
nombre ← "Ana"
```
---

## 🔹 Reglas para nombrar variables

- Deben iniciar con letra  
- No deben tener espacios  
- No deben usar símbolos especiales  
- No deben ser palabras reservadas  

✔ **Ejemplos válidos:**

- edad  
- nombre1  
- total_notas  

❌ **Ejemplos inválidos:**

- mi nombre  
- %edad  
- 1numero  

---

## 🧩 Ejemplo resuelto 1

### 📌 Problema
Almacenar la edad y mostrarla.

---

### 🔍 Análisis

- **Entrada:** edad  
- **Proceso:** almacenar valor  
- **Salida:** mostrar edad  

---

### 💻 Seudocódigo

```text
Leer edad
Escribir edad

```
---

## 🧠 Prueba de escritorio

Si edad = 18:

| Variable| Valor |
| :---    | :---  |
| edad    | 18    |


✔ **Salida:** 18

---

## 🧩 Ejemplo resuelto 2
### 📌 Problema

Calcular el promedio de dos notas decimales.

---

### 🔍 Análisis


- **Entrada:** nota1, nota2
- **Proceso:** (nota1 + nota2) / 2
- **Salida:** promedio

---

💻 Seudocódigo

```text
Leer nota1, nota2
promedio ← (nota1 + nota2) / 2
Escribir promedio
```

## 🧠 Prueba de escritorio

Si nota1 = 4.0 y nota2 = 3.0:

|Variable|Valor|
|:---    |:--- |
|nota1   | 4.0 |
|nota2   | 3.0 |
|promedio| 3.5 |

✔ **Salida:** 3.5

---

## ⚠️ Observaciones importantes

- El tipo de dato debe corresponder al valor que se almacena
- Usar nombres de variables claros mejora la comprensión
- Cuidado con operaciones entre enteros y decimales
- Los textos deben ir entre comillas

----

## ➕ 📘 MÓDULO 3: OPERADORES

---

## 🎯 Objetivo
Comprender el uso de los operadores aritméticos, relacionales y lógicos, así como la jerarquía de operaciones en la resolución de problemas.

---

## 📖 🔑 Conceptos clave

### 🔹 Operadores aritméticos
Permiten realizar operaciones matemáticas.

| Operador | Descripción | Ejemplo |
|----------|------------|--------|
| +        | Suma       | 5 + 3 = 8 |
| -        | Resta      | 5 - 3 = 2 |
| *        | Multiplicación | 5 * 3 = 15 |
| /        | División   | 6 / 2 = 3 |
| %        | Módulo (residuo) | 5 % 2 = 1 |

---

### 🔹 Operadores relacionales
Comparan valores y devuelven verdadero o falso.

| Operador | Significado | Ejemplo |
|----------|------------|--------|
| >        | Mayor que  | 5 > 3 → true |
| <        | Menor que  | 5 < 3 → false |
| ==       | Igual      | 5 == 5 → true |
| !=       | Diferente  | 5 != 3 → true |
| >=       | Mayor o igual | 5 >= 5 → true |
| <=       | Menor o igual | 3 <= 5 → true |

---

### 🔹 Operadores lógicos
Permiten combinar condiciones.

| Operador | Descripción | Ejemplo |
|----------|------------|--------|
| AND      | Y lógico   | true AND false → false |
| OR       | O lógico   | true OR false → true |
| NOT      | Negación   | NOT true → false |

---

### 🔹 Jerarquía de operaciones

Orden en que se resuelven las expresiones:

1. Paréntesis ( )
2. Multiplicación y división
3. Suma y resta

---

## 🧩 Ejemplo resuelto 1

### 📌 Problema
Calcular el valor de la expresión: 5 + 3 * 2

---

### 🔍 Análisis

- Se aplica jerarquía de operaciones  
- Primero multiplicación, luego suma  

---

### 💻 Desarrollo

```text
3 * 2 = 6
5 + 6 = 11
```
---

## 🧠 Prueba de escritorio

|Paso	   |Resultado |
| :---:  |  :---:   |
|3 * 2   |	6       |
|5 + 6	 |    11    | 

✔ **Salida:** 11

## 🧩 Ejemplo resuelto 2
### 📌 Problema

Evaluar la expresión lógica: `(5 > 3) AND (2 < 1)`

### 🔍 Análisis

- `5 > 3 → true`

- `2 < 1 → false`

- `true AND false → false`

###  💻 Desarrollo

```text
(5 > 3) = true
(2 < 1) = false
true AND false = false
```
---

## 🧠 Prueba de escritorio

|Expresión      |Resultado |
| ---           | ---      |
|5 > 3          | true     |
|2 < 1          |false     |
|true AND false |false     |


✔ **Salida:** false

---

## ⚠️ Observaciones importantes

- Respetar la jerarquía de operaciones evita errores
- No confundir `=` (asignación) con `==` (comparación)
- Las expresiones lógicas siempre devuelven `true (verdadero)` o `false (falso)`
- El operador módulo `%` es útil para determinar pares e impares

---

## 🔷 📘 MÓDULO 4: DIAGRAMAS DE FLUJO

---

## 🎯 Objetivo
Comprender la representación gráfica de algoritmos mediante diagramas de flujo, identificando correctamente sus símbolos y su secuencia lógica.

---

## 📖 🔑 Conceptos clave

### 🔹 Diagrama de flujo
Es una representación gráfica de un algoritmo mediante símbolos conectados por flechas que indican la secuencia de ejecución.

---

### 🔹 Importancia
- Facilita la comprensión de los algoritmos  
- Permite visualizar el proceso paso a paso  
- Ayuda a detectar errores antes de programar  

---

## 🔷 Símbolos básicos

| Símbolo        | Nombre            | Función |
|----------------|------------------|--------|
| Óvalo          | Inicio / Fin     | Indica el inicio o final del algoritmo |
| Rectángulo     | Proceso          | Representa operaciones o cálculos |
| Paralelogramo  | Entrada / Salida | Leer o mostrar datos |
| Flecha         | Flujo            | Indica la dirección del proceso |

---

## 🧩 Ejemplo resuelto 1

### 📌 Problema
Convertir horas a minutos.

---

### 🔍 Análisis

- **Entrada:** horas  
- **Proceso:** horas × 60  
- **Salida:** minutos  

---

### 🔷 Diagrama (descripción)

<img src="resources/images/diagrama_horas_minutos
.png" alt="Descripción" width="500">

![Texto descriptivo](resources/images/diagrama_horas_minutos
.png)
**Poner imagen**
1. Inicio  
2. Leer horas  
3. minutos ← horas * 60  
4. Escribir minutos  
5. Fin  

---

### 💻 Seudocódigo

```text
Leer horas
minutos ← horas * 60
Escribir minutos
```
---

## 🧠 Prueba de escritorio

Si horas = 2:

|Variable	| Valor |
| :---:   | :---: |
|horas	  | 2     |
|minutos	| 120   |

✔ **Salida:** 120

### 🧩 Ejemplo resuelto 2
## 📌 Problema

Calcular el promedio de dos notas.

---

### 🔍 Análisis

- **Entrada:** nota1, nota2
- **Proceso:** (nota1 + nota2) / 2
- **Salida:** promedio

---

### 🔷 Diagrama (descripción)

1. Inicio
2. Leer nota1, nota2
3. promedio ← (nota1 + nota2) / 2
4. Escribir promedio
5. Fin

---

### 💻 Seudocódigo

```text
Leer nota1, nota2
promedio ← (nota1 + nota2) / 2
Escribir promedio
```
---
🧠 Prueba de escritorio

Si nota1 = 4.0 y nota2 = 3.0:

|Variable	|Valor|
|:---:|:---:|
|nota1	|4.0|
|nota2	|3.0|
|promedio	|3.5|

✔ **Salida:** 3.5

---

## ⚠️ Observaciones importantes

- Todo diagrama debe tener inicio y fin
- Las flechas deben indicar correctamente la secuencia
- Cada símbolo debe usarse según su función
- El diagrama debe ser claro y ordenado

---
