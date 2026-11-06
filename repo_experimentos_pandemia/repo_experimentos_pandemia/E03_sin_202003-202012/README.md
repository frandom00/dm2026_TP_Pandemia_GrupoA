# E03 · Sin mar-2020 a dic-2020

**Familia:** F1 · Bloque pandemia
**Meses excluidos del training y del final_train:** 202003 a 202012 (10 meses)

Saca todo 2020 desde el inicio del ASPO, incluido diciembre, ya en DISPO.

## Resultado

| Ganancia promedio | Δ vs. todos los meses | Semillas en las que supera al baseline | Mín | Máx | Corridas |
|---|---|---|---|---|---|
| **73.456** | +4,3% | 9 / 10 | 65.545 | 80.415 | 30 |

El detalle de cada submit está en [`resultados.csv`](resultados.csv).

## Cómo correrlo

1. Abrir `orquestador_semillas.ipynb` con el kernel de **R** desde esta carpeta.
2. Correr todas las celdas: el orquestador ejecuta `z620_WorkFlow_01_junior_grupoA11.ipynb` una vez por semilla, cambiando `PARAM$semilla_primigenia` y `PARAM$experimento`.
3. Cada corrida genera `kaggle/KA<experimento>_<envios>.csv` para 1.800, 2.100 y 2.400 envíos y los sube a Kaggle.

| Semilla | Experimento | Archivos que genera |
|---|---|---|
| 111119 | WF9174 | `KA9174_1800.csv`, `_2100.csv`, `_2400.csv` |
| 333337 | WF9175 | `KA9175_1800.csv`, `_2100.csv`, `_2400.csv` |
| 444443 | WF9176 | `KA9176_1800.csv`, `_2100.csv`, `_2400.csv` |
| 555557 | WF9177 | `KA9177_1800.csv`, `_2100.csv`, `_2400.csv` |
| 666667 | WF9178 | `KA9178_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100519 | WF9179 | `KA9179_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100523 | WF9180 | `KA9180_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100537 | WF9181 | `KA9181_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100549 | WF9182 | `KA9182_1800.csv`, `_2100.csv`, `_2400.csv` |
| 100547 | WF9183 | `KA9183_1800.csv`, `_2100.csv`, `_2400.csv` |
