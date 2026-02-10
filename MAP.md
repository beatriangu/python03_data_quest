🧭 MAP.md — Python Garden · Data Quest (versión definitiva)
# 🧭 MAP.md — Python Garden · Data Quest
## python03_data_quest — Collections & Data Processing

Este documento es **MI mapa de aprendizaje y diseño**.
Explica cómo progresa mi razonamiento a lo largo del módulo y cómo cada
ejercicio añade una capa nueva al uso consciente de datos en Python.

No es una lista de ejercicios: es una **escalera mental**.
Acompaña al código como guía de comprensión, defensa y revisión.

---

## 🌱 Idea central del módulo

Pasar de:

❌ “tengo datos sueltos”  
a  
✅ “sé cómo representarlos, procesarlos y analizarlos”

**Clave del módulo:**  
👉 Elegir bien la **estructura de datos** importa más que el algoritmo.

---

## 🟢 ex0 — Command Quest

**Foco**  
→ Entrada de datos desde fuera del programa.

**Aprendo**
- `sys.argv`
- Diferencia entre:
  - nombre del script
  - argumentos del usuario
- Flujo de ejecución

**Clave mental**
👉 El programa no vive aislado.  
👉 El mundo exterior envía datos.

**Prepara para**
- Procesar datos reales
- Validar entradas

---

## 🟢 ex1 — Score Analytics

**Foco**  
→ Procesar datos secuenciales.

**Aprendo**
- Listas
- Acumulación de valores
- Estadísticas básicas
- `try / except`

**Clave mental**
👉 Los datos llegan en secuencia.  
👉 Las listas son el contenedor natural.

**Depende de**
- Entrada correcta (ex0)

**Prepara para**
- Análisis más estructurado

---

## 🟢 ex2 — Game Coordinate System

**Foco**  
→ Datos estructurados y fijos.

**Aprendo**
- Tuplas
- Inmutabilidad
- Tuple unpacking
- Cálculo matemático
- Validación de formato

**Clave mental**
👉 Algunos datos no deben cambiar.  
👉 La estructura comunica intención.



(x, y, z) → posición
no → lista genérica


**Depende de**
- Procesamiento básico (ex1)

**Prepara para**
- Datos con significado semántico

---

## 🟢 ex3 — Achievement Tracker

**Foco**  
→ Unicidad y análisis lógico.

**Aprendo**
- Sets
- Eliminación automática de duplicados
- Operaciones:
  - unión
  - intersección
  - diferencia

**Clave mental**
👉 No todo es contar.  
👉 A veces es comparar conjuntos.

**Prepara para**
- Analítica sin bucles complejos

---

## 🟢 ex4 — Inventory Master

**Foco**  
→ Relaciones complejas entre datos.

**Aprendo**
- Diccionarios
- Estructuras anidadas
- Clave → valor
- Modelado de dominio



Jugador
└── inventario
├── item
│ ├── cantidad
│ ├── rareza
│ └── valor


**Clave mental**
👉 Cuando hay relaciones → diccionario.  
👉 El dato tiene nombre.

**Depende de**
- Comprender colecciones simples

**Prepara para**
- Sistemas reales

---

## 🟢 ex5 — Data Stream

**Foco**  
→ Procesar datos sin cargarlos todos.

**Aprendo**
- Iteradores
- Generadores
- Procesamiento incremental
- Pensamiento streaming

**Clave mental**
👉 No todo cabe en memoria.  
👉 Se procesa mientras llega.

**Prepara para**
- Archivos, streams y pipelines

---

## 🟢 ex6 — Analytics Dashboard

**Foco**  
→ Expresión clara y potente.

**Aprendo**
- List comprehensions
- Dict comprehensions
- Set comprehensions
- Agregación
- Formato de salida

**Clave final**
👉 El código puede ser:
- corto
- legible
- expresivo  

sin perder claridad.

**Integra**
- Todo el módulo

---

## 🧠 Visión global



ex0 → entrada
ex1 → secuencia
ex2 → estructura
ex3 → unicidad
ex4 → relación
ex5 → streaming
ex6 → expresión


No son ejercicios aislados.  
Es **criterio para trabajar con datos**.

---

## 🎯 Objetivo final

Ser capaz de explicar:

- por qué usé esta estructura
- qué problema resuelve
- qué ocurriría con otra opción
- cómo escalaría el enfoque

Este MAP es **mi brújula del módulo** y refleja cómo pienso el
procesamiento de datos en Python.
