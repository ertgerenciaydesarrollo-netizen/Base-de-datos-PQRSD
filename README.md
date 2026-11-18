# Seguimiento PQRSD

Tablero interactivo para hacer seguimiento a las PQRSD por vicepresidencia y dependencia. Es un único archivo, `index.html`, que funciona sin instalación y sin conexión.

## En línea (GitHub Pages)

https://ertgerenciaydesarrollo-netizen.github.io/Base-de-datos-PQRSD/

La página publicada no contiene datos: cada persona carga su CSV y este se procesa solo en su navegador. Para publicarla, en *Settings → Pages* elija *Deploy from a branch*, rama `main`, carpeta `/ (root)`.

## Uso

1. Abra la página anterior, o descargue `index.html` y ábralo en el navegador (Chrome, Edge o Firefox).
2. Pulse **Cargar CSV** y seleccione el listado de radicados exportado (separado por `;`, con las columnas «Nombre Vicepresidencia Actual», «Nombre Dependencia Actual», «Cumplimiento», «Seguimiento Cumplimiento», etc.).
3. Navegue por vicepresidencia y dependencia en el panel izquierdo.
   - **Resumen estadístico**: indicadores, análisis, comparativos, evolución semanal y responsables.
   - **Seguimiento de radicados**: búsqueda, filtros, detalle de cada PQRSD y exportación a CSV.
4. **Generar reporte** arma el informe con el análisis de cada vicepresidencia y dependencia; se puede imprimir, guardar como PDF o descargar en HTML.

**Guardar copia con datos** descarga el tablero con la base ya incluida en un solo archivo HTML, para compartirlo o abrirlo sin volver a cargar el CSV.

## Datos personales

La base contiene nombres y teléfonos de peticionarios. El archivo se procesa únicamente en el navegador y no se envía a ningún servidor. Este repositorio es público: no suba a él el CSV ni una copia del tablero con datos.

## Nota sobre los radicados

Si el CSV se guarda desde Excel con la columna «Radicado» en formato numérico, los radicados quedan en notación científica (`2,02641E+13`) y no se pueden distinguir. Para conservarlos, dé formato de texto a esa columna antes de exportar. Cuando llegan así, el tablero identifica cada PQRSD por su número de fila en el archivo.
