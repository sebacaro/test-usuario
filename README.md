# Copec Pronto — prototipo HTML

Sitio estático (un solo `index.html`). Publicación sugerida: **GitHub Pages** desde la rama `main`, carpeta raíz `/`.

## Publicar en GitHub Pages

Este repo incluye un workflow (`.github/workflows/deploy-pages.yml`) que sube el sitio estático.

1. Sube los cambios: `git push origin main`
2. En GitHub, abre el repo → **Settings → Pages**.
3. En **Build and deployment → Source**, elige **GitHub Actions** (no “Deploy from a branch” si vas a usar el workflow).
4. Espera a que termine el workflow en la pestaña **Actions** (1–2 minutos la primera vez).
5. La URL será: `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`

Si ves **404 “There isn’t a GitHub Pages site here”**, casi siempre falta el paso 2–3 o el workflow aún no ha terminado.

### Opción sin Actions

En **Settings → Pages**, fuente **Deploy from a branch**, rama **`main`**, carpeta **`/ (root)`**, Guardar.
