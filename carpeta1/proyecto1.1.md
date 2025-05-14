# **Pull Request**

Un **Pull Request** es una solicitud para integrar cambios de una rama a la rama principal (`main`/`master`). Facilita la **revisión colaborativa** del código antes de fusionarlo.

## **Pasos para crear un Pull Request:**

1.  Crear una rama nueva (desde tu terminal local) para poder trabajar en algo nuevo o corregir un error sin afectar la principal `git branch "nueva rama"`.
2.  Realiza cambios y commits `git commit -m "Descripción clara de los cambios"`.
3.  Dirigite a la pestaña "Pull Requests" y haz click en "New Pull Request".
![pull request](imagen1.png)
4.  Elige las ramas de comparación (la rama de donde hiciste los cambios) y la base (usualmente `master` o `main`).
5.  Añade un **titulo** y una descripción detallada de los cambios realizados. Explica por qué estos cambios son necessarios.
6. Haz clic en "Create Pull Request" para enviarlo.

## **Ejemplo de mensaje para un Pull Request:**

- **Título :** Añadir validación al formulario de login
- **Descripción :** Este Pull Request incorpora una validación para verificar que el campo de correo electrónico no se encuentre vacío antes de enviar el formulario. Además, se solucionó un problema relacionado con la validación de la contraseña.

Este Pull Request es revisado por otros miembros del equipo antes de ser fusionado con la rama principal.

