# E06 · Sin abr-2020

**Familia:** F2 · Shock inicial
**Meses excluidos del training y del final_train:** 202004 (1 mes)

Saca solo el primer mes completo de cuarentena.

## Resultado

| Ganancia promedio | Δ vs. todos los meses | Semillas en las que supera al baseline | Mín | Máx | Corridas |
|---|---|---|---|---|---|
| **71.039** | +0,9% | 6 / 10 | 61.640 | 79.833 | 30 |

El detalle de cada submit está en [`resultados.csv`](resultados.csv).

## Cómo correrlo

1. Abrir `orquestador_semillas.ipynb` con el kernel de **R** desde esta carpeta.
2. Correr todas las celdas: el orquestador ejecuta `z620_WorkFlow_01_junior_grupoA11.ipynb` una vez por semilla, cambiando `PARAM$semilla_primigenia` y `PARAM$experimento`.
3. Cada corrida genera `kaggle/KA<experimento>_<envios>.csv` para 1.800, 2.100 y 2.400 envíos y los sube a Kaggle.

| Semilla | Experimento | Archivos que genera |
|---|---|---|
| 111119 | WF9224 | `KA9224_1800.csv`, `_2100.csv`, `_2400.csv` |
| 333337 | WF9225 | `KA9225_1800.csv`, `_2100.csv`, `_2400.csv` |
| 444443 | WF9226 | `KA9226_1800.csv`, `_2100.csv`, `_2400.csv` |
| 555557 | WF9227 | `KA9227_1800.csv`, `_2100.csv`, `_2400.csv` |
| 666667 | WF9228 | `KA9228_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100519 | WF9229 | `KA9229_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100523 | WF9230 | `KA9230_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100537 | WF9231 | `KA9231_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100549 | WF9232 | `KA9232_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100547 | WF9233 | `KA9233_1800.csv`, `_2100.csv`, `_2400.csv` |