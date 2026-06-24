# Portfolio GIS - Julio Cruz

Este es el repositorio del portfolio profesional de Julio Cruz, Consultor GIS y Analista de Datos Espaciales. 
La web está diseñada con HTML, CSS y JavaScript (Vanilla) y está completamente optimizada para ser desplegada como una página estática en **GitHub Pages**.

## Estructura de Archivos

- `index.html`: Estructura principal y contenido extraído del CV.
- `styles.css`: Estilos modernos, diseño responsivo y soporte nativo para Modo Oscuro (Dark Mode).
- `script.js`: Interactividad (scroll suave, menú móvil, modales para proyectos).
- `/assets`: Carpeta con imágenes (actualmente contiene placeholders profesionales generados mediante IA, que puedes reemplazar por tus propias capturas).

## Cómo Desplegar en GitHub Pages

Para publicar este portfolio y que sea accesible a través de una URL pública (ej. `https://tu-usuario.github.io` o `https://tu-usuario.github.io/portfolio`), sigue estos pasos:

1. **Sube los archivos a GitHub:**
   - Inicia sesión en tu cuenta de [GitHub](https://github.com).
   - Crea un nuevo repositorio.
   - Sube todos estos archivos (`index.html`, `styles.css`, `script.js`, y la carpeta `assets`) a la rama principal (`main` o `master`).

2. **Activa GitHub Pages:**
   - Ve a la pestaña **Settings** (Configuración) de tu repositorio.
   - En la barra lateral izquierda, haz clic en **Pages** (Páginas).
   - En la sección "Build and deployment", bajo "Source", selecciona **Deploy from a branch**.
   - Bajo "Branch", selecciona tu rama principal (generalmente `main`) y la carpeta `/ (root)`.
   - Haz clic en **Save** (Guardar).

3. **Espera unos minutos:**
   - GitHub Actions procesará tu sitio. Una vez terminado, aparecerá un mensaje en esa misma página de Settings > Pages con el enlace a tu nueva web publicada.

## Personalización

- **Imágenes:** Puedes reemplazar las imágenes en la carpeta `assets` por las tuyas propias. Asegúrate de mantener el mismo nombre de archivo, o si cambias el nombre, actualiza la ruta correspondiente en el archivo `index.html` (dentro de las etiquetas `<img>`).
- **Colores:** Si deseas cambiar los colores principales, puedes modificar las variables CSS en la parte superior del archivo `styles.css` dentro del bloque `:root`.
- **Contacto:** Revisa los enlaces de la sección de contacto en `index.html` para asegurarte de que apuntan a tus perfiles correctos de LinkedIn, WhatsApp, etc.
