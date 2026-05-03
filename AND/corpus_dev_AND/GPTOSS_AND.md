## GPT OSS

### Corpus desarrollo

Con **kNN = 3 por clase**, **SE E5** y **prompt dinámico**.

**Tabla. Reporte de clasificación por clase — GPT-OSS Corpus DEV, kNN = 3**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.88 | 0.88 | 0.88 | 184 |
| 1 | 0.59 | 0.58 | 0.59 | 55 |
| **Accuracy** |  |  | **0.81** | 239 |
| **Macro avg** | 0.73 | 0.73 | 0.73 | 239 |
| **Weighted avg** | 0.81 | 0.81 | 0.81 | 239 |

**Tabla. Matriz de confusión — GPT-OSS Corpus DEV, kNN = 3**

| Etiqueta real | Predicha 0 | Predicha 1 |
|---|---:|---:|
| 0 | 162 | 22 |
| 1 | 23 | 32 |
