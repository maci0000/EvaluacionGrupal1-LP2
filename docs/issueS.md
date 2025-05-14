# 🧾 Guía completa de GitHub Issues

---

## 🧠 ¿Qué es un Issue?

Los *Issues* en GitHub son herramientas clave para gestionar tareas, errores, mejoras o discusiones dentro de un proyecto. Son ideales para coordinar el trabajo colaborativo de un equipo y documentar el progreso.

---

## 🗂 Tipos comunes de Issues

- 🐛 **Reporte de errores (bugs)**
- ✨ **Propuesta de mejoras o nuevas funciones**
- ✅ **Tareas pendientes o To-Dos**
- ❓ **Consultas o discusiones técnicas**

---

## 🧩 Componentes de un Issue

Un Issue puede tener varios elementos importantes:

- **Título**: debe ser corto y descriptivo.
- **Descripción**: explica claramente el problema o propuesta, usando formato Markdown.
- **Etiquetas (Labels)**: categorizan el tipo de Issue.
- **Asignado (Assignees)**: miembro(s) del equipo responsables.
- **Milestone**: vinculación a una etapa del proyecto.
- **Comentarios**: para coordinar ideas y avances.
- **Referencias cruzadas**: enlaces a commits, PRs u otros Issues.

---

## 🛠 Cómo crear un Issue (paso a paso)

1. Ve a la pestaña **Issues** del repositorio.
2. Haz clic en **New Issue**.
3. Escribe un título descriptivo.
4. Detalla el problema o tarea en la descripción (usa Markdown).
5. Asigna el Issue a un miembro del equipo.
6. Añade etiquetas relevantes (ej. `bug`, `enhancement`, `help wanted`).
7. Relaciónalo con un Milestone si aplica.
8. Haz clic en **Submit new issue**.

📌 Ejemplo visual:
![Crear un nuevo Issue](images/crear-issue.png)

---

## 🔗 Vincular Issues con Commits o Pull Requests

Puedes relacionar un Issue con un commit o un PR para que se cierre automáticamente al aprobarse el cambio.

Usa palabras clave en el mensaje de commit o descripción del PR:

- `Fixes #1`
- `Closes #3`
- `Resolves #7`

📌 Ejemplo en un Pull Request:

```markdown
Este PR corrige el error de carga de imagen.  
Fixes #5

