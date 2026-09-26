# Portafolio — José Luis Monteza

**En vivo:** https://joseluismontezamilian12-rgb.github.io/portafolio-frontend/

Portafolio de una sola página, bilingüe (español / inglés), hecho a mano: un único `index.html` con HTML, CSS y JavaScript sin framework ni paso de build, publicado con GitHub Pages.

## Qué muestra

- **SupplyChainCore** como proyecto principal, con la API en vivo en Azure y credenciales de solo lectura para probarla en 30 segundos.
- **Producto propio:** Odontario, SaaS para consultorios dentales en producción, con demo pública.
- **Trabajo profesional:** el soporte informático al JNE, el motor de precantidades de Manzana Verde, el scraper de prospección, Astro IA y Kavea Travel.
- **Proyectos de ingeniería:** SupplyChainCore, Merma AI, ECommerceEcosystem y ECS Dashboard, cada uno con demo y código.
- **Decisiones de ingeniería** que enlazan al archivo exacto que las implementa.
- **CV descargable** en español y en inglés; el botón sigue el idioma elegido.

## Detalles

- **Idioma:** cada texto traducible lleva su versión en inglés en `data-en`. El script guarda el español al cargar y alterna entre ambos sin recargar. Recuerda la elección en `localStorage` y, si no hay ninguna, usa el idioma del navegador.
- **Accesibilidad:** enlace para saltar al contenido, foco visible con teclado y respeto por `prefers-reduced-motion`.
- **Vista previa al compartir:** metadatos Open Graph para LinkedIn y WhatsApp.

## Correr en local

No hace falta instalar nada: abre `index.html` en el navegador, o sirve la carpeta con cualquier servidor estático:

```bash
npx serve .
```

## Archivos

| Archivo | Contenido |
| :-- | :-- |
| `index.html` | Toda la página: marcado, estilos y script |
| `Jose_Luis_Monteza_CV_FullStack_Developer_ES.pdf` | CV en español |
| `Jose_Luis_Monteza_CV_FullStack_Developer.pdf` | CV en inglés |

## Licencia

MIT — ver [LICENSE](LICENSE).
