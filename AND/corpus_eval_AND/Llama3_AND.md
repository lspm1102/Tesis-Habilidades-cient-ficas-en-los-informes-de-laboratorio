### Corpus test

**Tabla. Matriz de confusión Llama3 8B insstruct**

| Etiqueta real | Pred 1 | Pred 0 |
|---|---:|---:|
| Real 1 | 38 | 18 |
| Real 0 | 57 | 127 |

El modelo debe ajustarse a respuestas de más de un token, en este caso **5**, dado que, en muy pocos casos, no se limita a responder solo `1` o `0`, sino que responde `RESPONDE 0`. Si la salida está limitada a un token, aparece `RESP` en vez de `1` o `0`.

**Tabla. Reporte de clasificación TEST LLAMA**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.88 | 0.69 | 0.77 | 184 |
| 1 | 0.40 | 0.68 | 0.50 | 56 |
| **Accuracy** |  |  | **0.69** | 240 |
| **Macro avg** | 0.64 | 0.68 | 0.64 | 240 |
| **Weighted avg** | 0.76 | 0.69 | 0.71 | 240 |
