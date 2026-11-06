# E00 · Todos los meses (baseline)

**Familia:** Baseline
**Meses excluidos del training y del final_train:** ninguno

Referencia: se entrena con todos los meses disponibles, sin sacar nada por la pandemia.

## Resultado

| Ganancia promedio | Δ vs. todos los meses | Semillas en las que supera al baseline | Mín | Máx | Corridas |
|---|---|---|---|---|---|
| **70.421** | — | — | 61.640 | 77.009 | 30 |

El detalle de cada submit está en [`resultados.csv`](resultados.csv).

## Cómo correrlo

1. Abrir `orquestador_semillas.ipynb` con el kernel de **R** desde esta carpeta.
2. Correr todas las celdas: el orquestador ejecuta `z620_WorkFlow_01_junior_grupoA11.ipynb` una vez por semilla, cambiando `PARAM$semilla_primigenia` y `PARAM$experimento`.
3. Cada corrida genera `kaggle/KA<experimento>_<envios>.csv` para 1.800, 2.100 y 2.400 envíos y los sube a Kaggle.

| Semilla | Experimento | Archivos que genera |
|---|---|---|
| 111119 | WF9144 | `KA9144_1800.csv`, `_2100.csv`, `_2400.csv` |
| 333337 | WF9145 | `KA9145_1800.csv`, `_2100.csv`, `_2400.csv` |
| 444443 | WF9146 | `KA9146_1800.csv`, `_2100.csv`, `_2400.csv` |
| 555557 | WF9147 | `KA9147_1800.csv`, `_2100.csv`, `_2400.csv` |
| 666667 | WF9148 | `KA9148_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100519 | WF9149 | `KA9149_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100523 | WF9150 | `KA9150_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100537 | WF9151 | `KA9151_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100549 | WF9152 | `KA9152_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100547 | WF9153 | `KA9153_1800.csv`, `_2100.csv`, `_2400.csv` |
