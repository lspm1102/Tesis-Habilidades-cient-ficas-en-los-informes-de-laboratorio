#### Corpus de test

Los resultados obtenidos con LLaMA sobre el corpus de test, utilizando un *prompt* sin ejemplos, se presentan en la siguiente tabla.

**Tabla. Reporte de clasificación — Corpus TEST (LLaMA, *prompt* sin ejemplos)**

| Clase | precision | recall | f1-score | support |
|---|---:|---:|---:|---:|
| 0 | 0.94 | 0.93 | 0.93 | 210 |
| 1 | 0.53 | 0.57 | 0.55 | 30 |
| accuracy |  |  | 0.88 | 240 |
| macro avg | 0.73 | 0.75 | 0.74 | 240 |
| weighted avg | 0.89 | 0.88 | 0.88 | 240 |

**Tabla. Matriz de confusión — Corpus TEST (LLaMA, *prompt* sin ejemplos)**

| Etiqueta real \ Etiqueta predicha | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 195 | 15 |
| Real 1 | 13 | 17 |
