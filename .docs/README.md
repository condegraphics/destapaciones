# Destapaciones con Máquina

Landing estática HTML + CSS para **Destapaciones con Máquina**, servicio de destapaciones de cañerías y cloacas con máquina profesional en CABA.

## Enfoque de la landing

La estructura prioriza la intención de urgencia: el visitante puede llamar o iniciar WhatsApp desde el primer pantallazo, con botones repetidos en los puntos de decisión y un botón flotante persistente. El contenido ordena la propuesta bajo un H1 principal y bloques H2/H3 orientados a servicios, equipo, zonas y contacto.

Se reforzaron los temas que presentaron caída de visibilidad en el reporte compartido: **destapaciones**, **destapaciones con máquina**, **destapaciones en CABA**, **destapaciones de cañerías**, **destapaciones de cloacas** y **empresa de destapaciones**. No se prometen tiempos de llegada ni precios que no estén confirmados; se comunica atención 24 horas y presupuesto sin cargo, datos presentes en la web vigente.

## Archivos

- `index.html`: estructura semántica, metadatos SEO, Schema.org tipo Plumber, formulario liviano y acciones de contacto.
- `styles.css`: diseño responsive mobile-first, sin frameworks ni JavaScript de terceros.
- `assets/`: logo e imágenes optimizadas/reutilizadas desde el sitio actual.

## Formulario

El formulario no requiere servidor: genera un mensaje precompletado y abre WhatsApp. Esto reduce dependencia de plugins y evita bloquear la carga. Para medir conversiones se recomienda agregar eventos en Google Tag Manager/GA4 en una segunda etapa, sin incorporar scripts hasta confirmar el sistema de medición.

## Próximos pasos sugeridos

1. Validar textos comerciales, barrios atendidos y disponibilidad real antes de publicar en producción.
2. Comprimir las imágenes con WebP/AVIF y agregar `srcset` si se incorporan más fotografías.
3. Configurar Search Console, GA4 y eventos para clic en teléfono, WhatsApp y envío del formulario.
4. Revisar datos estructurados y solicitar indexación de la URL final.
5. Reemplazar el dominio de producción solo después de la aprobación del cliente.
