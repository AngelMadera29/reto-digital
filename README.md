# Reto Digital — Cultura Digital I

Sitio HTML estático listo para Render.

## Publicación en Render
1. Sube `index.html` a un repositorio de GitHub.
2. Render → New → Static Site → conecta el repositorio.
3. Build Command: `echo "Static site ready"`
4. Publish Directory: `.`
5. Despliega y abre la URL `*.onrender.com`.

## Google Sheets
La URL de Apps Script está configurada en `GOOGLE_SCRIPT_URL` dentro de `index.html`.
El navegador usa `fetch` con `mode: "no-cors"`: **no es posible confirmar desde el navegador si Google Sheets realmente guardó la fila**. Comprueba un envío de prueba directamente en la hoja `Resultados`.

## Nota de seguridad
La calificación se calcula en el navegador y las respuestas correctas están en el HTML. Apto para práctica y actividades de repaso, no para exámenes con requisitos de integridad. El endpoint de Apps Script es público.
