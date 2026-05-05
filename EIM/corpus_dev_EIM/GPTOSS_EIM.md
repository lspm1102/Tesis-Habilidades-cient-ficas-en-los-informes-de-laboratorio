## GPT OSS

#### Corpus de desarrollo

Los resultados obtenidos con GPT-OSS sobre el corpus de desarrollo, utilizando SE Multilingual E5 y kNN con tres ejemplos, se presentan en la siguiente tabla.

**Tabla. Reporte de clasificación — Corpus DEV (GPT-OSS + SE E5 + kNN = 3)**

| Clase | precision | recall | f1-score | support |
|---|---:|---:|---:|---:|
| 0 | 0.97 | 0.92 | 0.95 | 210 |
| 1 | 0.59 | 0.83 | 0.69 | 29 |
| accuracy |  |  | 0.91 | 239 |
| macro avg | 0.78 | 0.87 | 0.82 | 239 |
| weighted avg | 0.93 | 0.91 | 0.91 | 239 |

**Tabla. Matriz de confusión — Corpus DEV (GPT-OSS + SE E5 + kNN = 3)**

| Etiqueta real \ Etiqueta predicha | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 193 | 17 |
| Real 1 | 5 | 24 |
