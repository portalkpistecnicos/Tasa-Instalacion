# Tasa de Instalación · ELECNOR

Dashboard de tasa de instalación (Completadas / (Completadas + Canceladas)) por agencia zonal,
generado a partir de las bases TOA descargadas diariamente.

- `index.html` — dashboard (tarjetas por agencia, evolución diaria, detalle).
- `data/historico.csv` / `data/historico.json` — histórico acumulado, un registro por día y agencia.
- `assets/logo-elecnor.png` — logo corporativo.

Este repositorio solo contiene datos **agregados** (conteos y tasas). No incluye información
personal de clientes ni las bases crudas de origen.

Se actualiza con el script `Actualizar_Tasa_Instalacion.ps1` ubicado en la carpeta local
`KPI's\Tasa de Instalación`, que lee el último archivo TOA de `BBDD`, recalcula las tasas y publica
los cambios aquí.
