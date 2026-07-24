# futboltotal-links

Panel de **links gestionados remotamente** para la app **Fútbol Total (FT)**.

- `links.json` — lista de páginas que FT muestra en su sección **"Canales del creador"**.
- Lo **lee** la app FT (usuario) al abrir, vía `raw.githubusercontent.com` (repo público, sin token).
- Lo **escribe** solo **ADM FT** (con token de GitHub): agregar / quitar / reemplazar links.
- Son solo URLs de sitios de streaming, **no hay datos secretos** → repo público a propósito.

Separado del repo de la app (`futboltotal`) y del de NOVAX (`iptvxen-listas`).
