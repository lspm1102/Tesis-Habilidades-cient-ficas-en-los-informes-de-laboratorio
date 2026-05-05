#### Corpus de test

Los resultados obtenidos con Gemini sobre el corpus de evaluación (test), incorporando ejemplos seleccionados mediante SE Gemma y kNN con tres ejemplos por clase, se presentan en la siguiente tabla.

**Tabla. Reporte de clasificación — Corpus TEST (Gemini + kNN, 3 ejemplos por clase)**

| Clase | precision | recall | f1-score | support |
|---|---:|---:|---:|---:|
| 0 | 0.99 | 0.91 | 0.95 | 210 |
| 1 | 0.60 | 0.93 | 0.73 | 30 |
| accuracy |  |  | 0.91 | 240 |
| macro avg | 0.79 | 0.92 | 0.84 | 240 |
| weighted avg | 0.94 | 0.91 | 0.92 | 240 |

**Tabla. Matriz de confusión — Corpus TEST (Gemini + kNN, 3 ejemplos por clase)**

| Etiqueta real \ Etiqueta predicha | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 191 | 19 |
| Real 1 | 2 | 28 |
