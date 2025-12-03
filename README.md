# Tarea 14 - Uso de Git y GitHub
## Programación 1 - Héctor Gabriel Sánchez Pérez

Este repositorio fue creado como parte de la **Tarea 14** de la clase de Programación 1, donde se demuestra el uso de **Git** como sistema de control de versiones y **GitHub** como plataforma de alojamiento de código.

---

## 📋 Objetivos de la Tarea

Esta tarea cumple con los siguientes puntos requeridos:

### ✅ 1. Modificar un script con control de versiones
Se utilizó el script `main.py` de tareas previas y se le realizaron **múltiples modificaciones**, guardando cada cambio en el repositorio local de Git mediante commits individuales.

**Archivo modificado:** `main.py`
- **Primera modificación**: Se agregó funcionalidad básica con mensaje de salida
- **Modificaciones adicionales**: Se realizaron mejoras en el código y comentarios

### ✅ 2. Crear un sitio de GitHub
Se creó un repositorio público en GitHub para alojar el proyecto:

**🔗 Enlace al repositorio:**  
[https://github.com/cfocoder/tarea_clase_14_programacion_1](https://github.com/cfocoder/tarea_clase_14_programacion_1)

### ✅ 3. Subir todas las versiones a GitHub
Se subieron todas las versiones del archivo modificado al repositorio remoto de GitHub usando los comandos:
```bash
git add .
git commit -m "descripción del cambio"
git push origin main
```

El historial completo de commits está disponible en el repositorio de GitHub, donde se puede ver la evolución del código.

---

## 📂 Estructura del Proyecto

```
tarea_clase_14_programacion_1/
├── main.py                                 # Script principal con modificaciones
├── Clase_12_SQL_Hector_Sanchez.ipynb      # Notebook con ejercicios de SQL
├── DB_Propia.db                            # Base de datos SQLite
├── pyproject.toml                          # Configuración del proyecto
├── README.md                               # Este archivo
└── .python-version                         # Versión de Python utilizada
```

---

## 🚀 Comandos Git Utilizados

Durante el desarrollo de esta tarea se utilizaron los siguientes comandos de Git:

```bash
# Inicializar repositorio local
git init

# Configurar identidad
git config user.name "Héctor Sánchez"
git config user.email "hector@example.com"

# Agregar archivos al staging area
git add main.py
git add .

# Hacer commits con mensajes descriptivos
git commit -m "Inicialización del Proyecto"
git commit -m "Primera modificación al script"
git commit -m "Segunda modificación al script"

# Conectar con repositorio remoto
git remote add origin https://github.com/cfocoder/tarea_clase_14_programacion_1.git

# Subir cambios a GitHub
git push -u origin main
git push origin main

# Ver historial de commits
git log
git log --oneline

# Ver estado del repositorio
git status
```

---

## 📸 Evidencias

Las capturas de pantalla que demuestran el cumplimiento de cada punto se encuentran documentadas en el repositorio de GitHub, mostrando:

1. **Historial de commits** con las modificaciones al script
2. **Repositorio público en GitHub** con todos los archivos
3. **Historial de versiones** visible en la interfaz de GitHub
4. **Configuración del repositorio** y opciones de visibilidad

---

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**: Lenguaje de programación
- **Git**: Sistema de control de versiones distribuido
- **GitHub**: Plataforma de alojamiento de código
- **SQLite**: Base de datos para el notebook de SQL
- **Jupyter Notebook**: Para ejercicios de SQL con Python
- **uv**: Gestor de paquetes y entornos virtuales de Python

---

## 📝 Contenido Adicional

El repositorio también incluye:
- **Notebook de SQL** (`Clase_12_SQL_Hector_Sanchez.ipynb`) con ejercicios prácticos de consultas SQL usando Python, SQLite y Pandas
- **Base de datos SQLite** con datos de empleados, proyectos, clientes y resultados de la Maratón de Nueva York

---

## 👨‍💻 Autor

**Héctor Gabriel Sánchez Pérez**

Tarea realizada para la clase de **Programación 1**  
Tarea 14: Uso de Git y GitHub

---

## 📅 Fecha de Entrega

Diciembre 2025

---

## 🔗 Enlaces Importantes

- **Repositorio GitHub**: [https://github.com/cfocoder/tarea_clase_14_programacion_1](https://github.com/cfocoder/tarea_clase_14_programacion_1)
- **Perfil GitHub**: [https://github.com/cfocoder](https://github.com/cfocoder)

---

*Este proyecto demuestra el uso de Git para control de versiones y GitHub para colaboración y alojamiento de código fuente.*
