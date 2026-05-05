## LLAMA

#### Corpus de desarrollo

Los resultados obtenidos con LLaMA sobre el corpus de desarrollo se presentan en la siguiente tabla.

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.94 | 0.89 | 0.91 | 205 |
| 1 | 0.50 | 0.68 | 0.57 | 34 |
| **Accuracy** |  |  | **0.86** | 239 |
| **Macro avg** | 0.72 | 0.78 | 0.74 | 239 |
| **Weighted avg** | 0.88 | 0.86 | 0.87 | 239 |

**Tabla.** Evaluación de LLaMA sobre el corpus DEV: reporte de clasificación.

La matriz de confusión correspondiente se presenta a continuación.

| Etiqueta real | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 182 | 23 |
| Real 1 | 11 | 23 |

**Tabla.** Evaluación de LLaMA sobre el corpus DEV: matriz de confusión.
