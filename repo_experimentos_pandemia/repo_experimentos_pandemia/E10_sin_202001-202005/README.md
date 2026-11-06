# E10 · Sin ene-2020 a may-2020

**Familia:** F3 · Pre-cuarentena
**Meses excluidos del training y del final_train:** 202001 a 202005 (5 meses)

Saca los meses previos a la cuarentena y los primeros de ASPO, hasta mayo de 2020.

## Resultado

| Ganancia promedio | Δ vs. todos los meses | Semillas en las que supera al baseline | Mín | Máx | Corridas |
|---|---|---|---|---|---|
| **67.810** | −3,7% | 1 / 10 | 58.483 | 77.424 | 30 |

El detalle de cada submit está en [`resultados.csv`](resultados.csv).

## Cómo correrlo

1. Abrir `orquestador_semillas.ipynb` con el kernel de **R** desde esta carpeta.
2. Correr todas las celdas: el orquestador ejecuta `z620_WorkFlow_01_junior_grupoA11.ipynb` una vez por semilla, cambiando `PARAM$semilla_primigenia` y `PARAM$experimento`.
3. Cada corrida genera `kaggle/KA<experimento>_<envios>.csv` para 1.800, 2.100 y 2.400 envíos y los sube a Kaggle.

| Semilla | Experimento | Archivos que genera |
|---|---|---|
| 111119 | WF9184 | `KA9184_1800.csv`, `_2100.csv`, `_2400.csv` |
| 333337 | WF9185 | `KA9185_1800.csv`, `_2100.csv`, `_2400.csv` |
| 444443 | WF9186 | `KA9186_1800.csv`, `_2100.csv`, `_2400.csv` |
| 555557 | WF9187 | `KA9187_1800.csv`, `_2100.csv`, `_2400.csv` |
| 666667 | WF9188 | `KA9188_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100519 | WF9189 | `KA9189_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100523 | WF9190 | `KA9190_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100537 | WF9191 | `KA9191_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100549 | WF9192 | `KA9192_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100547 | WF9193 | `KA9193_1800.csv`, `_2100.csv`, `_2400.csv` |
