#### Corpus de test

Los resultados obtenidos con Regresión Logística para la clase EIM sobre el corpus de test, utilizando lematización y eliminación de *stop words*, se presentan en la siguiente tabla.

**Tabla. Reporte de clasificación — Clase EIM, Corpus TEST (Regresión Logística con lemas y eliminación de *stop words*)**

| Clase | precision | recall | f1-score | support |
|---|---:|---:|---:|---:|
| 0 | 0.93 | 0.95 | 0.94 | 210 |
| 1 | 0.62 | 0.53 | 0.57 | 30 |
| accuracy |  |  | 0.90 | 240 |
| macro avg | 0.77 | 0.74 | 0.76 | 240 |
| weighted avg | 0.89 | 0.90 | 0.90 | 240 |

**Tabla. Matriz de confusión — Clase EIM, Corpus TEST (Regresión Logística con lemas y eliminación de *stop words*)**

| Etiqueta real \ Etiqueta predicha | Predicha 0 | Predicha 1 |
|---|---:|---:|
| Real 0 | 200 | 10 |
| Real 1 | 14 | 16 |
