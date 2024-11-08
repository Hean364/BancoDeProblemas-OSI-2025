# BancoDeProblemas-OSI-2025

¡Bienvenidos al **Banco de Problemas** de la **Olimpiada de Informática de El Salvador**! Este repositorio está diseñado exclusivamente para los organizadores del evento y diseñadores de problemas, facilitando la creación, gestión y almacenamiento de los problemas que se presentarán durante la OSI o futuras competiciones.

## 📋 Objetivos

- **Centralización de Problemas:** Mantener todos los problemas en un solo lugar para facilitar su acceso y gestión.
- **Calidad y Consistencia:** Asegurar que cada problema cumpla con los estándares de calidad y formato establecidos.
- **Colaboración Eficiente:** Facilitar la colaboración entre los organizadores para la creación y revisión de problemas.
- **Seguridad y Privacidad:** Restringir el acceso únicamente a los organizadores para mantener la integridad de los problemas hasta el día de la competición.

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
- **CODE_OF_CONDUCT.md**: Código de conducta para mantener un ambiente colaborativo y respetuoso.
- **LICENSE**: Información sobre la licencia del repositorio.
- **.gitignore**: Archivos y carpetas que Git debe ignorar.

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

Ejemplo de `enunciado.md`:

```markdown
# Título del Problema

## Descripción

Descripción detallada del problema, incluyendo el contexto y lo que se espera que los participantes resuelvan.

## Formato de Entrada

Descripción de cómo se presentará la entrada al programa.

## Formato de Salida

Descripción de cómo debe ser la salida del programa.

## Restricciones

- Restricción 1
- Restricción 2
- ...

## Ejemplos

**Entrada:**
```
3 4
```

**Salida:**
```
7
```

## Notas

Cualquier información adicional que pueda ser útil para resolver el problema.
```

### 2. **Creación y Gestión de Problemas:**

- **Asignación de Números:** Los problemas deben numerarse secuencialmente (`problema-01`, `problema-02`, etc.) para mantener un orden lógico.
- **Soluciones Oficiales:** Solo los organizadores deben agregar las soluciones oficiales en la carpeta `soluciones/`.
- **Revisión y Validación:** Antes de finalizar un problema, debe ser revisado y validado por al menos otro organizador para asegurar su calidad y corrección.

### 3. **Control de Acceso:**

- **Privacidad del Repositorio:** El repositorio debe ser **privado**. Solo los organizadores autorizados deben tener acceso.
- **Roles y Permisos:** Asignar roles adecuados a los miembros del equipo (por ejemplo, administradores, colaboradores) para gestionar quién puede modificar el contenido.
- **No Compartir Externamente:** Está estrictamente prohibido compartir el contenido del repositorio con personas no autorizadas hasta el anuncio oficial de los problemas.

### 4. **Uso de Archivos de Input y Output:**

- **Consistencia en Formatos:** Asegurarse de que los archivos `input.txt` y `output.txt` sigan un formato consistente para facilitar las pruebas automáticas.
- **Pruebas Exhaustivas:** Cada problema debe tener múltiples casos de prueba para cubrir diferentes escenarios y asegurar la robustez de las soluciones.

### 5. **Evitar Divulgación de Soluciones:**

- **Protección de Soluciones:** Las soluciones oficiales deben mantenerse confidenciales hasta después de la competición.
- **Restricciones en los Commits:** Los miembros deben evitar agregar soluciones a ramas que puedan ser visibles accidentalmente antes del tiempo.

### 6. **Reportar Problemas:**

- **Uso de Issues Internos:** Utilizar la sección de **Issues** del repositorio para reportar errores, inconsistencias o sugerir mejoras en los problemas existentes.
- **Etiquetado Adecuado:** Utilizar etiquetas específicas (por ejemplo, `bug`, `mejora`, `consulta`) para organizar y priorizar los issues.

## 🤝 Cómo Contribuir

Este repositorio está destinado exclusivamente para los organizadores de la Olimpiada de Informática de El Salvador. Para contribuir:

1. **Clona el Repositorio:**
   ```bash
   git clone https://github.com/tu_usuario/banco-de-problemas-olimpiada.git
   ```
2. **Crea una Rama para tu Contribución:**
   ```bash
   git checkout -b nombre-de-la-rama
   ```
3. **Realiza los Cambios Necesarios:**
   - Agrega nuevos problemas siguiendo la estructura establecida.
   - Actualiza o mejora los problemas existentes.
4. **Realiza un Commit con un Mensaje Descriptivo:**
   ```bash
   git commit -m "Agregado problema 04: Descripción del problema"
   ```
5. **Envía tus Cambios al Repositorio Remoto:**
   ```bash
   git push origin nombre-de-la-rama
   ```
6. **Crea un Pull Request:**
   - Ve al repositorio en GitHub y crea un Pull Request para que otro organizador revise y apruebe los cambios.

Para más detalles, consulta el archivo [`CONTRIBUTING.md`](./CONTRIBUTING.md).


## 📬 Contacto

Si tienes preguntas, sugerencias o necesitas asistencia, por favor contacta a los mantenedores del repositorio o abre un **Issue** privado.

¡Gracias por tu colaboración y dedicación para hacer de la Olimpiada de Informática de El Salvador un éxito!
