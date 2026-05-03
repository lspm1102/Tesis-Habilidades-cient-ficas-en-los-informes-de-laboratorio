Se probó **SE Gemma con KNN**, utilizando **1, 3 y 5 vecinos**. Se optó por **k = 5**, ya que presentó el mejor desempeño en las métricas evaluadas.

**Tabla. Reporte de clasificación DEV SE Gemma KNN 5**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.95 | 0.96 | 0.96 | 210 |
| 1 | 0.69 | 0.62 | 0.65 | 29 |
| **Accuracy** |  |  | **0.92** | 239 |
| **Macro avg** | 0.82 | 0.79 | 0.80 | 239 |
| **Weighted avg** | 0.92 | 0.92 | 0.92 | 239 |

**Tabla. Matriz de confusión DEV SE Gemma KNN 5**

| Etiqueta real | Predicho 1 | Predicho 0 |
|---|---:|---:|
| 1 | 18 | 11 |
| 0 | 8 | 202 |
