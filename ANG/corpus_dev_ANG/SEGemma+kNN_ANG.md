

### Corpus de desarrollo

**Tabla. Reporte de clasificación usando Sentence Embeddings Gemma con kNN (k = 5)**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.92 | 0.96 | 0.94 | 204 |
| 1 | 0.70 | 0.54 | 0.61 | 35 |
| **Accuracy** |  |  | **0.90** | 239 |
| **Macro avg** | 0.81 | 0.75 | 0.78 | 239 |
| **Weighted avg** | 0.89 | 0.90 | 0.89 | 239 |

**Tabla. Matriz de confusión usando Sentence Embeddings Gemma con kNN (k = 5)**

| Etiqueta real | Pred 0 | Pred 1 |
|---|---:|---:|
| Real 0 | 196 | 8 |
| Real 1 | 16 | 19 |
