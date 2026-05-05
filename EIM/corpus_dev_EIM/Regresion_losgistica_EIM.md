## Regresión Logística

#### Corpus de desarrollo

Los resultados obtenidos con Regresión Logística sobre el corpus de desarrollo, utilizando lematización y eliminación de *stop words*, se presentan en la siguiente tabla.

**Tabla. Reporte de clasificación — Corpus DEV (Regresión Logística con lemas y eliminación de *stop words*)**

| Clase | precision | recall | f1-score | support |
|---|---:|---:|---:|---:|
| 0 | 0.95 | 0.92 | 0.94 | 212 |
| 1 | 0.50 | 0.59 | 0.54 | 27 |
| accuracy |  |  | 0.89 | 239 |
| macro avg | 0.72 | 0.76 | 0.74 | 239 |
| weighted avg | 0.90 | 0.89 | 0.89 | 239 |

**Tabla. Matriz de confusión — Corpus DEV (Regresión Logística con lemas y eliminación de *stop words*)**

| Etiqueta real \ Etiqueta predicha | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 196 | 16 |
| Real 1 | 11 | 16 |
