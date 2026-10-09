# Portafolio

Sitio estático (HTML + CSS) publicado con GitHub Pages.

## Desarrollo local

```bash
python3 -m http.server 8000
```

Abre http://localhost:8000

## Deploy

Cada `push` a `main` ejecuta `.github/workflows/deploy.yml`, que publica el sitio en GitHub Pages.
El progreso se ve en la pestaña **Actions** del repositorio.
