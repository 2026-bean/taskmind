# TaskMind — versión lista para GitHub Pages

Esta carpeta contiene TaskMind v3 preparado como PWA.

## Archivos
- `index.html` — aplicación TaskMind
- `manifest.json` — configuración para instalarla como app
- `sw.js` — soporte offline/cache
- `icon.svg` — icono de la app

## Publicarlo en GitHub Pages
1. Crea un repositorio nuevo en GitHub, por ejemplo `taskmind`.
2. Sube estos 4 archivos a la raíz del repositorio.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda y espera a que GitHub publique la página.
7. Abre la dirección `https://TU-USUARIO.github.io/taskmind/` en tu celular.

## Instalar en el celular
Desde el navegador del celular, abre la página publicada y usa la opción del navegador **Agregar a pantalla de inicio / Instalar aplicación** si aparece.

Los datos de TaskMind siguen guardándose localmente en el navegador. Esta versión no sincroniza automáticamente los datos entre PC y celular.
