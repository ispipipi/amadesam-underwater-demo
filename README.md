# AMADESAM Underwater Operations Demo

Demo funcional client-side para el Bloque 1 Underwater Services de AMADESAM.

## Abrir la demo

Abre este archivo en el navegador:

`amadesam-underwater-demo.html`

No requiere backend, instalacion de dependencias ni base de datos. Todo el estado se guarda en `localStorage` del navegador.

## Modulos incluidos

- Dashboard con KPIs, mapa visual del puerto, calendario semanal, servicios activos y alertas SLA.
- Cotizaciones con analisis con IA del email, ejemplos precargados, deteccion de tipo Cotizacion/Disponibilidad, autofill de barco/LOA, plantillas A/B, calculo de tarifas y preview tipo PDF.
- Lista de cotizaciones filtrable y ordenable, con drawer de detalle y cambios de estado.
- Seguimiento de cotizaciones vencidas con recordatorio simulado.
- Confirmaciones y checklist de documentacion pre-arribo.
- Permisos DockRP con formulario, documentos simulados y kanban de estados.
- Operaciones con calendario, pizarra de buzos y transiciones de servicio.
- Worksheets, reportes finales, facturacion pendiente, historial y configuracion editable.

## Reset de datos

Para volver al seed original, borra la clave `amadesam-underwater-demo-v1` desde las herramientas de desarrollador del navegador, en Application > Local Storage.
