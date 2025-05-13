# 📁 Publicar un sitio con GitHub Pages

## 1. ¿Qué es GitHub Pages?

**GitHub Pages** es un servicio gratuito de GitHub que permite publicar sitios web estáticos directamente desde un repositorio. Puedes usar archivos HTML, CSS, JavaScript o Markdown, y mostrar el contenido en una dirección pública como: https://usuario.github.io/repositorio


Esto lo hace ideal para portafolios, blogs, documentación, proyectos académicos, entre otros.

---
## 2. ¿Para qué sirve GitHub Pages?

---
## 3. ¿Cómo publicar un sitio estático?

A continuación, se describen los pasos básicos para publicar un sitio usando GitHub Pages:

1. Crear un repositorio en GitHub.
2. Crear una página HTML (`index.html`) o Markdown (`index.md`) con el contenido que deseas mostrar.
3. Crear una carpeta llamada `/docs` y colocar allí tu archivo.
4. Subir todo al repositorio (hacer _commit_ y _push_).
5. Ir a la pestaña **Settings** del repositorio.
![Settings](src/imagen1.png)
6. En la sección **Pages**, seleccionar la rama principal (`main`) y la carpeta `/docs` como fuente.
![Pages](src/imagen2.png)
![docs](src/imagen3.png)
7. Guardar los cambios.
8. Después de unos segundos, tu sitio estará disponible en: 
https://[usuario].github.io/[repositorio]


---

## 4. Estructura ideal de un repositorio

Se recomienda organizar el repositorio con la siguiente estructura:

```
/repositorio
├── /docs
│ ├── index.html # Página principal del sitio
│ └── github_pages.md # Explicación teórica (este archivo)
├── /src
│ ├── estilos.css # Hojas de estilo
│ ├── script.js # Archivos JavaScript
│ └── imagenes/ # Imágenes u otros recursos
├── README.md # Información general del repositorio

``` 
### Descripción de carpetas:

- `/docs`: contiene el contenido visible del sitio. Es la fuente que GitHub Pages usará para publicar.
- `/src`: incluye los archivos fuente del proyecto. Aquí puedes desarrollar antes de mover a `/docs`.
- `README.md`: archivo principal del repositorio. Explica el propósito del proyecto, cómo usarlo, y puede incluir el enlace al sitio web publicado.

---

> ✅ **Recuerda:** GitHub Pages solo funciona con archivos estáticos. No puedes usar bases de datos ni lenguajes del lado del servidor como PHP o Python.


