# Pensum Ingeniería Industrial UNET

App web (PWA) para estudiantes de Ingeniería Industrial de la UNET: marca las materias aprobadas,
ve cuáles están disponibles según las prelaciones del pensum y recibe una recomendación de qué inscribir
en un semestre regular o un intensivo.

Centro de Estudiantes de Ingeniería Industrial (CEII) · Movimiento Estudiantil Alpha.

## Instalar en el teléfono
- **iPhone (Safari):** abre el link, toca Compartir → *Agregar a pantalla de inicio*.
- **Android (Chrome):** abre el link, toca ⋮ → *Instalar app* (o *Agregar a pantalla principal*).

El progreso se guarda en el teléfono de cada estudiante y, si inicia sesión, también en la nube (Firebase).
El *código de respaldo* sirve para pasarlo a otro dispositivo sin cuenta.

## Actualizar
Los datos del pensum están dentro de `index.html` (constante `DATA`). Si cambias archivos,
sube también el número de `CACHE` en `sw.js` para que los teléfonos descarguen la versión nueva.
