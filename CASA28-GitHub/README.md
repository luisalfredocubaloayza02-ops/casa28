# CASA28

Landing page oficial de **CASA28**, alojamiento en Lima, Perú. El sitio presenta la propiedad, sus servicios y un flujo inicial de consulta de disponibilidad con opciones para reserva directa, Airbnb y Booking.

## Vista local

El proyecto es completamente estático. Puedes abrir `index.html` directamente o iniciar un servidor local:

```bash
python3 -m http.server 8080
```

Después visita `http://localhost:8080`.

## Estructura

```text
CASA28-GitHub/
├── .github/workflows/pages.yml
├── assets/
│   └── casa28-logo.png
├── index.html
├── .gitignore
└── README.md
```

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube todo el contenido de esta carpeta a la rama `main`.
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **GitHub Actions**.
5. El flujo incluido publicará el sitio automáticamente.

También puedes hacerlo desde la terminal:

```bash
git init
git add .
git commit -m "Publicar landing de CASA28"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
git push -u origin main
```

## Personalización pendiente

Busca los enlaces con `href="#"` para conectar:

- Instagram
- Airbnb
- Booking
- Políticas

En el bloque JavaScript del final de `index.html`, sustituye los avisos temporales por los enlaces reales de WhatsApp, Airbnb y Booking.

Las tres piezas de la galería son composiciones visuales provisionales. Se pueden sustituir por fotografías reales de la propiedad cuando estén disponibles.

## Tecnología

- HTML5
- CSS responsive
- JavaScript sin dependencias
- GitHub Actions y GitHub Pages

© 2026 CASA28. Todos los derechos reservados.
