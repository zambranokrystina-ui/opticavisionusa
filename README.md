# Invitación · Cumpleaños de Claudia Acuña

## 1. Conectar las confirmaciones (Google Sheets)
1. Ventana de incógnito, una sola cuenta de Gmail personal (no Workspace).
2. Crear una Hoja de Cálculo nueva: "Confirmaciones Cumpleaños Claudia".
3. Extensiones → Apps Script → borrar todo y pegar `apps-script-confirmaciones.gs` completo.
4. Ejecutar la función `prueba` una vez y aceptar permisos. Borrar la fila de prueba.
5. Implementar → Nueva implementación → Aplicación web. Ejecutar como: yo. Acceso: Cualquier persona.
6. Copiar la URL que termina en `/exec`.
7. En `cumpleanos.html` reemplazar `PEGAR_URL_APPS_SCRIPT_AQUI` por esa URL.
8. Compartir la hoja con Claudia (solo lectura): ahí ve la lista y, en la celda H2, el total de personas.

## 2. Publicar
Arrastrar la carpeta a Netlify Drop (app.netlify.com/drop) o subir `cumpleanos.html` a GitHub Pages.
El enlace resultante es el que se envía por WhatsApp.

## Música (opcional)
Guardar la canción como `musica.mp3` en la misma carpeta que `cumpleanos.html`.
Empieza a sonar cuando el invitado abre el sobre y aparece un botón para pausarla.
Si no hay archivo, la página funciona igual y el botón no se muestra.

## Pendientes
- `PEGAR_URL_APPS_SCRIPT_AQUI` en cumpleanos.html
- Confirmar que la hora es 8:30 p.m.
