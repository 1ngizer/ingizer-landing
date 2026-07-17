# ingizer.com — Landing

Landing corporativa estática de **ingizer** (director financiero con IA).
Sitio 100% estático (HTML/CSS/JS), desplegado en **Netlify** con dominio `ingizer.com`.

## Estructura
```
index.html            Página única (CSS y JS inline)
assets/               Logo, banner OG, app icon, marca
manifest.webmanifest  PWA
robots.txt            SEO
sitemap.xml           SEO
netlify.toml          Config de deploy (publish = raíz, sin build)
```

## Cómo se actualiza
1. Se edita `index.html` (o los assets).
2. `git commit` de los cambios.
3. `git push` → **Netlify redespliega automáticamente** (~1 min). No se toca el DNS.

## Notas
- El asistente vive en `https://app.ingizer.com` (los CTA apuntan ahí).
- Marca oficial: navy `#081C2A`, verde `#04C537`, espectro del medidor; Comfortaa + Poppins.
- `index-a-respaldo.html` es un respaldo local y **no se despliega** (ver `.gitignore`).
