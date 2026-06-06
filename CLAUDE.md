# Librería Circular de Guayaquil — Proyecto Web

## Contexto del proyecto
Sitio web estático para la **Librería Circular de Guayaquil**, una iniciativa comunitaria fundada por **Mayi Gómez** que distribuye libros 100% gratis, sostenida por donaciones. Reconocida por la ESPOL como modelo de economía circular aplicado a la cultura.

El sitio funciona como extensión digital de sus redes sociales.

## Stack
- HTML5 semántico + CSS3 moderno (custom properties, grid, flexbox) + Vanilla JS
- Sin frameworks, sin build step — se abre directo en el navegador
- Google Fonts: Playfair Display (headings) + DM Sans (body)

## Estructura de archivos
```
libreria-circular-guayaquil/
├── index.html          ← sitio completo (una sola página)
├── css/styles.css      ← todos los estilos
├── js/main.js          ← nav mobile, scroll-reveal, smooth scroll
└── assets/images/      ← vacío, aquí van las fotos reales
```

## Paleta de colores
| Token          | Valor     | Uso                        |
|----------------|-----------|----------------------------|
| `--cream`      | `#FBF7F2` | Fondo principal            |
| `--linen`      | `#F0EAE0` | Fondo secciones alternas   |
| `--peach-pale` | `#FADDCA` | Acentos suaves             |
| `--peach`      | `#F4B896` | Acentos medios             |
| `--orange`     | `#E07A4F` | Color marca principal      |
| `--orange-dark`| `#C4613A` | Hover / botones            |
| `--wood`       | `#8B5740` | Color secundario           |
| `--bark`       | `#4E2D1E` | Texto oscuro / headings    |

## Secciones del sitio (en orden)
1. **Hero** — Titular, libros CSS animados flotando, CTAs WhatsApp + Instagram
2. **Sobre nosotros** (`#quienes-somos`) — Historia, Mayi Gómez, conexión ESPOL
3. **Cómo funciona** (`#como-funciona`) — 3 pasos del modelo circular
4. **Acompañamiento emocional** (`#acompanamiento`) — Sesiones, link Notion
5. **En los medios** (`#medios`) — Entrevista ESPOL (Google Drive)
6. **Apóyanos** (`#apoyanos`) — Donación libros + apoyo monetario Notion
7. **Footer** — Todos los links y redes
8. **FAB** — Botón flotante WhatsApp (siempre visible)

## Links externos integrados
- WhatsApp: `https://api.whatsapp.com/message/6DYN3IJA7Q4QA1?autoload=1&app_absent=0`
- Instagram librería: `https://www.instagram.com/libreriacirculardeguayaquil/`
- Instagram Mayi: `https://www.instagram.com/mayigomez__/`
- Entrevista ESPOL: `https://drive.google.com/file/d/10XcreIqo4Vuy13E8-pZCZgvSyWh0TQbO/view`
- Sesiones Notion: `https://nifty-run-647.notion.site/Info-Sesiones-34bc0065e588806987a0f2093ed8bd1e`

## Pendiente / cómo continuar
- [ ] **Foto de Mayi** — Reemplazar `about__photo-placeholder` en `index.html` con `<img src="assets/images/mayi-gomez.jpg" alt="Mayi Gómez, fundadora">`
- [ ] **Fotos del hero/galería** — Si el cliente provee imágenes de Instagram, integrarlas
- [ ] **Link de apoyo monetario** — Si existe un Notion separado del de sesiones, actualizarlo en la sección `#apoyanos` (actualmente apunta al mismo Notion)
- [ ] **Favicon** — Añadir `<link rel="icon">` con logo o símbolo ◎
- [ ] **Deploy** — El sitio es estático; compatible con Netlify, Vercel, GitHub Pages o cualquier hosting

## Skills instalados en el proyecto padre
En `C:\sistemas\BibliotecasWeb\.claude\skills\` están instalados:
- **impeccable** — 23 comandos de diseño (`/impeccable shape`, `/impeccable polish`, etc.)
- **design-motion-principles** — Auditoría y creación de animaciones

Para usar impeccable desde el IDE, escribir `/impeccable <comando>` en el chat de Claude Code.
