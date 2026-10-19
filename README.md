# Atmósfera · Menús QR de demostración

Proyecto Astro estático con dos demostraciones:

- `/bruma-cafe/`
- `/fuego-y-mesa/`

## Desarrollo
```bash
npm install
npm run dev
npm run build
```

## Cloudflare Pages
Conectar este repositorio desde **Workers & Pages → Pages → Import an existing Git repository**.

- Framework preset: Astro
- Build command: `npm run build`
- Build output directory: `dist`

Tras publicar y comprobar la URL `.pages.dev`, agregar `demo.atmosferastudio.cl` en **Custom domains**. Verificar antes la administración DNS del dominio principal, que continúa en Vercel.

## Editar contenido
Modificar `src/data/menus.js`. Los cambios publicados en la rama principal generan una nueva compilación.

No hay base de datos ni funciones de servidor. Los negocios, precios y descripciones son ficticios.
