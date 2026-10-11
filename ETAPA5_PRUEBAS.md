# Etapa 5/6 — Informe y pruebas

- Catálogos visuales: Logias, Grados, Cargos, Títulos, Períodos, Estados.
- Estados: un catálogo vacío compartido; ejemplos solo con activación explícita DEMO.
- SCG33: exactamente 4°, 9°, 14°, 18°, 24°, 30°, 31°, 32°, 33°.
- Cargos: listas tomadas del Excel; CMRACA sin lista de cargos en el Excel, se presenta vacío.
- Períodos: ámbitos independientes, vacíos.
- Acciones: solo demostración, no persisten datos.
- Conservados assets originales y rutas existentes.

## Verificación estática
- Sintaxis JS mediante node --check.
- Integridad ZIP mediante unzip -t.
- Smoke test de navegador: pendiente de validación manual en dispositivo destino; no se afirma que se haya ejecutado.

## Limitación heredada
El expediente de Etapa 4 todavía utiliza algunas opciones demostrativas propias y no está enlazado a estos catálogos; la integración funcional queda fuera del prototipo.
