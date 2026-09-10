# CMS Strapi FNA - Presentación

Manual operativo interactivo del CMS Strapi que sostiene el portal institucional
del Fondo Nacional del Ahorro. Presentación estática de una sola página (24
secciones), con identidad visual de la Agencia Nacional Digital (AND).

## Contenido

- `index.html` — presentación (misma que `CMS_Strapi_FNA_Presentacion.html`)
- `CMS_Strapi_FNA_Presentacion.html` — copia con nombre descriptivo
- `vercel.json` — configuración de despliegue (`cleanUrls`)

Incluye: matriz de 7 roles (RBAC), diagrama del flujo editorial (9 estados),
límites técnicos, glosario con buscador y una **evaluación técnica de 30
preguntas** (casos y escenarios, con navegador de preguntas, revisión previa,
confirmación de envío y resultado por competencia).

## Despliegue

Sitio estático en Vercel. La rama de producción es `master`; cada push a `master`
publica en producción automáticamente.
