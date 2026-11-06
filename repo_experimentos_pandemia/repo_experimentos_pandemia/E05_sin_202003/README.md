# E05 · Sin mar-2020

**Familia:** F2 · Shock inicial
**Meses excluidos del training y del final_train:** 202003 (1 mes)

Saca solo el primer mes de la cuarentena.

## Resultado

| Ganancia promedio | Δ vs. todos los meses | Semillas en las que supera al baseline | Mín | Máx | Corridas |
|---|---|---|---|---|---|
| **70.895** | +0,7% | 8 / 10 | 61.806 | 77.092 | 30 |

El detalle de cada submit está en [`resultados.csv`](resultados.csv).

## Cómo correrlo

1. Abrir `orquestador_semillas.ipynb` con el kernel de **R** desde esta carpeta.
2. Correr todas las celdas: el orquestador ejecuta `z620_WorkFlow_01_junior_grupoA11.ipynb` una vez por semilla, cambiando `PARAM$semilla_primigenia` y `PARAM$experimento`.
3. Cada corrida genera `kaggle/KA<experimento>_<envios>.csv` para 1.800, 2.100 y 2.400 envíos y los sube a Kaggle.

| Semilla | Experimento | Archivos que genera |
|---|---|---|
| 111119 | WF9204 | `KA9204_1800.csv`, `_2100.csv`, `_2400.csv` |
| 333337 | WF9205 | `KA9205_1800.csv`, `_2100.csv`, `_2400.csv` |
| 444443 | WF9206 | `KA9206_1800.csv`, `_2100.csv`, `_2400.csv` |
| 555557 | WF9207 | `KA9207_1800.csv`, `_2100.csv`, `_2400.csv` |
| 666667 | WF9208 | `KA9208_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100519 | WF9209 | `KA9209_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100523 | WF9210 | `KA9210_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100537 | WF9211 | `KA9211_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100549 | WF9212 | `KA9212_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100547 | WF9213 | `KA9213_1800.csv`, `_2100.csv`, `_2400.csv` |

