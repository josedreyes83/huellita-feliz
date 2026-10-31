# Adopción Huellita Feliz — sitio web

Sitio de la fundación **Adopción Huellita Feliz** (rescate y adopción de perros y gatos en Bogotá).

## Estado
Prototipo navegable (v1): intro animada (scrollytelling), catálogo de peluditos, mapa esquemático de zonas de entrega por localidad y formulario de adopción en 3 pasos (peludito → zona → hogar).

## Stack
- HTML/CSS/JS en un solo archivo (`index.html`), sin build.
- Animaciones: GSAP 3.12 + ScrollTrigger (CDN).
- Tipografías: Fredoka + Nunito Sans (Google Fonts).
- Despliegue: Vercel (estático).

## Próximos pasos
1. Fotos y fichas reales de los animales (hoy son ilustraciones de ejemplo).
2. Mapa real por UPZ (MapLibre + GeoJSON de IDECA) y verificación automática de dirección.
3. Backend en Supabase: tablas `animales`, `solicitudes`, `zonas`; panel de triage para la fundación.
4. Respuestas automáticas por WhatsApp con n8n.

## Desarrollo local
Abrir `index.html` en el navegador, o `npx serve .`
