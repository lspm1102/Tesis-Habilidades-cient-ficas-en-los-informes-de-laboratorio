

### Reporte de clasificación GPT-OSS sobre el corpus de desarrollo usando solo prompt, sin ejemplos

| Clase | Precisión | Recall | F1-score | Soporte |
|---|---:|---:|---:|---:|
| Clase 0 | 0.90 | 0.96 | 0.93 | 199 |
| Clase 1 | 0.69 | 0.46 | 0.55 | 39 |
| **Accuracy** |  |  | **0.88** | **238** |
| **Macro avg** | **0.80** | **0.71** | **0.74** | **238** |
| **Weighted avg** | **0.87** | **0.88** | **0.87** | **238** |

El total de enunciados clasificados no es de 239 porque el modelo puede en ocasiones no responder únicamente 0 o 1. 

### Matriz de confusión GPT-OSS corpus de desarrollo usando solo prompt, sin ejemplos

| Etiqueta real | Predicción: clase 0 | Predicción: clase 1 |
|---|---:|---:|
| Real 0 | 191 | 8 |
| Real 1 | 21 | 18 |


### Reporte de clasificación GPT-OSS DEV con SE-E5 + k-NN, usando 3 vecinos

| Clase | Precisión | Recall | F1-score | Soporte |
|---|---:|---:|---:|---:|
| Clase 0 | 0.93 | 0.96 | 0.95 | 199 |
| Clase 1 | 0.78 | 0.62 | 0.69 | 40 |
| **Accuracy** |  |  | **0.91** | **239** |
| **Macro avg** | **0.85** | **0.79** | **0.82** | **239** |
| **Weighted avg** | **0.90** | **0.91** | **0.90** | **239** |

### Matriz de confusión

| Etiqueta verdadera | Predicción: clase 0 | Predicción: clase 1 |
|---|---:|---:|
| Clase 0 | 192 | 7 |
| Clase 1 | 15 | 25 |
