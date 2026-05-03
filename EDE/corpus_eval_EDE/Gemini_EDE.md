
### Corpus de test

**Tabla. Reporte de clasificación — Gemini 2.5 Flash lite, con proomt dinámico, con tres ejémplos por clase, oobtenidos con SE Gemma + kNN**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.95 | 0.93 | 0.94 | 205 |
| 1 | 0.63 | 0.74 | 0.68 | 35 |
| **Accuracy** |  |  | **0.90** | 240 |
| **Macro avg** | 0.79 | 0.83 | 0.81 | 240 |
| **Weighted avg** | 0.91 | 0.90 | 0.90 | 240 |

**Tabla. Matriz de confusión — Código EDE, Corpus TEST, Gemini + kNN = 3**

| Etiqueta real | Pred 0 | Pred 1 |
|---|---:|---:|
| Real 0 | 190 | 15 |
| Real 1 | 9 | 26 |
