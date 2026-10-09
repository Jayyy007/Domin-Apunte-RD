# Dominó Apunte — PWA para GitHub Pages (v64)

## Publicar en GitHub
1. Crea un repositorio en GitHub.
2. Sube **todos** los archivos y carpetas de este paquete; `index.html` debe quedar en la raíz.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
5. Guarda y abre la URL de GitHub Pages que GitHub te indique.

## Instalar en Android
1. Abre la URL publicada en Chrome.
2. Usa el menú ⋮ y selecciona **Instalar aplicación** o **Añadir a pantalla principal**.

## Notas
- El service worker necesita HTTPS (GitHub Pages lo proporciona) o `localhost`.
- Esta entrega empaqueta el HTML v64 recibido y agrega los archivos básicos de PWA.
- La disponibilidad de cámara, funcionamiento sin conexión y todas las funciones deben probarse en el teléfono una vez publicado.
