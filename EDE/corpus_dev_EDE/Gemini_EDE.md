## Gemini

### Corpus de desarrollo

**Tabla. Reporte de clasificación — Gemini solo prompt sin ejemplos**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.9054 | 0.9805 | 0.9415 | 205 |
| 1 | 0.7647 | 0.3824 | 0.5098 | 34 |
| **Accuracy** |  |  | **0.8954** | 239 |
| **Macro avg** | 0.8351 | 0.6814 | 0.7256 | 239 |
| **Weighted avg** | 0.8854 | 0.8954 | 0.8800 | 239 |

**Tabla. Matriz de confusión — Gemini solo prompt sin ejemplos**

| Etiqueta real | Pred 0 | Pred 1 |
|---|---:|---:|
| Real 0 | 201 | 4 |
| Real 1 | 21 | 13 |

**Tabla. Reporte de clasificación — Gemini + kNN, 3 ejemplos por clase**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.9213 | 0.9707 | 0.9454 | 205 |
| 1 | 0.7391 | 0.5000 | 0.5965 | 34 |
| **Accuracy** |  |  | **0.9038** | 239 |
| **Macro avg** | 0.8302 | 0.7354 | 0.7709 | 239 |
| **Weighted avg** | 0.8954 | 0.9038 | 0.8957 | 239 |

**Tabla. Matriz de confusión — Gemini + kNN, 3 ejemplos por clase**

| Etiqueta real | Pred 0 | Pred 1 |
|---|---:|---:|
| Real 0 | 199 | 6 |
| Real 1 | 17 | 17 |
