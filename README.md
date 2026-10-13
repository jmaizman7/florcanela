# Flor de Canela Café Bistró

Sitio estático (HTML + CSS, sin build). Carpeta lista para Vercel.

## Contenido

- `index.html`: la página completa
- `img/`: fotos y logo
- `favicon.svg`: ícono de la pestaña
- `vercel.json`: configuración (URLs limpias y caché de imágenes)

## Subir a Vercel

**Opción 1: desde la terminal**

1. Instala Node.js si no lo tienes.
2. Abre una terminal dentro de esta carpeta.
3. Ejecuta `npx vercel` y responde las preguntas (si pregunta por el framework, elige "Other").
4. Para publicar en el dominio definitivo ejecuta `npx vercel --prod`.

**Opción 2: desde GitHub**

1. Sube esta carpeta a un repositorio nuevo en GitHub.
2. En vercel.com entra a Add New > Project e importa el repositorio.
3. Framework Preset: **Other**. Deja vacíos Build Command y Output Directory.
4. Pulsa Deploy.

## Cambios frecuentes

- Teléfono y WhatsApp: busca `74664695` y `59174664695` en `index.html` (591 es el código de Bolivia).
- Fotos: reemplaza los archivos de `img/` con el mismo nombre. `hero.jpg` es la foto principal, `interior.jpg` la del local y `servicios.jpg` la de bebidas y postre.
