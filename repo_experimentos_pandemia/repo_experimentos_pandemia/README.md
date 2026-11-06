# Utilización de los meses de pandemia · Training Strategy

Problema #04 · Data Mining, edición 2026 · Maestría en Ciencia de Datos, ITBA
Grupo A: Carolina Blanco y Francisco Dominguez

¿Conviene entrenar con los meses de pandemia para predecir qué clientes se dan de baja del banco (BAJA+2)? Este repo tiene todo lo necesario para replicar los 11 experimentos: en cada uno cambia qué meses de pandemia se sacan del entrenamiento.

**Ganador: E04, sin mar-2020 a mar-2021**, con una ganancia promedio de 78.092 (+10,9% contra entrenar con todos los meses). Supera al baseline en las 10 semillas.

## Experimentos

| Carpeta | Meses excluidos | Familia | Ganancia promedio | Δ vs. todos | Semillas que gana |
|---|---|---|---|---|---|
| [`E00_todos_los_meses`](E00_todos_los_meses/) | ninguno (baseline) | Baseline | 70.421 | — | — |
| [`E01_sin_202006-202011`](E01_sin_202006-202011/) | 202006 a 202011 (6 meses) | F1 · Bloque pandemia | 70.911 | +0,7% | 6 / 10 |
| [`E02_sin_202003-202011`](E02_sin_202003-202011/) | 202003 a 202011 (9 meses) | F1 · Bloque pandemia | 71.396 | +1,4% | 8 / 10 |
| [`E03_sin_202003-202012`](E03_sin_202003-202012/) | 202003 a 202012 (10 meses) | F1 · Bloque pandemia | 73.456 | +4,3% | 9 / 10 |
| [`E04_sin_202003-202103`](E04_sin_202003-202103/) | 202003 a 202103 (13 meses) | F1 · Bloque pandemia | **78.092** ★ | +10,9% | 10 / 10 |
| [`E05_sin_202003`](E05_sin_202003/) | 202003 (1 mes) | F2 · Shock inicial | 70.895 | +0,7% | 8 / 10 |
| [`E06_sin_202004`](E06_sin_202004/) | 202004 (1 mes) | F2 · Shock inicial | 71.039 | +0,9% | 6 / 10 |
| [`E07_sin_202003-202004`](E07_sin_202003-202004/) | 202003 a 202004 (2 meses) | F2 · Shock inicial | 69.840 | −0,8% | 3 / 10 |
| [`E08_sin_202002`](E08_sin_202002/) | 202002 (1 mes) | F3 · Pre-cuarentena | 69.997 | −0,6% | 5 / 10 |
| [`E09_sin_202001-202002`](E09_sin_202001-202002/) | 202001 a 202002 (2 meses) | F3 · Pre-cuarentena | 69.710 | −1,0% | 4 / 10 |
| [`E10_sin_202001-202005`](E10_sin_202001-202005/) | 202001 a 202005 (5 meses) | F3 · Pre-cuarentena | 67.810 | −3,7% | 1 / 10 |

Ganancia promedio de 30 submits a Kaggle por experimento (10 semillas × 3 cortes de envíos).

## Estrategia común a todos los experimentos

* **Dataset:** `analistajr_competencia_2026.csv.gz` (se lee desde `/content/datasets/`).
* **Modelo:** LightGBM con hiperparámetros optimizados (Optimización Bayesiana del workflow).
* **Meses candidatos:** de 201901 a 202105 para `training` y `final_train`; a esa lista se le restan los meses del experimento.
* **Validación:** 202107. **Futuro:** 202109.
* **Semillas:** 111119, 333337, 444443, 555557, 666667, 100519, 100523, 100537, 100549, 100547.
* **Cortes de envíos:** 1.800, 2.100 y 2.400.

## Cómo replicar

1. **Requisitos:** Ambos archivos (orquestador y notebook "padre") deben estar en la misma carpeta. Actualizar sus semillas en el notebook orquestador y correr las 3 celdas.