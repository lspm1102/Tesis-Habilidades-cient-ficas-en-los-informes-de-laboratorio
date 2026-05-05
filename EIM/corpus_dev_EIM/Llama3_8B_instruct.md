## LLaMA

#### Corpus de desarrollo

Los resultados obtenidos con LLaMA sobre el corpus de desarrollo, utilizando un *prompt* sin ejemplos, se presentan en la siguiente tabla.

**Tabla. Reporte de clasificación — Corpus DEV (LLaMA, *prompt* sin ejemplos)**

| Clase | precision | recall | f1-score | support |
|---|---:|---:|---:|---:|
| 0 | 0.94 | 0.95 | 0.95 | 210 |
| 1 | 0.63 | 0.59 | 0.61 | 29 |
| accuracy |  |  | 0.91 | 239 |
| macro avg | 0.79 | 0.77 | 0.78 | 239 |
| weighted avg | 0.91 | 0.91 | 0.91 | 239 |

**Tabla. Matriz de confusión — Corpus DEV (LLaMA, *prompt* sin ejemplos)**

| Etiqueta real \ Etiqueta predicha | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 200 | 10 |
| Real 1 | 12 | 17 |
