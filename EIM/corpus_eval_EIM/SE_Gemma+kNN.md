#### Corpus de test

Los resultados obtenidos para el código EIM sobre el corpus de test, utilizando Sentence Embedding Gemma y kNN con cinco vecinos, se presentan en la siguiente tabla.

**Tabla. Reporte de clasificación — Código EIM, Corpus TEST (Sentence Embedding Gemma + kNN = 5)**

| Clase | precision | recall | f1-score | support |
|---|---:|---:|---:|---:|
| 0 | 0.94 | 0.96 | 0.95 | 210 |
| 1 | 0.67 | 0.60 | 0.63 | 30 |
| accuracy |  |  | 0.91 | 240 |
| macro avg | 0.81 | 0.78 | 0.79 | 240 |
| weighted avg | 0.91 | 0.91 | 0.91 | 240 |

**Tabla. Matriz de confusión — Código EIM, Corpus TEST (Sentence Embedding Gemma + kNN = 5)**

| Etiqueta real \ Etiqueta predicha | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 201 | 9 |
| Real 1 | 12 | 18 |
