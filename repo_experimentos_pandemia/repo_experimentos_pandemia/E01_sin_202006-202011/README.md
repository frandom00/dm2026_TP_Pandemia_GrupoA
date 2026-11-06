# E01 · Sin jun-2020 a nov-2020

**Familia:** F1 · Bloque pandemia
**Meses excluidos del training y del final_train:** 202006 a 202011 (6 meses)

Saca la parte media del ASPO (jun a nov 2020), dejando afuera el shock inicial.

## Resultado

| Ganancia promedio | Δ vs. todos los meses | Semillas en las que supera al baseline | Mín | Máx | Corridas |
|---|---|---|---|---|---|
| **70.911** | +0,7% | 6 / 10 | 62.222 | 76.760 | 30 |

El detalle de cada submit está en [`resultados.csv`](resultados.csv).

## Cómo correrlo

1. Abrir `orquestador_semillas.ipynb` con el kernel de **R** desde esta carpeta.
2. Correr todas las celdas: el orquestador ejecuta `z620_WorkFlow_01_junior_grupoA11.ipynb` una vez por semilla, cambiando `PARAM$semilla_primigenia` y `PARAM$experimento`.
3. Cada corrida genera `kaggle/KA<experimento>_<envios>.csv` para 1.800, 2.100 y 2.400 envíos y los sube a Kaggle.

| Semilla | Experimento | Archivos que genera |
|---|---|---|
| 111119 | WF9234 | `KA9234_1800.csv`, `_2100.csv`, `_2400.csv` |
| 333337 | WF9235 | `KA9235_1800.csv`, `_2100.csv`, `_2400.csv` |
| 444443 | WF9236 | `KA9236_1800.csv`, `_2100.csv`, `_2400.csv` |
| 555557 | WF9237 | `KA9237_1800.csv`, `_2100.csv`, `_2400.csv` |
| 666667 | WF9238 | `KA9238_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100519 | WF9239 | `KA9239_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100523 | WF9240 | `KA9240_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100537 | WF9241 | `KA9241_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100549 | WF9242 | `KA9242_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100547 | WF9243 | `KA9243_1800.csv`, `_2100.csv`, `_2400.csv` |
