# Copec Pronto — prototipo HTML

Sitio estático (un solo `index.html`). Publicación sugerida: **GitHub Pages** desde la rama `main`, carpeta raíz `/`.

## Publicar en GitHub Pages

1. Crea un repositorio vacío en GitHub (sin README si ya vas a hacer push desde aquí).
2. En la raíz de este proyecto:

   ```bash
   git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
   git branch -M main
   git push -u origin main
   ```

3. En GitHub: **Settings → Pages → Build and deployment → Source**: *Deploy from a branch*.
4. **Branch**: `main`, carpeta **`/ (root)`**, Guardar.
5. La app quedará en `https://TU_USUARIO.github.io/TU_REPO/` (HTTPS; apto para probar cámara en iPhone).
