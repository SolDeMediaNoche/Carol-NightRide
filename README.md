# Para Carol 💖 — Night Ride FM

Una página de cumpleaños con una carta personalizada, una estación de radio, visualizador musical y galería de recuerdos en video.

## Publicar en GitHub Pages
1. Sube el contenido de esta carpeta (`index.html`, `musuc/` y `videos/`) a la raíz de un repositorio de GitHub.
2. Entra a **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**.
4. Selecciona la rama `main` y la carpeta `/ (root)`, guarda y espera a que GitHub Pages publique el sitio.

## Importante
- Mantén las carpetas `musuc/` y `videos/` junto a `index.html`; la página usa rutas relativas.
- La primera pista es `Feliz cumple (3).mp3` y aparece como **Feliz cumpleaños — Alvarito Díaz**.
- Las demás pistas se cargan desde `musuc/`.
- Los clips de `videos/` sustituyen las imágenes de motos de la galería.
- El visualizador ya responde al audio y cambia de paleta con cada canción.
- Para que la música funcione, abre la página y pulsa **Encender Motor y Abrir**; los navegadores bloquean el audio automático hasta que hay una interacción.

Los archivos de música y video se incluyen tal como venían en el ZIP original, salvo los nombres que se limpiaron para quitar `y2meta.com`.

## Importante: fotos y videos que se añaden desde la página

El botón **Añadir Fotos / Videos** permite previsualizar archivos durante la sesión actual del navegador, pero esos archivos no se guardan en GitHub ni quedan disponibles automáticamente para otras personas o dispositivos. Al recargar la página, pueden desaparecer.

Para que Carol y cualquier visitante vean los archivos de forma permanente, hay que agregarlos a la carpeta del proyecto (por ejemplo, `fotos/` o `videos/`), actualizar la lista `mediaItems` en `index.html` y volver a subir los cambios al repositorio. GitHub Pages publica los archivos que están dentro del repositorio; no sincroniza automáticamente los archivos que alguien selecciona con el botón de la web.
