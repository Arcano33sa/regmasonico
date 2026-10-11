# Etapa 6/6 — Verificación de integración

## Verificaciones automatizadas / estáticas
- Integridad del ZIP y presencia de los tres PNG originales y del Excel maestro.
- Validación sintáctica de `app.js` con Node (`node --check`).
- Integridad de las rutas de accesos rápidos a Logias, Estados y Períodos.
- Sin API de persistencia ni servicio backend en la app.
- Directorio real vacío por defecto y ejemplos explícitamente ficticios.

## Smoke test manual recomendado (navegador)
1. Abrir Inicio; revisar métricas vacías, tres escudos y menú lateral.
2. Accesos rápidos: Nuevo Hermano, Buscar miembro, Catálogo de Logias, Catálogo de Estados, Períodos Institucionales.
3. Miembros: estado vacío, activar DEMO, filtrar por nombre/cuerpo/logia, abrir expediente y volver.
4. Expediente: pestañas Personal/GL/SCG33/RA, grados SCG33, VOE al seleccionar estado cuando esté disponible en DEMO.
5. Catálogos: recorrer seis pestañas, selectores por ámbito y mensajes de acciones sin guardado.
6. Probar escritorio y tablet, tabulación por teclado y comprobar consola y ausencia de scroll horizontal global.

**Alcance de validación:** la revisión de estructura y sintaxis no equivale a un smoke test ejecutado en navegador real. Las pruebas visuales, de consola y de interacción completas deben realizarse en el navegador de destino.
