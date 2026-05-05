#### Corpus de test

Los resultados obtenidos con GPT-OSS sobre el corpus de test, utilizando SE Multilingual E5 y kNN con tres ejemplos, se presentan en la siguiente tabla.

**Tabla. Reporte de clasificación — Corpus TEST (GPT-OSS + SE E5 + kNN = 3)**

| Clase | precision | recall | f1-score | support |
|---|---:|---:|---:|---:|
| 0 | 0.97 | 0.90 | 0.94 | 210 |
| 1 | 0.56 | 0.83 | 0.67 | 30 |
| accuracy |  |  | 0.90 | 240 |
| macro avg | 0.76 | 0.87 | 0.80 | 240 |
| weighted avg | 0.92 | 0.90 | 0.90 | 240 |

**Tabla. Matriz de confusión — Corpus TEST (GPT-OSS + SE E5 + kNN = 3)**

| Etiqueta real \ Etiqueta predicha | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 190 | 20 |
| Real 1 | 5 | 25 |
