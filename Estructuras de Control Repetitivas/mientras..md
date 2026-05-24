# Ciclo Mientras en PSeInt

---

# 1. Introducción

```markdown
# Ciclo Mientras en PSeInt

El ciclo Mientras es una estructura repetitiva utilizada
para ejecutar un conjunto de instrucciones mientras una
condición lógica sea verdadera.

Esta estructura permite automatizar tareas repetitivas,
realizar validaciones y controlar procesos iterativos
dentro de un algoritmo.

En programación, los ciclos son fundamentales para
resolver problemas matemáticos, desarrollar software
interactivo y construir soluciones computacionales.

El ciclo Mientras evalúa primero una condición lógica.
Si la condición es verdadera, ejecuta las instrucciones.
Cuando la condición deja de cumplirse, el ciclo finaliza.
```

---

# 2. ¿Qué es un ciclo Mientras?

```markdown
## ¿Qué es un ciclo Mientras?

El ciclo Mientras es una estructura de control repetitiva
que ejecuta instrucciones múltiples veces dependiendo
del resultado de una condición lógica.

La condición debe ser verdadera para que el ciclo continúe
ejecutándose.

La estructura general funciona así:

1. Se inicializa una variable de control.
2. Se evalúa una condición.
3. Si la condición es verdadera:
   - se ejecutan las instrucciones,
   - se actualiza la variable de control.
4. El proceso vuelve a repetirse.
5. Cuando la condición es falsa, el ciclo termina.

Esta estructura es ampliamente utilizada en:

- Validación de datos
- Menús interactivos
- Operaciones matemáticas
- Juegos
- Automatización de procesos
- Simulaciones computacionales
```

---

# 3. Sintaxis

## Sintaxis del ciclo Mientras

```pseint
Mientras condicion Hacer

    instrucciones

FinMientras
```

## Operadores importantes

### Asignación

El operador "=" permite almacenar valores en variables.

```pseint
contador = 1
```

### Comparación

El operador "==" permite comparar valores.

```pseint
contador == 10
```

## Ejemplo básico

```pseint
Algoritmo EjemploMientras

    Definir contador Como Entero

    contador = 1

    Mientras contador <= 5 Hacer

        Escribir contador

        contador = contador + 1

    FinMientras

FinAlgoritmo
```

---

# 4. Diagrama general del ciclo Mientras

## Diagrama general

El ciclo Mientras sigue una estructura lógica repetitiva.

1. Inicialización
2. Evaluación de condición
3. Ejecución de instrucciones
4. Actualización de variable
5. Repetición

![Diagrama General](imagenes/diagrama_mientras_general.png)

---

# 5. Ejercicio Resuelto 1

# 5.1 Enunciado

# Ejercicio 1 - Contador del 1 al 10

## Enunciado

Realizar un algoritmo en PSeInt que muestre los números
del 1 al 10 utilizando un ciclo Mientras.

---

# 5.2 Análisis

## Análisis

El problema requiere repetir una instrucción varias veces.

Para controlar la repetición se utilizará:

- una variable contador,
- una condición lógica,
- un incremento progresivo.

El algoritmo debe:

1. Inicializar el contador en 1.
2. Mostrar el valor.
3. Incrementar el contador.
4. Repetir mientras el contador sea menor o igual a 10.

---

# 5.3 Variables

## Variables

| Variable | Tipo | Descripción |
|----------|----------|--------------|
| cont | Entero | Controla la repetición |

---

# 5.4 Código comentado


## Código comentado

```
Algoritmo Contador

    // Inicialización
    cont = 1

    // Ciclo repetitivo
    Mientras cont <= 10 Hacer

        // Mostrar número actual
        Escribir cont

        // Incrementar contador
        cont = cont + 1

    FinMientras

FinAlgoritmo
```


---

# 5.5 Diagrama de flujo


## Diagrama de flujo

![Diagrama de Flujo](imagenes/diagrama_mientras_ejercicio_1.png)


---

# 5.6 Explicación paso a paso


## Explicación paso a paso

### Paso 1
La variable cont inicia en 1.

### Paso 2
El ciclo evalúa la condición:

```pseint
cont <= 10
```

### Paso 3
Si la condición es verdadera, se muestra el valor actual.

### Paso 4
El contador aumenta en una unidad.

```pseint
cont = cont + 1
```

