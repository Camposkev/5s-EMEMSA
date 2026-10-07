# 5S EMEMSA

Apps web para la inspección 5S (auditor) y el levantamiento de observaciones (facilitador), con el formato E-FSIG 022.

- `index.html`: página de inicio con acceso a las dos apps.
- `inspeccion.html`: reporte de inspección (ANTES).
- `levantamiento.html`: levantamiento de observaciones (DESPUÉS).
- `sw.js`: permite usar las apps sin señal después de abrirlas una vez.

Los datos, fotos y reportes se procesan y guardan solo en el dispositivo de cada usuario. No se envían a ningún servidor.

## Publicar una actualización

1. Reemplaza el archivo `.html` modificado en el repositorio.
2. En `sw.js`, sube la versión (por ejemplo `ememsa-5s-v1` → `ememsa-5s-v2`) para que los celulares descarguen la versión nueva.

Dudas o sugerencias: auxiliar5s@ememsa.pe
