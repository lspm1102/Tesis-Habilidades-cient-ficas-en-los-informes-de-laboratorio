## GPT OSS

#### Corpus de desarrollo

Los resultados obtenidos con GPT-OSS sobre el corpus de desarrollo, utilizando kNN con \(k=3\), se presentan en la siguiente tabla.

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.97 | 0.89 | 0.93 | 205 |
| 1 | 0.56 | 0.85 | 0.67 | 34 |
| **Accuracy** |  |  | **0.88** | 239 |
| **Macro avg** | 0.77 | 0.87 | 0.80 | 239 |
| **Weighted avg** | 0.91 | 0.88 | 0.89 | 239 |

**Tabla.** Evaluación de GPT-OSS sobre el corpus DEV, utilizando kNN con \(k=3\): reporte de clasificación.

La matriz de confusión correspondiente se presenta a continuación.

| Etiqueta real | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 182 | 23 |
| Real 1 | 5 | 29 |

**Tabla.** Evaluación de GPT-OSS sobre el corpus DEV, utilizando kNN con \(k=3\): matriz de confusión.
