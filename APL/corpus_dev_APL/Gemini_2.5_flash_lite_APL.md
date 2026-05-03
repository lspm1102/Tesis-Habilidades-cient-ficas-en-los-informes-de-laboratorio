Resultados obtenidos con técnica de *prompting* que incluye ejemplos de cada clase seleccionados manualmente. Se utilizaron cuatro ejemplos: dos de cada clase.

### Reporte de clasificación — Gemini 2.5 Flash Lite, Few Shot manual

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.9340 | 0.9246 | 0.9293 | 199 |
| 1 | 0.6429 | 0.6750 | 0.6585 | 40 |
| **Accuracy** |  |  | 0.8828 | 239 |
| **Macro avg** | 0.7884 | 0.7998 | 0.7939 | 239 |
| **Weighted avg** | 0.8853 | 0.8828 | 0.8840 | 239 |

### Matriz de confusión

| Etiqueta real | Pred 0 | Pred 1 |
|---|---:|---:|
| Real 0 | 184 | 15 |
| Real 1 | 13 | 27 |



### Reporte de clasificación — Gemini con ejemplos seleccionados mediante EmbeddingGemma + kNN con k=3, seleccionando 3 por clase

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.93 | 0.95 | 0.94 | 199 |
| 1 | 0.74 | 0.65 | 0.69 | 40 |
| **Accuracy** |  |  | 0.90 | 239 |
| **Macro avg** | 0.84 | 0.80 | 0.82 | 239 |
| **Weighted avg** | 0.90 | 0.90 | 0.90 | 239 |

### Matriz de confusión

| Etiqueta real | Predicho 0 | Predicho 1 |
|---|---:|---:|
| Real 0 | 190 | 9 |
| Real 1 | 14 | 26 |
