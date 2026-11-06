# E02 · Sin mar-2020 a nov-2020

**Familia:** F1 · Bloque pandemia
**Meses excluidos del training y del final_train:** 202003 a 202011 (9 meses)

Saca el período ASPO completo en el AMBA (del 20-mar-2020 al 8-nov-2020).

## Resultado

| Ganancia promedio | Δ vs. todos los meses | Semillas en las que supera al baseline | Mín | Máx | Corridas |
|---|---|---|---|---|---|
| **71.396** | +1,4% | 8 / 10 | 62.720 | 77.341 | 30 |

El detalle de cada submit está en [`resultados.csv`](resultados.csv).

## Cómo correrlo

1. Abrir `orquestador_semillas.ipynb` con el kernel de **R** desde esta carpeta.
2. Correr todas las celdas: el orquestador ejecuta `z620_WorkFlow_01_junior_grupoA11.ipynb` una vez por semilla, cambiando `PARAM$semilla_primigenia` y `PARAM$experimento`.
3. Cada corrida genera `kaggle/KA<experimento>_<envios>.csv` para 1.800, 2.100 y 2.400 envíos y los sube a Kaggle.

| Semilla | Experimento | Archivos que genera |
|---|---|---|
| 111119 | WF9244 | `KA9244_1800.csv`, `_2100.csv`, `_2400.csv` |
| 333337 | WF9245 | `KA9245_1800.csv`, `_2100.csv`, `_2400.csv` |
| 444443 | WF9246 | `KA9246_1800.csv`, `_2100.csv`, `_2400.csv` |
| 555557 | WF9247 | `KA9247_1800.csv`, `_2100.csv`, `_2400.csv` |
| 666667 | WF9248 | `KA9248_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100519 | WF9249 | `KA9249_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100523 | WF9250 | `KA9250_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100537 | WF9251 | `KA9251_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100549 | WF9252 | `KA9252_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100547 | WF9253 | `KA9253_1800.csv`, `_2100.csv`, `_2400.csv` |
