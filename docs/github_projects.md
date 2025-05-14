cat > docs/github_projects.md << "EOF"
# 🧩 Manual de GitHub Projects

Este manual explica cómo utilizar **GitHub Projects** para organizar tareas, asignar responsabilidades y hacer seguimiento del trabajo en equipo en un repositorio.

---

## 📌 ¿Qué es GitHub Projects?

GitHub Projects es una herramienta de gestión visual de trabajo dentro de GitHub que permite organizar tareas en tableros de tipo kanban, listas, cronogramas, etc. Es ideal para planificar, priorizar y hacer seguimiento de issues, pull requests y tareas individuales.

---

## 🧱 Tipos de proyectos

| Tipo de Proyecto | Descripción |
|------------------|-------------|
| 🟦 Tablero (Kanban) | Basado en tarjetas y columnas. Muy visual y práctico para flujos de trabajo. |
| 📅 Cronograma (Timeline) | Ideal para planes a largo plazo con fechas de inicio y finalización. |
| 📃 Lista (Table) | Vista en tabla, útil para filtrar, agrupar y ordenar tareas por prioridad. |

---

## 🚀 ¿Cómo crear un Project?

1. Ve al repositorio en GitHub.
2. Haz clic en la pestaña **Projects**.
3. Pulsa **"New project"**.
4. Elige entre:
   - **Board** (kanban)
   - **Table**
   - **Timeline**
5. Asigna un nombre y descripción.
6. Haz clic en **"Create"**.

> 🧠 Puedes crear Projects a nivel de repositorio, organización o usuario.

---

## 📝 Cómo añadir tareas (issues o notas)

1. Abre el Project creado.
2. Haz clic en **"+ Add item"**.
3. Puedes:
   - Escribir una nota (`note`) directamente.
   - Buscar y agregar un issue o pull request existente.

> 💡 Si conectas un issue a un Project, su estado se actualizará automáticamente conforme avance en el tablero.

---

## 👥 Asignar miembros y etiquetas

- Abre el ítem en el Project (nota o issue).
- En el panel derecho puedes:
   - Asignar un responsable (assignee).
   - Agregar etiquetas (labels).
   - Establecer prioridad.
   - Definir fechas límite.

---

## ✅ Seguimiento del progreso

- Puedes **agrupar** las tareas por estado, prioridad, responsable, etc.
- Usa filtros como:
  - `status:todo`
  - `assignee:@tuusuario`
  - `label:prioridad-alta`

> 📊 Las columnas avanzan automáticamente si el issue cambia de estado (ej. al cerrar un issue, se mueve a "Done").

---

## 🌐 Recursos útiles

- [Documentación oficial de GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects)
- [Video oficial: Organiza tu trabajo con Projects](https://www.youtube.com/watch?v=d4V1QvzGkWw)
- [GitHub Blog sobre Projects](https://github.blog/2022-06-22-the-new-github-projects/)
- ![Ejemplo visual](https://docs.github.com/assets/images/help/projects/projects-board.png)

---

## 🛠️ Buenas prácticas

- Usa etiquetas claras y colores.
- Mantén las tareas actualizadas.
- No llenes de columnas innecesarias.
- Integra tus issues y pull requests.

---

## ✍️ Créditos

Este manual fue elaborado por el equipo de **Evaluación Grupal LP2** como parte de una práctica integral sobre GitHub colaborativo.  
Autores: Luis, Sean, Maciel.

EOF
