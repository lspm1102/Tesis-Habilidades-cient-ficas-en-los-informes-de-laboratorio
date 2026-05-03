## GPT OSS

### Corpus de desarrollo

**Tabla. Reporte de clasificación CORPUS DEV usando GPT OSS solo prompt**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| Clase 0 | 0.93 | 0.95 | 0.94 | 203 |
| Clase 1 | 0.68 | 0.60 | 0.64 | 35 |
| **Accuracy** |  |  | **0.90** | 238 |
| **Macro avg** | 0.80 | 0.78 | 0.79 | 238 |
| **Weighted avg** | 0.89 | 0.90 | 0.90 | 238 |

**Tabla. Matriz de confusión CORPUS DEV usando GPT OSS solo prompt**

| Etiqueta real | Pred 0 | Pred 1 |
|---|---:|---:|
| Real 0 | 193 | 10 |
| Real 1 | 14 | 21 |

Los resultados usando tres ejemplos de cada clase, prompt dinámico con **kNN = 3**, fueron los siguientes.

**Tabla. Reporte de clasificación CORPUS DEV usando GPT OSS, con ejemplos seleccionados mediante kNN (k = 3; 3 ejemplos de cada clase)**

| Clase | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| Clase 0 | 0.94 | 0.96 | 0.95 | 204 |
| Clase 1 | 0.71 | 0.63 | 0.67 | 35 |
| **Accuracy** |  |  | **0.91** | 239 |
| **Macro avg** | 0.82 | 0.79 | 0.81 | 239 |
| **Weighted avg** | 0.90 | 0.91 | 0.91 | 239 |

**Tabla. Matriz de confusión CORPUS DEV usando GPT OSS, con ejemplos seleccionados mediante kNN (k = 3; 3 ejemplos de cada clase)**

| Etiqueta real | Pred Clase 0 | Pred Clase 1 |
|---|---:|---:|
| Clase 0 | 195 | 9 |
| Clase 1 | 13 | 22 |
