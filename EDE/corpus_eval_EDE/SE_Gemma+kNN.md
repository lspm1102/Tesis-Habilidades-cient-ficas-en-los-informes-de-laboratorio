#### Corpus de test

Los resultados obtenidos con SE-Gemma sobre el corpus de test, utilizando kNN con \(k=5\), se presentan en la siguiente tabla.

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.93 | 0.98 | 0.95 | 205 |
| 1 | 0.83 | 0.54 | 0.66 | 35 |
| **Accuracy** |  |  | **0.92** | 240 |
| **Macro avg** | 0.88 | 0.76 | 0.80 | 240 |
| **Weighted avg** | 0.91 | 0.92 | 0.91 | 240 |

**Tabla.** Evaluación de SE-Gemma sobre el corpus TEST, utilizando kNN con \(k=5\): reporte de clasificación.

La matriz de confusión correspondiente se presenta a continuación.

| Etiqueta real | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 201 | 4 |
| Real 1 | 16 | 19 |

**Tabla.** Evaluación de SE-Gemma sobre el corpus TEST, utilizando kNN con \(k=5\): matriz de confusión.
