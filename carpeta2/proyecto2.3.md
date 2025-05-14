#  Buenas Prácticas en GitHub  

Estas son algunas recomendaciones para trabajar de manera eficiente y colaborativa en proyectos usando **Git y GitHub**.  

## 🔹 Flujo de Trabajo Recomendado  

1. **Sincroniza tu repositorio local frecuentemente**  
   ```bash
   git pull origin main  # O la rama principal que usen

2. **Trabaja en ramas(branches)**
   ```bash
   git checkout -b nombre-de-la-rama  # Crea una rama nueva

3. **Haz commits atómicos y descriptivos**
- Un commit = un cambio específico.
- Usa mensajes claros:
   ```bash
   git commit -m "feat: poner una descripción concisa"
- Estilos recomendados:
  - `feat`: para nuevas funcionalidades
  - `fix`: para correciones de bugs
  - `docs`: para cambios en documentación
  - `refactor`: para mejoras de código sin cambiar funcionalidad
4. **Sube cambios con frecuencia**
   ```bash
   git push origin "nombre de la rama"

##  Buenas practicas en Pull Requests(PRs)

### 1. PRs pequeños y enfocados
- Un PR = una funcionalidad especifica(evita mezclar cambios no relacionados).
### 2. Revisa tus cambios antes de crear un PR
- Usa git diff o herramientas gráficas para ver qué modificiaste.
### 3. Describe claramente tu PR
- Incluye:
    - Que cambiaste.
    - Por qué lo hiciste
    - Capturas de pantalla
### 4. Solicita revisión a tus compañeros
- Asigan reviwes en GitHub(pestaña derecha en el PR).
### 5. Resuelve los comentarios antes de fusionar
- Si te piden cambios, haz nuevos commits en la misma rama.

## QUE EVITAR
- Commits del tipo "cambios" sin explicación
- PRs con cientos de cambios no relacionados
- Fusioanr tu propio PR sin revisión (a menos que sea urgente)