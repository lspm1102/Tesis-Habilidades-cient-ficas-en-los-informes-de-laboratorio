
### Corpus desarrollo

**Tabla. Reporte de clasificación Gemini sin ejemplos **

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.9087 | 0.9265 | 0.9175 | 204 |
| 1 | 0.5161 | 0.4571 | 0.4848 | 35 |
| **Accuracy** |  |  | **0.8577** | 239 |
| **Macro avg** | 0.7124 | 0.6918 | 0.7012 | 239 |
| **Weighted avg** | 0.8512 | 0.8577 | 0.8541 | 239 |

**Tabla. Matriz de confusión Gemini sin ejemplos**

| Etiqueta real | Pred 0 | Pred 1 |
|---|---:|---:|
| Real 0 | 189 | 15 |
| Real 1 | 19 | 16 |

Resultados con **SE Gemma KNN 3** y prompt.

**Tabla. Reporte de clasificación Gemini SE Gemma KNN 3 y prompt **

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.93 | 0.96 | 0.95 | 204 |
| 1 | 0.72 | 0.60 | 0.66 | 35 |
| **Accuracy** |  |  | **0.91** | 239 |
| **Macro avg** | 0.83 | 0.78 | 0.80 | 239 |
| **Weighted avg** | 0.90 | 0.91 | 0.90 | 239 |

**Tabla. Matriz de confusión Gemini SE Gemma KNN 3 **

| Etiqueta real | Predicho 0 | Predicho 1 |
|---|---:|---:|
| Real 0 | 196 | 8 |
| Real 1 | 14 | 21 |
