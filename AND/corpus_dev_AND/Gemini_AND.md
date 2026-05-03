
**Tabla. Reporte de clasificación usando Gemini 2.5 FLash lite, con 3 ejemplos por clase seleccionados mediante kNN en el espacio de embeddings SE Gemma**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| Clase 0 | 0.90 | 0.76 | 0.82 | 184 |
| Clase 1 | 0.47 | 0.73 | 0.57 | 55 |
| **Accuracy** |  |  | **0.70** | 239 |
| **Macro avg** | 0.67 | 0.74 | 0.66 | 239 |
| **Weighted avg** | 0.80 | 0.70 | 0.72 | 239 |

**Tabla. Matriz de confusión**

| Etiqueta real | Pred 0 | Pred 1 |
|---|---:|---:|
| Real 0 | 139 | 45 |
| Real 1 | 15 | 40 |
