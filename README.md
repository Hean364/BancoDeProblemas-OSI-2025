# BancoDeProblemas-OSI-2025

¡Bienvenidos al **Banco de Problemas** de la **Olimpiada de Informática de El Salvador**! Este repositorio está diseñado exclusivamente para los organizadores del evento y diseñadores de problemas, facilitando la creación, gestión y almacenamiento de los problemas que se presentarán durante la OSI o futuras competiciones.

## 📋 Objetivos

- Mantener todos los problemas en un solo lugar para facilitar su acceso y gestión.
- Asegurar que cada problema cumpla con los estándares de calidad y formato establecidos.
- Facilitar la colaboración entre los organizadores para la creación y revisión de problemas.
- Restringir el acceso únicamente a los organizadores para mantener la integridad de los problemas hasta el día de la competición.

## 🗂️ Estructura del Repositorio

```
BancoDeProblemas-OSI-2025/
├── problemas/
│   ├── problema-01/
│   │   ├── enunciado.md
│   │   ├── input.txt
│   │   ├── output.txt
│   │   └── soluciones/
│   │       ├── solucion.cpp
│   │       └── solucion.py
│   ├── problema-02/
│   │   ├── enunciado.md
│   │   ├── input.txt
│   │   ├── output.txt
│   │   └── soluciones/
│   │       ├── solucion.cpp
│   │       └── solucion.py
│   └── ...
├── README.md
├── CONTRIBUTING.md
```

### **Descripción de Carpetas y Archivos:**

- **problemas/**: Carpeta principal que contiene subcarpetas para cada problema.
  - **problema-XX/**: Subcarpeta para cada problema, donde `XX` es el número del problema.
    - `enunciado.md`: Descripción detallada del problema en formato Markdown.
    - `input.txt`: Datos de entrada de ejemplo.
    - `output.txt`: Salida esperada correspondiente al `input.txt`.
    - **soluciones/**: Carpeta que contiene las soluciones oficiales en diferentes lenguajes de programación.
      - `solucion.cpp`: Solución en C++.
      - `solucion.py`: Solución en Python.
- **README.md**: Descripción general del repositorio.
- **CONTRIBUTING.md**: Guía para los organizadores sobre cómo contribuir al repositorio.

## 📜 Reglas y Directrices

### 1. **Formato de los Enunciados:**

Cada enunciado debe seguir una estructura consistente para facilitar su comprensión y evaluación:

- **Título del Problema**
- **Descripción Detallada**
- **Formato de Entrada**
- **Formato de Salida**
- **Restricciones**
- **Ejemplos de Entrada y Salida**
- **Notas Adicionales** (si aplica)

### 2. **Creación y Gestión de Problemas:**

- Los problemas deben numerarse secuencialmente (`problema-01`, `problema-02`, etc.) para mantener un orden lógico.
- Solo los organizadores deben agregar las soluciones oficiales en la carpeta `soluciones/`.
- Antes de finalizar un problema, debe ser revisado y validado por al menos otro organizador para asegurar su calidad y corrección.

### 3. **Control de Acceso:**

- El repositorio debe ser **privado**. Solo los organizadores autorizados deben tener acceso.
- Asignar roles adecuados a los miembros del equipo (por ejemplo, administradores, colaboradores) para gestionar quién puede modificar el contenido.
- Está estrictamente prohibido compartir el contenido del repositorio con personas no autorizadas hasta el anuncio oficial de los problemas.

### 4. **Uso de Archivos de Input y Output:**

- Asegurarse de que los archivos `input.txt` y `output.txt` sigan un formato consistente para facilitar las pruebas automáticas.
- Cada problema debe tener múltiples casos de prueba para cubrir diferentes escenarios y asegurar la robustez de las soluciones.

### 5. **Evitar Divulgación de Soluciones:**

- Las soluciones oficiales deben mantenerse confidenciales hasta después de la competición.
- Los miembros deben evitar agregar soluciones a ramas que puedan ser visibles accidentalmente antes del tiempo.

### 6. **Reportar Problemas:**

- Utilizar la sección de **Issues** del repositorio para reportar errores, inconsistencias o sugerir mejoras en los problemas existentes.
- Utilizar etiquetas específicas (por ejemplo, `bug`, `mejora`, `consulta`) para organizar y priorizar los issues.
## 🧩 Áreas a Evaluar

Los problemas de la Olimpiada de Informática de El Salvador están categorizados en diferentes áreas temáticas y distribuidos en dos fases.

### **Áreas de Evaluación:**

- **Greedy**
- **Programación Dinámica (DP)**
- **Matemáticas**
- **Divide and Conquer**
- **Range Queries**
- **Estructuras de Datos Básicas** (pilas, colas, vectores, matrices)
- **Ad Hoc**
- **Complete Search**
- **Binary Search**
- **Combinatoria**
- **Floodfill**
- **Strings**

### **Distribución por Fases:**

#### **Fase 1:**
- Greedy
- Matemáticas
- Divide and Conquer
- Estructuras de Datos Básicas (pilas, colas, vectores, matrices)
- Complete Search
- Floodfill

#### **Fase 2:**
- Binary Search
- Programación Dinámica (DP)
- Range Queries
- Strings
- Combinatoria
- Ad Hoc

## 📬 Contacto

Si tienes preguntas, sugerencias o necesitas asistencia, por favor contacta a los mantenedores del repositorio o abre un **Issue** privado.

¡Gracias por tu colaboración y dedicación para hacer de la Olimpiada de Informática de El Salvador un éxito!