### Paso 5
El proceso se repite hasta que el cont sea mayor que 10.

---

# 5.7 Resultado esperado


## Resultado esperado

```txt
1
2
3
4
5
6
7
8
9
10
```
---

# 6. Ejercicio Resuelto 2

# 6.1 Enunciado

# Ejercicio 2 - Tabla de multiplicar

## Enunciado

Realizar un algoritmo en PSeInt que solicite un número al usuario y muestre su tabla de multiplicar del 1 al 10 utilizando un ciclo Mientras.

---

# 6.2 Análisis

## Análisis

El problema requiere repetir operaciones matemáticas varias veces.

Para resolverlo se utilizará:

- una variable para almacenar el número,
- una variable contador,
- una operación de multiplicación,
- un ciclo repetitivo.

El algoritmo debe:

1. Solicitar un número.
2. Inicializar el contador en 1.
3. Multiplicar el número por el contador.
4. Mostrar el resultado.
5. Incrementar el contador.
6. Repetir hasta llegar a 10.

---

# 6.3 Variables

## Variables

| Variable | Tipo | Descripción |
|----------|----------|--------------|
| n | Entero | Número ingresado |
| contador | Entero | Controla la repetición |
| resultado | Entero | Guarda la multiplicación |

---

# 6.4 Código comentado

## Código comentado

```pseint
Algoritmo TablaMultiplicar

    
    // Solicitar número
    Escribir "Ingrese un número"
    Leer n

    // Inicialización
    contador = 1

    // Ciclo repetitivo
    Mientras contador <= 10 Hacer

        // Multiplicación
        resultado = n * contador

        // Mostrar resultado
        Escribir n, " * ", contador, " = ", resultado

        // Incrementar contador
        contador = contador + 1

    FinMientras

FinAlgoritmo
```

---

# 6.5 Diagrama de flujo

## Diagrama de flujo

<!-- ![Diagrama de Flujo](imagenes/diagrama_mientras_ejercicio_2.png) -->
<img src="resources\images\diagrama_mientras_ejercicio_2.png" alt="Descripción" width="500">



---

# 6.6 Explicación paso a paso

## Explicación paso a paso

### Paso 1
El usuario ingresa un número.

### Paso 2
El contador inicia en 1.

### Paso 3
El ciclo evalúa la condición:

```pseint
contador <= 10
```

### Paso 4
Se calcula la multiplicación.

```pseint
resultado = numero * contador
```

### Paso 5
El contador aumenta en una unidad.

### Paso 6
El proceso se repite hasta llegar al 10.

---

# 6.7 Resultado esperado

## Resultado esperado

```txt
Ingrese un número
5

5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
```

---

# 7. Ejercicio Resuelto 3

# 7.1 Enunciado

# Ejercicio 3 - Suma acumulativa

## Enunciado

Realizar un algoritmo que permita sumar los números del 1 al 5 utilizando un ciclo Mientras.

---

# 7.2 Análisis

## Análisis

El algoritmo debe acumular valores progresivamente.

Se utilizará:

- una variable contador,
- una variable acumuladora,
- un ciclo repetitivo.

El algoritmo debe:

1. Inicializar contador.
2. Inicializar suma.
3. Sumar el contador.
4. Incrementar contador.
5. Repetir el proceso.

---

# 7.3 Variables

## Variables

| Variable | Tipo | Descripción |
|----------|----------|--------------|
| contador | Entero | Controla la repetición |
| suma | Entero | Acumula valores |

---

# 7.4 Código comentado

## Código comentado

```pseint
Algoritmo SumaAcumulativa

  
    // Inicialización
    contador = 1
    suma = 0

    // Ciclo repetitivo
    Mientras contador <= 5 Hacer

        // Acumular suma
        suma = suma + contador

        // Incrementar contador
        contador = contador + 1

    FinMientras

    // Mostrar resultado
    Escribir "La suma es: ", suma

FinAlgoritmo
```

---

# 7.5 Diagrama de flujo

## Diagrama de flujo

<!-- ![Diagrama de Flujo](imagenes/diagrama_mientras_ejercicio_3.png) -->
<img src="resources\images\diagrama_mientras_ejercicio_3.png" alt="Descripción" width="500">

---

# 7.6 Explicación paso a paso

## Explicación paso a paso

### Paso 1
Las variables se inicializan.

```pseint
contador = 1
suma = 0
```

