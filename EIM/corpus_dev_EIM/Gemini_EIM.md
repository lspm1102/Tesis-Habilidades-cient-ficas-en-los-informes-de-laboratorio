## Gemini

#### Corpus de desarrollo

##### Resultados *zero-shot*

Los resultados obtenidos con Gemini sobre el corpus de desarrollo, sin incluir ejemplos en el *prompt*, se presentan en la siguiente tabla.

**Tabla. Reporte de clasificación — Corpus DEV (Gemini sin ejemplos)**

| Clase | precision | recall | f1-score | support |
|---|---:|---:|---:|---:|
| 0 | 0.9797 | 0.9190 | 0.9484 | 210 |
| 1 | 0.5952 | 0.8621 | 0.7042 | 29 |
| accuracy |  |  | 0.9121 | 239 |
| macro avg | 0.7875 | 0.8906 | 0.8263 | 239 |
| weighted avg | 0.9330 | 0.9121 | 0.9188 | 239 |

**Tabla. Matriz de confusión — Corpus DEV (Gemini sin ejemplos)**

| Etiqueta real \ Etiqueta predicha | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 193 | 17 |
| Real 1 | 4 | 25 |

##### Resultados con SE Gemma y kNN = 3 por clase

Los resultados obtenidos con Gemini sobre el corpus de desarrollo, incorporando ejemplos seleccionados mediante SE Gemma y kNN con tres ejemplos por clase, se presentan en la siguiente tabla.

**Tabla. Reporte de clasificación — Corpus DEV (Gemini + kNN, 3 ejemplos por clase)**

| Clase | precision | recall | f1-score | support |
|---|---:|---:|---:|---:|
| 0 | 0.99 | 0.90 | 0.94 | 210 |
| 1 | 0.57 | 0.90 | 0.69 | 29 |
| accuracy |  |  | 0.90 | 239 |
| macro avg | 0.77 | 0.90 | 0.82 | 239 |
| weighted avg | 0.93 | 0.90 | 0.91 | 239 |

**Tabla. Matriz de confusión — Corpus DEV (Gemini + kNN, 3 ejemplos por clase)**

| Etiqueta real \ Etiqueta predicha | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 190 | 20 |
| Real 1 | 3 | 26 |
