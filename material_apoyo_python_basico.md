# 📘 Material de Apoyo — Python Básico 🐍

# Introducción

Python es un lenguaje de programación simple, legible y muy utilizado en:

- Desarrollo web
- Automatización
- Ciencia de datos
- Inteligencia artificial
- Ciberseguridad
- Desarrollo de scripts

Una de las ventajas de Python es que permite aprender programación de manera práctica y sencilla.

---

# ⚙️ Instalación y Primer Programa

## Ejecutar Python

Desde terminal:

```bash
python archivo.py
```

---

# 🖥️ Hola Mundo

El primer programa tradicional en cualquier lenguaje es mostrar un mensaje en pantalla.

## Sintaxis

```python
print("Hola mundo")
```

## Explicación

- `print()` permite mostrar información en pantalla.
- El texto entre comillas se conoce como string.

## Ejemplo

```python
print("Bienvenidos a Python")
print("Primera clase")
```

---

# 📦 Variables

Las variables permiten almacenar información.

## Ejemplo

```python
nombre = "Juan"
edad = 20
altura = 1.75
```

## Reglas básicas

- No usar espacios
- No comenzar con números
- Usar nombres descriptivos

✅ Correcto:

```python
nombre_usuario = "Ana"
```

❌ Incorrecto:

```python
1nombre = "Ana"
```

---

# 🔢 Tipos de Datos Numéricos

## Integer (`int`)

Números enteros.

```python
edad = 25
```

---

## Float (`float`)

Números decimales.

```python
altura = 1.80
```

---

# ➕ Operaciones Matemáticas

| Operación | Símbolo |
|---|---|
| Suma | `+` |
| Resta | `-` |
| Multiplicación | `*` |
| División | `/` |

## Ejemplo

```python
numero1 = 10
numero2 = 5

print(numero1 + numero2)
print(numero1 - numero2)
print(numero1 * numero2)
print(numero1 / numero2)
```

---

# 🔤 Strings (Cadenas de Texto)

Los strings representan texto.

## Ejemplo

```python
nombre = "Carlos"
ciudad = "Santiago"
```

---

# 🔗 Concatenación

Permite unir textos.

## Ejemplo

```python
nombre = "Ana"
apellido = "Pérez"

print(nombre + " " + apellido)
```

Resultado:

```text
Ana Pérez
```

---

# ⌨️ Entrada de Datos con input()

`input()` permite ingresar datos desde teclado.

## Ejemplo

```python
nombre = input("Ingrese su nombre: ")

print("Hola " + nombre)
```

---

# 🔄 Conversión de Datos

Los datos ingresados con `input()` son texto.

Para trabajar con números:

## int()

```python
edad = int(input("Ingrese su edad: "))
```

## float()

```python
altura = float(input("Ingrese su altura: "))
```

---

# 📋 Listas

Las listas almacenan múltiples elementos.

## Ejemplo

```python
frutas = ["manzana", "pera", "uva"]
```

## Acceder a elementos

```python
print(frutas[0])
```

---

# ➕ Agregar elementos a una lista

## append()

```python
frutas.append("sandía")
```

---

# 📦 Tuplas

Las tuplas son similares a las listas pero no pueden modificarse.

## Ejemplo

```python
coordenadas = (10, 20)
```

---

# 🗂️ Diccionarios

Permiten almacenar información usando clave y valor.

## Ejemplo

```python
persona = {
    "nombre": "Ana",
    "edad": 22,
    "ciudad": "Santiago"
}
```

## Acceder a valores

```python
print(persona["nombre"])
```

---

# 🏷️ Booleanos

Representan valores verdaderos o falsos.

## Valores

```python
True
False
```

---

# ⚖️ Operadores Relacionales

| Operador | Significado |
|---|---|
| `>` | Mayor que |
| `<` | Menor que |
| `==` | Igual |
| `!=` | Distinto |
| `>=` | Mayor o igual |
| `<=` | Menor o igual |

## Ejemplo

```python
edad = 20

print(edad >= 18)
```

Resultado:

```text
True
```

---

# 🔀 Condicionales

Los condicionales permiten tomar decisiones.

---

# if

## Sintaxis

```python
if condicion:
    instrucciones
```

## Ejemplo

```python
edad = 20

if edad >= 18:
    print("Mayor de edad")
```

---

# else

Se ejecuta cuando la condición no se cumple.

## Ejemplo

```python
edad = 15

if edad >= 18:
    print("Mayor de edad")
else:
    print("Menor de edad")
```

---

# elif

Permite evaluar múltiples condiciones.

## Ejemplo

```python
nota = 5.5

if nota >= 6:
    print("Excelente")
elif nota >= 4:
    print("Aprobado")
else:
    print("Reprobado")
```

---

# 🔁 Bucles

Los bucles permiten repetir instrucciones.

---

# while

## Sintaxis

```python
while condicion:
    instrucciones
```

## Ejemplo

```python
contador = 1

while contador <= 5:
    print(contador)
    contador += 1
```

---

# for

El bucle `for` se utiliza para recorrer elementos o repetir acciones.

## Ejemplo

```python
for numero in range(1, 6):
    print(numero)
```

---

# 🔢 range()

`range()` genera secuencias numéricas.

## Ejemplo

```python
range(1, 6)
```

Genera:

```text
1 2 3 4 5
```

---

# 🧠 Buenas Prácticas

## Usar nombres descriptivos

✅ Correcto:

```python
nombre_estudiante = "Ana"
```

❌ Incorrecto:

```python
x = "Ana"
```

---

## Mantener el código ordenado

Usar indentación correctamente.

✅ Correcto:

```python
if edad >= 18:
    print("Mayor de edad")
```

❌ Incorrecto:

```python
if edad >= 18:
print("Mayor de edad")
```

---

# 🛠️ Errores Comunes

## Olvidar comillas

❌ Incorrecto:

```python
print(Hola)
```

✅ Correcto:

```python
print("Hola")
```

---

## Error de indentación

Python depende de la indentación.

❌ Incorrecto:

```python
if True:
print("Hola")
```

✅ Correcto:

```python
if True:
    print("Hola")
```

---

# 🎯 Ejercicios Recomendados

- Información personal
- Calculadora básica
- Verificador de edad
- Lista de compras
- Tabla de multiplicar
- Sistema de notas
- Cajero automático
- Adivina el número
- Gestor de estudiantes

---

# 📚 Resumen del Curso

Durante este curso aprendimos:

✅ Variables  
✅ Tipos de datos  
✅ Strings  
✅ Input y Output  
✅ Operaciones matemáticas  
✅ Listas  
✅ Tuplas  
✅ Diccionarios  
✅ Condicionales  
✅ Bucles  

---

# 🚀 Próximos Temas Recomendados

Después de dominar estos conceptos puedes continuar con:

- Funciones
- Archivos
- Manejo de errores
- Módulos
- Programación orientada a objetos
- APIs
- Desarrollo web con Flask o Django

---

# 👨‍💻 Fin del Material de Apoyo

Practica constantemente, modifica ejemplos y experimenta con el código.
La mejor manera de aprender programación es escribiendo programas.

