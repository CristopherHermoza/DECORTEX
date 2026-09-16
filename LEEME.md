# Casa Velo — sitio web de cortinas y textiles

Sitio estático hecho solo con HTML y CSS, sin JavaScript ni frameworks.

## Archivos

```
casa-velo/
├── index.html        Página principal
├── productos.html    Catálogo por categorías
├── servicios.html    Proceso de trabajo y otros servicios
├── nosotros.html     Historia, valores y horarios
├── contacto.html     Formulario y datos de contacto
├── css/
│   └── estilos.css   Todos los estilos del sitio
└── img/              Aquí van tus fotos
```

Para verlo: abre `index.html` con doble clic en tu navegador.

## Qué cambiar primero

1. **Nombre y datos.** Busca `Casa Velo`, `+51 900 000 000`, `hola@casavelo.pe` y `Av. Ejemplo 123` en los cinco archivos HTML y reemplázalos.
2. **WhatsApp.** En `contacto.html` cambia `https://wa.me/51900000000` por tu número con código de país, sin `+` ni espacios.
3. **Colores.** Están al inicio de `css/estilos.css`, dentro de `:root`. Cambia un valor ahí y se actualiza todo el sitio.
4. **Fotos.** Los rectángulos con textura son marcadores hechos con CSS (clase `.foto`). Cuando tengas imágenes, ponlas en `img/` y reemplaza:

```html
<div class="foto"></div>
```

por:

```html
<img src="img/cortina-sala.jpg" alt="Cortina blackout en sala">
```

El atributo `alt` describe la foto para lectores de pantalla y para cuando la imagen no carga.

## Sobre el formulario

El formulario de `contacto.html` no envía nada todavía: HTML solo dibuja los campos. Para recibir los mensajes en tu correo, puedes crear una cuenta gratuita en Formspree y poner la dirección que te den en el atributo `action` del `<form>`.

## Detalles del diseño

- Paleta: verde pino `#2c3a34`, salvia `#7d8f84`, arena `#e6e1d7`, hueso `#f8f7f4` y bronce `#9a7b4f` como acento.
- Tipografías: Cormorant Garamond para títulos y Karla para el texto, cargadas desde Google Fonts (necesitas internet para verlas; si no, el navegador usa las de respaldo).
- Responsive: hay una sola media query al final del CSS, en 760px, donde las rejillas pasan a una columna.
