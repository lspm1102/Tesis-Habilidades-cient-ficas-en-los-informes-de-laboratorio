Los resultados corresponden al uso de SE Gemma + kNN con tres ejemplos sobre el corpus de test.

### Reporte de clasificación

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.98 | 0.96 | 0.97 | 200 |
| 1 | 0.82 | 0.90 | 0.86 | 40 |
| **Accuracy** |  |  | 0.95 | 240 |
| **Macro avg** | 0.90 | 0.93 | 0.91 | 240 |
| **Weighted avg** | 0.95 | 0.95 | 0.95 | 240 |

### Matriz de confusión

| Etiqueta real | Predicho 0 | Predicho 1 |
|---|---:|---:|
| Real 0 | 192 | 8 |
| Real 1 | 14 | 36 |
