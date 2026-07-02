# Dozer Proyectos — sitio web

## Estructura

```
dozer-proyectos/
├── index.html        → contenido y estructura (textos, secciones)
├── css/
│   └── style.css     → todos los estilos (colores, tipografía, layout)
├── js/
│   └── main.js        → interacciones (por ahora: efecto del header al hacer scroll)
├── assets/
│   └── dozer-logo.png → tu logo
└── README.md
```

Separé todo en tres archivos porque es la convención estándar y hace mucho
más fácil editar sin perderte: HTML = contenido, CSS = apariencia,
JS = comportamiento.

## Cómo abrirlo en VS Code

1. Copia toda la carpeta `dozer-proyectos` a tu computadora.
2. Abre VS Code → `File > Open Folder...` → selecciona `dozer-proyectos`.
3. Instala la extensión **Live Server** (de Ritwick Dey, la más usada).
   Con eso, click derecho sobre `index.html` → **"Open with Live Server"**
   y se abre en el navegador con recarga automática cada vez que guardas
   un cambio. Así no tienes que abrir el archivo manualmente cada vez.

## Dónde tocar cada cosa

- **Cambiar textos** (títulos, descripciones de servicios, teléfono,
  correo): edita directo en `index.html`, es todo texto plano entre
  etiquetas.
- **Cambiar colores**: en `css/style.css`, arriba de todo hay un bloque
  `:root { ... }` con variables como `--navy-950` y `--steel-500`.
  Cambia el valor ahí una sola vez y se actualiza en todo el sitio.
- **Cambiar el logo**: reemplaza el archivo `assets/dozer-logo.png`
  manteniendo el mismo nombre (o cambia la ruta en `index.html` si usas
  otro nombre).
- **Agregar una sección nueva**: copia el bloque `<section class="section">
  ... </section>` que más se parezca a lo que quieres agregar, y ajusta.

## Próximos pasos pendientes (cuando tengas la info)

- Teléfono / WhatsApp real (hoy dice "Por confirmar").
- Correo definitivo (hoy es un placeholder).
- Fotos reales de trabajos para reemplazar los íconos de línea en
  la sección "Nosotros" si quieres ir a fotografía real.
- Conectar el formulario de contacto a un servicio real (hoy solo
  simula el envío en el navegador — no manda nada a ningún lado todavía).
