# Copec Pronto — prototipo HTML

Sitio estático (un solo `index.html`). Publicación sugerida: **GitHub Pages** desde la rama `main`, carpeta raíz `/`.

## Publicar en GitHub Pages

Este repo usa un workflow (`.github/workflows/deploy-pages.yml`) que despliega el sitio estático.

### Primera vez (orden importante)

1. Repo **público** (cuenta gratuita: Pages no aplica a repos privados sin plan de pago).
2. En GitHub: **Settings → Pages → Build and deployment**.
3. **Source** → **GitHub Actions** → **Save**.  
   Sin este paso, el workflow falla en *Setup Pages* con `Not Found` (GitHub aún no tiene creado el sitio de Pages).
4. **Actions** → abre el último workflow → **Re-run failed jobs** (o haz un push vacío).
5. Cuando el job esté en verde, el sitio queda en:

   `https://sebacaro.github.io/test-usuario/`

### Opción sin Actions

**Settings → Pages** → **Deploy from a branch** → rama **`main`**, carpeta **`/ (root)`** → Save. No necesitas el workflow; GitHub publica el `index.html` solo.
