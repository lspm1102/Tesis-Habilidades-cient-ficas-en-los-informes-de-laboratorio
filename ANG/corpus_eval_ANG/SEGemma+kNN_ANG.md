### Corpus test

**Tabla. Reporte de clasificación usando Sentence Embeddings Gemma con kNN (k = 5)**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.94 | 0.92 | 0.93 | 205 |
| 1 | 0.57 | 0.66 | 0.61 | 35 |
| **Accuracy** |  |  | **0.88** | 240 |
| **Macro avg** | 0.76 | 0.79 | 0.77 | 240 |
| **Weighted avg** | 0.89 | 0.88 | 0.88 | 240 |

**Tabla. Matriz de confusión corpus test usando Sentence Embeddings Gemma con kNN (k = 5)**

| Etiqueta real | Pred 0 | Pred 1 |
|---|---:|---:|
| Real 0 | 188 | 17 |
| Real 1 | 12 | 23 |
