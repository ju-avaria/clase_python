# Curso Básico de Python 🐍

Bienvenido a este repositorio de introducción a Python.  
Durante esta semana aprenderemos los fundamentos de programación utilizando ejemplos simples y ejercicios prácticos.

El objetivo es **aprender haciendo**: escribir código, probar ideas y resolver pequeños problemas paso a paso.

---

# 📚 Contenidos del Curso

1. Hola Mundo
2. Tipos de datos numéricos
3. Tipo de datos cadena
4. Lista, tupla y diccionario
5. Categorización de valores
6. Tipos de datos compuestos
7. Condicionales
8. Bucles

---

# ⚙️ Requisitos

- Tener instalado Python 3
- Editor recomendado:
  - VS Code
  - PyCharm
  - Thonny

## Ejecutar programas desde terminal

```bash
python archivo.py
```

---

# 🚀 1. Hola Mundo

## 🎯 Qué aprenderemos

- Qué es Python
- Cómo ejecutar un programa
- Cómo mostrar mensajes en pantalla
- Uso básico de `print()`

## 📌 Ejemplo

```python
print("Hola mundo")
print("Bienvenidos a Python")
```

## 🛠️ Actividades

- Crear un programa que muestre tu nombre
- Mostrar tu edad
- Mostrar tu ciudad

## ✅ Resultado esperado

Aprender a ejecutar programas simples y entender la estructura básica de un script en Python.

---

# 🔢 2. Tipos de datos numéricos

## 🎯 Qué aprenderemos

- Variables
- Enteros (`int`)
- Decimales (`float`)
- Operaciones matemáticas

## 📌 Ejemplo

```python
edad = 20
altura = 1.75

print(edad)
print(altura)

suma = 10 + 5
multiplicacion = 4 * 3

print(suma)
print(multiplicacion)
```

## 🛠️ Actividades

- Crear dos variables numéricas
- Realizar:
  - suma
  - resta
  - multiplicación
  - división
- Calcular el promedio de 3 números

## ✅ Resultado esperado

Comprender cómo almacenar y utilizar valores numéricos en Python.

---

# 🔤 3. Tipo de datos cadena

## 🎯 Qué aprenderemos

- Uso de texto (`string`)
- Concatenación
- Entrada de datos con `input()`

## 📌 Ejemplo

```python
nombre = "Juan"
apellido = "Pérez"

print(nombre + " " + apellido)
```

## 📌 Ejemplo con input

```python
nombre = input("Ingrese su nombre: ")

print("Hola " + nombre)
```

## 🛠️ Actividades

- Pedir nombre y apellido al usuario
- Mostrar un saludo personalizado
- Crear una frase usando varias variables

## ✅ Resultado esperado

Aprender a trabajar con texto e interactuar con el usuario.

---

# 📦 4. Lista, tupla y diccionario

## 🎯 Qué aprenderemos

- Colecciones de datos
- Diferencias básicas entre:
  - listas
  - tuplas
  - diccionarios

---

## 📌 Listas

```python
frutas = ["manzana", "pera", "uva"]

print(frutas)
print(frutas[0])
```

### 🛠️ Actividades

- Crear una lista de colores
- Mostrar el primer y último elemento
- Agregar un nuevo elemento

---

## 📌 Tuplas

```python
coordenadas = (10, 20)

print(coordenadas)
```

### 🛠️ Actividades

- Crear una tupla con datos personales
- Mostrar cada valor

---

## 📌 Diccionarios

```python
persona = {
    "nombre": "Ana",
    "edad": 22,
    "ciudad": "Santiago"
}

print(persona["nombre"])
```

### 🛠️ Actividades

- Crear un diccionario con información de un estudiante
- Mostrar cada dato

## ✅ Resultado esperado

Comprender cómo almacenar múltiples datos de distintas formas.

---

# 🏷️ 5. Categorización de valores

## 🎯 Qué aprenderemos

- Comparaciones
- Valores booleanos (`True` y `False`)
- Operadores relacionales

## 📌 Ejemplo

```python
edad = 18

print(edad >= 18)
```

## 📌 Operadores

| Operador | Significado |
|---|---|
| `>` | Mayor que |
| `<` | Menor que |
| `==` | Igual |
| `!=` | Distinto |
| `>=` | Mayor o igual |
| `<=` | Menor o igual |

## 🛠️ Actividades

- Verificar si un número es positivo
- Verificar si una persona es mayor de edad
- Comparar dos números

## ✅ Resultado esperado

Entender cómo Python evalúa condiciones y comparaciones.

---

# 🔗 6. Tipos de datos compuestos

## 🎯 Qué aprenderemos

- Combinar distintos tipos de datos
- Uso de listas con números y texto
- Estructuras simples de datos

## 📌 Ejemplo

```python
producto = {
    "nombre": "Teclado",
    "precio": 15000,
    "stock": True
}

print(producto)
```

## 🛠️ Actividades

- Crear un diccionario de productos
- Crear una lista de estudiantes
- Guardar información mezclando texto y números

## ✅ Resultado esperado

Aprender a organizar información de forma más realista.

---

# 🔀 7. Condicionales

## 🎯 Qué aprenderemos

- Uso de `if`
- Uso de `else`
- Uso de `elif`

## 📌 Ejemplo

```python
edad = 20

if edad >= 18:
    print("Mayor de edad")
else:
    print("Menor de edad")
```

## 📌 Ejemplo con múltiples condiciones

```python
nota = 5.5

if nota >= 6:
    print("Excelente")
elif nota >= 4:
    print("Aprobado")
else:
    print("Reprobado")
```

## 🛠️ Actividades

- Verificar si un número es par o impar
- Crear un sistema simple de notas
- Determinar si una persona puede votar

## ✅ Resultado esperado

Tomar decisiones en programas utilizando condiciones.

---

# 🔁 8. Bucles

## 🎯 Qué aprenderemos

- Repetición de instrucciones
- Uso de `while`
- Uso de `for`

---

## 📌 While

```python
contador = 1

while contador <= 5:
    print(contador)
    contador += 1
```

---

## 📌 For

```python
for numero in range(1, 6):
    print(numero)
```

## 🛠️ Actividades

- Mostrar números del 1 al 10
- Mostrar tablas de multiplicar
- Contar vocales en una palabra
- Sumar números ingresados por el usuario

## ✅ Resultado esperado

Automatizar tareas repetitivas usando ciclos.

---

# 🎯 Proyecto Final Sugerido

Crear un programa que:

- Solicite datos al usuario
- Use variables
- Utilice listas o diccionarios
- Tome decisiones con `if`
- Use un bucle

## 📌 Ideas

- Registro de estudiantes
- Calculadora básica
- Sistema de notas
- Lista de compras

---

# 📖 Recomendaciones

- Practicar todos los días
- Ejecutar el código varias veces
- Modificar ejemplos para experimentar
- Leer los errores y tratar de entenderlos

---

# 🧠 Meta del Curso

Al finalizar esta semana podrás:

✅ Crear programas básicos en Python  
✅ Utilizar variables y estructuras de datos  
✅ Trabajar con condiciones y bucles  
✅ Resolver problemas simples mediante programación  

---

Repositorio creado para clases prácticas de introducción a Python.
