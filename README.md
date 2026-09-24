# ============================================
# 🎓 ACTIVIDAD 8 - USO Y CREACIÓN DE UNA CLASE EN C++
# ============================================

# --------------------------------------------
# 📋 DESCRIPCIÓN
# --------------------------------------------
# En esta actividad se explica cómo crear y usar una clase
# en C++. Una clase es una plantilla que define las
# características (atributos) y comportamientos (métodos)
# que tendrán los objetos creados a partir de ella.


# ============================================
# 🏗️ ¿QUÉ ES UNA CLASE?
# ============================================
# Una clase es como un "molde" o "plantilla" que sirve para
# crear objetos. Define:
#
#   🔹 ATRIBUTOS: Son las características o datos que
#      describen al objeto (ej: nombre, edad, carrera).
#
#   🔹 MÉTODOS: Son las acciones o comportamientos que
#      puede realizar el objeto (ej: mostrar información).
#
# Ejemplo: La clase "Estudiante" es el molde, y cada
# estudiante específico (Ana, Luis, etc.) es un objeto.


# ============================================
# 🧱 PARTES DE UNA CLASE
# ============================================

# 1️⃣ ATRIBUTOS (Variables de la clase)
# --------------------------------------------
# Son las características del objeto. Se declaran dentro
# de la clase y normalmente son privados (private) para
# proteger los datos.
#
# En nuestro caso:
#   - nombre (string)
#   - edad (int)
#   - carrera (string)


# 2️⃣ CONSTRUCTOR
# --------------------------------------------
# Es un método especial que se ejecuta automáticamente
# cuando se crea un objeto de la clase. Sirve para
# inicializar los atributos.
#
# Recibe los valores iniciales y los asigna a los
# atributos del objeto.


# 3️⃣ MÉTODOS (Funciones de la clase)
# --------------------------------------------
# Son las acciones que puede realizar el objeto.
# Normalmente son públicos (public) para que puedan
# usarse desde fuera de la clase.
#
# En nuestro caso:
#   - getNombre()   → devuelve el nombre
#   - getEdad()     → devuelve la edad
#   - getCarrera()  → devuelve la carrera
#   - mostrarInfo() → muestra toda la información


# 4️⃣ ENCAPSULAMIENTO
# --------------------------------------------
# Es un principio de la POO que consiste en proteger los
# datos. Los atributos se ponen como "private" y se
# accede a ellos mediante métodos "public" (getters y
# setters).
#
# Esto evita que los datos se modifiquen directamente
# desde fuera de la clase.


# ============================================
# 🔄 FLUJO DEL PROGRAMA
# ============================================

# PASO 1: Se declara la clase "Estudiante"
#         con sus atributos y métodos.

# PASO 2: En la función main(), se piden al usuario
#         los datos (edad, nombre, carrera).

# PASO 3: Se crea un OBJETO de la clase Estudiante,
#         pasándole los datos al constructor.

# PASO 4: Se llama al método mostrarInfo() del objeto
#         para que imprima la información en pantalla.


# ============================================
# 💻 EJEMPLO DE SALIDA
# ============================================
# Introduce tu edad:
# 21
# Introduce tu nombre:
# Ana
# Introduce tu carrera:
# Ingenieria Informatica
#
# Bienvenido! Ana
# Edad: 21
# Carrera: Ingenieria Informatica


# ============================================
# 🧠 CONCEPTOS APRENDIDOS
# ============================================
# - ¿Qué es una clase y para qué sirve?
# - Diferencia entre clase y objeto
# - Uso de atributos (private)
# - Uso de métodos (public)
# - Uso de constructor
# - Uso de getters
# - Encapsulamiento
# - Creación de objetos
# - Programación Orientada a Objetos (POO)
# - Entrada y salida de datos (cin y cout)
# - Variables tipo int y string
# - Inclusión de bibliotecas (iostream, string)


# ============================================
# 🎯 VENTAJAS DE USAR CLASES
# ============================================
# ✅ Código más organizado
# ✅ Reutilización de código
# ✅ Fácil mantenimiento
# ✅ Protección de datos (encapsulamiento)
# ✅ Modela mejor objetos del mundo real
# ✅ Base para herencia y polimorfismo


# ============================================
# 📁 ESTRUCTURA DEL PROYECTO
# ============================================
# registro-estudiante/
# ├── main.cpp
# ├── README.md
# └── LICENSE


# ============================================
# 🚀 POSIBLES MEJORAS
# ============================================
# [ ] Validación de entrada
# [ ] Registro de múltiples estudiantes
# [ ] Guardar datos en archivo
# [ ] Interfaz más amigable
# [ ] Más campos (matrícula, semestre, etc.)
# [ ] Herencia y polimorfismo
# [ ] Setters para modificar datos


# ============================================
# 📄 LICENCIA
# ============================================
# MIT License
