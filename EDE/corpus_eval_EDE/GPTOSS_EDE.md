### Corpus de test

Los resultados obtenidos con GPT-OSS sobre el corpus de test, utilizando kNN con \(k=3\), se presentan en la siguiente tabla.

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.98 | 0.88 | 0.93 | 205 |
| 1 | 0.56 | 0.89 | 0.67 | 35 |
| **Accuracy** |  |  | **0.88** | 240 |
| **Macro avg** | 0.77 | 0.88 | 0.81 | 240 |
| **Weighted avg** | 0.92 | 0.88 | 0.89 | 240 |

**Tabla.** Evaluación de GPT-OSS sobre el corpus TEST, utilizando kNN con \(k=3\): reporte de clasificación.

La matriz de confusión correspondiente se presenta a continuación.

| Etiqueta real | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 181 | 24 |
| Real 1 | 4 | 31 |

**Tabla.** Evaluación de GPT-OSS sobre el corpus TEST, utilizando kNN con \(k=3\): matriz de confusión.
