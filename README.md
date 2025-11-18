# 📘 Gestor de Tareas — Tkinter + Strategy Pattern + Persistencia (JSON/CSV/SQLite)

Aplicación de escritorio desarrollada en **Python** para gestionar tareas personales o académicas.  
Incluye interfaz gráfica con **Tkinter**, diversas estrategias de priorización mediante **Strategy Pattern**, y persistencia en **JSON, CSV o SQLite**.

---

## 🚀 Características Principales

✔ Crear tareas  
✔ Editar tareas  
✔ Eliminar tareas  
✔ Visualizar todas las tareas  
✔ Filtrar y ordenar por categoría, estado, prioridad, fecha  
✔ Priorización inteligente mediante Strategy Pattern  
✔ Persistencia intercambiable (JSON, CSV o SQLite)  
✔ Interfaz gráfica completa con Tkinter  
✔ Modularidad y separación de responsabilidades  
✔ Documentación + pruebas unitarias

---

## 🧠 Estrategias de Prioridad (Strategy Pattern)

El sistema permite cambiar dinámicamente cómo se calcula la prioridad:

- **Por Fecha**
- **Por Categoría**
- **Manual**

---

## ▶️ Instalación

```bash
git clone https://github.com/TU_USUARIO/gestor_tareas.git
cd gestor_tareas
pip install -r requirements.txt
python src/main.py
