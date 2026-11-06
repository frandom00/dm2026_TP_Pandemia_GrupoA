# E07 · Sin mar-2020 y abr-2020

**Familia:** F2 · Shock inicial
**Meses excluidos del training y del final_train:** 202003 a 202004 (2 meses)

Saca los dos primeros meses de la cuarentena.

## Resultado

| Ganancia promedio | Δ vs. todos los meses | Semillas en las que supera al baseline | Mín | Máx | Corridas |
|---|---|---|---|---|---|
| **69.840** | −0,8% | 3 / 10 | 61.308 | 75.929 | 30 |

El detalle de cada submit está en [`resultados.csv`](resultados.csv).

## Cómo correrlo

1. Abrir `orquestador_semillas.ipynb` con el kernel de **R** desde esta carpeta.
2. Correr todas las celdas: el orquestador ejecuta `z620_WorkFlow_01_junior_grupoA11.ipynb` una vez por semilla, cambiando `PARAM$semilla_primigenia` y `PARAM$experimento`.
3. Cada corrida genera `kaggle/KA<experimento>_<envios>.csv` para 1.800, 2.100 y 2.400 envíos y los sube a Kaggle.

| Semilla | Experimento | Archivos que genera |
|---|---|---|
| 111119 | WF9214 | `KA9214_1800.csv`, `_2100.csv`, `_2400.csv` |
| 333337 | WF9215 | `KA9215_1800.csv`, `_2100.csv`, `_2400.csv` |
| 444443 | WF9216 | `KA9216_1800.csv`, `_2100.csv`, `_2400.csv` |
| 555557 | WF9217 | `KA9217_1800.csv`, `_2100.csv`, `_2400.csv` |
| 666667 | WF9218 | `KA9218_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100519 | WF9219 | `KA9219_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100523 | WF9220 | `KA9220_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100537 | WF9221 | `KA9221_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100549 | WF9222 | `KA9222_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100547 | WF9223 | `KA9223_1800.csv`, `_2100.csv`, `_2400.csv` |
