# Posada Nueva España · Sitio Web

Rediseño moderno del sitio web de **Posada Nueva España**, una casona colonial de 1810 ubicada en el tradicional barrio de Yanahuara, Arequipa, Perú.

## Características

- **Single-page** moderno, totalmente responsive (móvil, tablet, desktop)
- **Tres idiomas**: Español, Inglés, Francés — selector en vivo sin recarga
- **Reservas por WhatsApp**: cada botón de reserva abre WhatsApp con un mensaje pre-escrito en el idioma del visitante, identificando la habitación deseada
- **Pantalla de carga** con animación tipográfica del monograma del hotel
- **Galería** con fotografías profesionales de la casona
- **Mapa integrado** de Google Maps en la sección de contacto
- **Favicon** y apple-touch-icon personalizados
- **Cero dependencias build**: HTML + CSS + JS puro, listo para servir desde cualquier hosting estático

## Estructura

```
.
├── index.html              # Sitio completo (single file)
├── img/                    # 51 fotografías procesadas a JPG web (~1800px)
├── favicon-32.png          # Favicon estándar
├── favicon-512.png         # Favicon alta resolución
├── apple-touch-icon.png    # Ícono para iOS / pantalla de inicio
└── README.md
```

## Stack

- HTML5 + CSS3 puro (variables CSS, grid, flexbox)
- JavaScript vanilla (sin frameworks)
- Fuentes Google: Cormorant Garamond (titulares) + Inter (cuerpo)
- Paleta inspirada en la piedra sillar y la buganvilia de Arequipa

## Despliegue

Cualquier hosting estático funciona. Recomendados:

- **GitHub Pages**: activa en Settings → Pages, branch `main`, carpeta `/`
- **Netlify / Vercel**: arrastra la carpeta o conecta el repo, deploy automático
- **Hosting tradicional**: sube el contenido por FTP a la raíz del dominio

## Contacto del hotel

- **Dirección**: Calle Antiquilla 106, Yanahuara, Arequipa
- **Teléfonos**: +51 (54) 71 8562 · +51 958 347 809 · +51 993 404 899
- **Email**: nuespana@gmail.com

---

© 2026 Posada Nueva España · Una casona desde 1810
