# SolarPro — Landing page

Landing page estática lista para GitHub Pages.

## Archivos
- `index.html`: estructura de la página.
- `styles.css`: estilos adaptables a móvil y escritorio.
- `assets/logo.svg`: logotipo vectorial.
- `assets/favicon.svg`: icono del sitio.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub, por ejemplo `solarpro-landing`.
2. Sube todos los archivos y carpetas conservando esta estructura.
3. Entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`. Guarda.
6. Espera a que GitHub genere la URL de publicación.

No requiere Node, base de datos ni compilación. Los archivos deben quedar en la raíz del repositorio, con `index.html` al mismo nivel que `styles.css`.

## Personalización
Puedes cambiar el nombre, textos y colores en `index.html` y `styles.css`. La tipografía Exo 2 se carga desde Google Fonts; si no hay conexión, se utiliza una fuente alternativa.
