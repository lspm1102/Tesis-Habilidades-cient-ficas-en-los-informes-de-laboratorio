## Sentence Embeddings + kNN

#### Corpus de desarrollo

Los resultados obtenidos para el código EIM sobre el corpus de desarrollo, utilizando SE Gemma y kNN con cinco vecinos, se presentan en la siguiente tabla.

**Tabla. Reporte de clasificación — Código EIM, Corpus DEV (SE Gemma + kNN = 5)**

| Clase | precision | recall | f1-score | support |
|---|---:|---:|---:|---:|
| 0 | 0.95 | 0.97 | 0.96 | 199 |
| 1 | 0.85 | 0.72 | 0.78 | 40 |
| accuracy |  |  | 0.93 | 239 |
| macro avg | 0.90 | 0.85 | 0.87 | 239 |
| weighted avg | 0.93 | 0.93 | 0.93 | 239 |

**Tabla. Matriz de confusión — Código EIM, Corpus DEV (SE Gemma + kNN = 5)**

| Etiqueta real \ Etiqueta predicha | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 194 | 5 |
| Real 1 | 11 | 29 |
