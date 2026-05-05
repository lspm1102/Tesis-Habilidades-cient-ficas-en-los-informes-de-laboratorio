## Sentence Embeddings

#### Corpus de desarrollo

Los resultados obtenidos con SE-Gemma sobre el corpus de desarrollo, utilizando kNN con \(k=5\), se presentan en la siguiente tabla.

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.93 | 0.99 | 0.96 | 205 |
| 1 | 0.86 | 0.56 | 0.68 | 34 |
| **Accuracy** |  |  | **0.92** | 239 |
| **Macro avg** | 0.90 | 0.77 | 0.82 | 239 |
| **Weighted avg** | 0.92 | 0.92 | 0.92 | 239 |

**Tabla.** Evaluación de SE-Gemma sobre el corpus DEV, utilizando kNN con \(k=5\): reporte de clasificación.

La matriz de confusión correspondiente se presenta a continuación.

| Etiqueta real | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 202 | 3 |
| Real 1 | 15 | 19 |

**Tabla.** Evaluación de SE-Gemma sobre el corpus DEV, utilizando kNN con \(k=5\): matriz de confusión.
