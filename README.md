# CASA28 · sitio multipropiedad

Web estática de CASA28 para presentar y reservar varios alojamientos de corta estancia en Lima.

## Estructura

```text
├── index.html                         # Portada y catálogo
├── properties/
│   ├── casa28-i-miraflores/index.html # CASA28 I
│   └── casa28-miraflores/index.html   # CASA28 II
├── assets/
│   ├── css/styles.css
│   ├── casa28-logo.png
│   └── properties/                    # Fotografías por propiedad
└── .github/workflows/pages.yml
```

Cada alojamiento tiene una ruta propia, una carpeta de imágenes independiente y un enlace directo a su anuncio de Airbnb.

## Vista local

```bash
python3 -m http.server 8080
```

Abre `http://localhost:8080`.

## Publicación

El workflow incluido publica automáticamente en GitHub Pages cada cambio enviado a `main`. Para Cloudflare Pages, el directorio de salida es la raíz del repositorio.

## Estado

- CASA28 I: Airbnb conectado.
- CASA28 II: Airbnb conectado.
- Booking y reserva directa: pendientes.

© 2026 CASA28.
