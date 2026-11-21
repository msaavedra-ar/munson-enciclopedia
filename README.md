# Munson — Gran enciclopedia del archipiélago

Libro de arte y enciclopedia de un mundo de fantasía, con navegación horizontal animada, índice con búsqueda y vista de impresión.

## Ver online

[Abrí la enciclopedia en Vercel](https://munson-enciclopedia.vercel.app/).

## Alojamiento

La web se publica en Vercel, en el proyecto `munson-enciclopedia` del equipo `mgss3`. GitHub conserva el código; GitHub Pages está desactivado.

## Archivos

- `index.html`: página completa con estilos, navegación, contenido e imágenes integradas; funciona sin conexión.
- `manifest.webmanifest`, favicons e `icons/`: identidad e iconos para la pantalla de inicio.
- `vercel.json`: sitio estático, Framework Preset `Other`, Output Directory `.`, sin instalación ni compilación.

## Actualizaciones

El primer despliegue se realizó directamente mediante la API de Vercel. Los cambios en GitHub todavía no se publican automáticamente: falta instalar la integración GitHub de Vercel y conectar `msaavedra-ar/munson-enciclopedia`, con `main` como rama de producción.

Hasta conectar esa integración, cada actualización debe desplegarse directamente en el proyecto existente de Vercel. No requiere variables de entorno.

## Verificación de la migración

Publicación en producción confirmada el 21 de noviembre de 2026. Se comprobó el acceso público, la navegación por páginas, la búsqueda de Andrinos y la apertura de la entrada Minerales. La consola del navegador no registró errores durante esas pruebas.

El contenido y las ilustraciones pertenecen a sus respectivos autores. Este repositorio no concede una licencia de reutilización.
