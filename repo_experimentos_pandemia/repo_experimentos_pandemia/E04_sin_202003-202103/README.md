# E04 · Sin mar-2020 a mar-2021  ★ ganador

**Familia:** F1 · Bloque pandemia
**Meses excluidos del training y del final_train:** 202003 a 202103 (13 meses)

Saca el ASPO completo y los primeros meses del DISPO, hasta marzo de 2021.

## Resultado

| Ganancia promedio | Δ vs. todos los meses | Semillas en las que supera al baseline | Mín | Máx | Corridas |
|---|---|---|---|---|---|
| **78.092** | +10,9% | 10 / 10 | 68.203 | 86.313 | 30 |

El detalle de cada submit está en [`resultados.csv`](resultados.csv).

## Cómo correrlo

1. Abrir `orquestador_semillas.ipynb` con el kernel de **R** desde esta carpeta.
2. Correr todas las celdas: el orquestador ejecuta `z620_WorkFlow_01_junior_grupoA11.ipynb` una vez por semilla, cambiando `PARAM$semilla_primigenia` y `PARAM$experimento`.
3. Cada corrida genera `kaggle/KA<experimento>_<envios>.csv` para 1.800, 2.100 y 2.400 envíos y los sube a Kaggle.

| Semilla | Experimento | Archivos que genera |
|---|---|---|
| 111119 | WF9194 | `KA9194_1800.csv`, `_2100.csv`, `_2400.csv` |
| 333337 | WF9195 | `KA9195_1800.csv`, `_2100.csv`, `_2400.csv` |
| 444443 | WF9196 | `KA9196_1800.csv`, `_2100.csv`, `_2400.csv` |
| 555557 | WF9197 | `KA9197_1800.csv`, `_2100.csv`, `_2400.csv` |
| 666667 | WF9198 | `KA9198_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100519 | WF9199 | `KA9199_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100523 | WF9200 | `KA9200_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100537 | WF9201 | `KA9201_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100549 | WF9202 | `KA9202_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100547 | WF9203 | `KA9203_1800.csv`, `_2100.csv`, `_2400.csv` |