### Paso 2
El ciclo evalúa la condición.

```pseint
contador <= 5
```

### Paso 3
Se acumula el valor actual.

```pseint
suma = suma + contador
```

### Paso 4
El contador aumenta.

### Paso 5
El ciclo termina cuando contador sea mayor que 5.

---

# 7.7 Resultado esperado

## Resultado esperado

```txt
La suma es: 15
```

---

# 8. Ejercicio Resuelto 4

# 8.1 Enunciado

# Ejercicio 4 - Validación de contraseña

## Enunciado

Realizar un algoritmo que solicite una contraseña hasta que el usuario ingrese la clave correcta.

---

# 8.2 Análisis

## Análisis

El problema requiere validar información repetidamente.

Se utilizará:

- una variable tipo cadena,
- una comparación,
- un ciclo Mientras.

El algoritmo debe:

1. Solicitar contraseña.
2. Comparar el valor ingresado.
3. Repetir mientras sea incorrecta.
4. Mostrar acceso permitido.

---

# 8.3 Variables

## Variables

| Variable | Tipo | Descripción |
|----------|----------|--------------|
| clave | Cadena | Guarda la contraseña |

---

# 8.4 Código comentado

## Código comentado

```pseint
Algoritmo ValidacionClave

    // Definición de variable
    Definir clave Como Cadena

    // Inicialización
    clave = ""

    // Validación repetitiva
    Mientras clave <> "1234" Hacer

        // Solicitar contraseña
        Escribir "Ingrese contraseña"
        Leer clave

    FinMientras

    // Acceso permitido
    Escribir "Acceso correcto"

FinAlgoritmo
```

---

# 8.5 Diagrama de flujo

## Diagrama de flujo

<!-- ![Diagrama de Flujo](imagenes/diagrama_mientras_ejercicio_2.png) -->
<img src="resources\images\diagrama_mientras_ejercicio_2.png" alt="Descripción" width="500">

---

# 8.6 Explicación paso a paso

## Explicación paso a paso

### Paso 1
La variable clave inicia vacía.

### Paso 2
El ciclo evalúa:

```pseint
clave <> "1234"
```

### Paso 3
Mientras la contraseña sea incorrecta, el sistema seguirá solicitándola.

### Paso 4
Cuando la clave sea correcta, el ciclo termina.

---

# 8.7 Resultado esperado

## Resultado esperado

```txt
Ingrese contraseña
1111

Ingrese contraseña
0000

Ingrese contraseña
1234

Acceso correcto
```

---

# 9. Ejercicio Resuelto 5

# 9.1 Enunciado

# Ejercicio 5 - Números pares

## Enunciado

Realizar un algoritmo que muestre los números pares del 2 al 20 utilizando un ciclo Mientras.

---

# 9.2 Análisis

## Análisis

El algoritmo debe mostrar únicamente números pares.

Se utilizará:

- una variable contador,
- incrementos de dos en dos,
- un ciclo repetitivo.

El algoritmo debe:

1. Inicializar contador en 2.
2. Mostrar el número.
3. Incrementar en 2.
4. Repetir hasta llegar a 20.

---

# 9.3 Variables

## Variables

| Variable | Tipo | Descripción |
|----------|----------|--------------|
| contador | Entero | Controla la repetición |

---

# 9.4 Código comentado

## Código comentado

```pseint
Algoritmo NumerosPares

    // Definición de variable
    Definir contador Como Entero

    // Inicialización
    contador = 2

    // Ciclo repetitivo
    Mientras contador <= 20 Hacer

        // Mostrar número par
        Escribir contador

        // Incrementar de dos en dos
        contador = contador + 2

    FinMientras

FinAlgoritmo
```

---

# 9.5 Diagrama de flujo

## Diagrama de flujo

<!-- ![Diagrama Pares](imagenes/numeros_pares.png) -->

---

# 9.6 Explicación paso a paso

## Explicación paso a paso

### Paso 1
El contador inicia en 2.

### Paso 2
El ciclo evalúa:

```pseint
contador <= 20
```

### Paso 3
Se muestra el número actual.

### Paso 4
El contador aumenta en 2.

```pseint
contador = contador + 2
```

### Paso 5
El proceso termina cuando el contador supera 20.

---

# 9.7 Resultado esperado

## Resultado esperado

```txt
2
4
6
8
10
12
14
16
18
20
```
