#### Corpus de test

Los resultados obtenidos con LLaMA sobre el corpus de test, utilizando un prompt con ejemplos seleccionados manualmente, se presentan en la siguiente tabla.

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.94 | 0.90 | 0.92 | 205 |
| 1 | 0.53 | 0.69 | 0.60 | 35 |
| **Accuracy** |  |  | **0.87** | 240 |
| **Macro avg** | 0.74 | 0.79 | 0.76 | 240 |
| **Weighted avg** | 0.88 | 0.87 | 0.87 | 240 |

**Tabla.** Evaluación de LLaMA sobre el corpus TEST, utilizando un prompt con ejemplos seleccionados manualmente: reporte de clasificación.

La matriz de confusión correspondiente se presenta a continuación.

| Etiqueta real | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 184 | 21 |
| Real 1 | 11 | 24 |

**Tabla.** Evaluación de LLaMA sobre el corpus TEST, utilizando un prompt con ejemplos seleccionados manualmente: matriz de confusión.
