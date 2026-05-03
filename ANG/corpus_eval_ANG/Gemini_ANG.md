
### Corpus test

**Tabla. Reporte de clasificación TEST usando Gemini, con ejemplos seleccionados mediante kNN (k = 3)**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.94 | 0.92 | 0.93 | 205 |
| 1 | 0.59 | 0.66 | 0.62 | 35 |
| **Accuracy** |  |  | **0.88** | 240 |
| **Macro avg** | 0.77 | 0.79 | 0.78 | 240 |
| **Weighted avg** | 0.89 | 0.88 | 0.89 | 240 |

**Tabla. Matriz de confusión TEST usando Gemini, con ejemplos seleccionados mediante kNN (k = 3)**

| Etiqueta real | Pred 0 | Pred 1 |
|---|---:|---:|
| Real 0 | 189 | 16 |
| Real 1 | 12 | 23 |
