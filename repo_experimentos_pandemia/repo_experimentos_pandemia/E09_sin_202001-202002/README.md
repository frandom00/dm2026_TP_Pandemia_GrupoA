# E09 · Sin ene-2020 y feb-2020

**Familia:** F3 · Pre-cuarentena
**Meses excluidos del training y del final_train:** 202001 a 202002 (2 meses)

Saca enero y febrero de 2020, cuando China ya había hecho la primera cuarentena del mundo.

## Resultado

| Ganancia promedio | Δ vs. todos los meses | Semillas en las que supera al baseline | Mín | Máx | Corridas |
|---|---|---|---|---|---|
| **69.710** | −1,0% | 4 / 10 | 62.222 | 79.667 | 29 |

El detalle de cada submit está en [`resultados.csv`](resultados.csv).

## Cómo correrlo

1. Abrir `orquestador_semillas.ipynb` con el kernel de **R** desde esta carpeta.
2. Correr todas las celdas: el orquestador ejecuta `z620_WorkFlow_01_junior_grupoA11.ipynb` una vez por semilla, cambiando `PARAM$semilla_primigenia` y `PARAM$experimento`.
3. Cada corrida genera `kaggle/KA<experimento>_<envios>.csv` para 1.800, 2.100 y 2.400 envíos y los sube a Kaggle.

| Semilla | Experimento | Archivos que genera |
|---|---|---|
| 111119 | WF9154 | `KA9154_1800.csv`, `_2100.csv`, `_2400.csv` |
| 333337 | WF9155 | `KA9155_1800.csv`, `_2100.csv`, `_2400.csv` |
| 444443 | WF9156 | `KA9156_1800.csv`, `_2100.csv`, `_2400.csv` |
| 555557 | WF9157 | `KA9157_1800.csv`, `_2100.csv`, `_2400.csv` |
| 666667 | WF9158 | `KA9158_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100519 | WF9159 | `KA9159_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100523 | WF9160 | `KA9160_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100537 | WF9161 | `KA9161_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100549 | WF9162 | `KA9162_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100547 | WF9163 | `KA9163_1800.csv`, `_2100.csv`, `_2400.csv` |
