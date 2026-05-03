### Resultados sobre el corpus de desarrollo utilizando Llama3 8B instruct

En este caso, se utilizó un prompt al que se incorporaron ejemplos seleccionados manualmente para cada clase. El prompt incluía cuatro ejemplos clave de la clase 1 y tres ejemplos de la clase 0.

#### Reporte de clasificación LLAMA sobre el corpus de desarrollo

| Clase | Precisión | Recall | F1-score | Soporte |
|---|---:|---:|---:|---:|
| Clase 0 | 0.92 | 0.97 | 0.95 | 199 |
| Clase 1 | 0.80 | 0.60 | 0.69 | 40 |
| **Accuracy** |  |  | **0.91** | **239** |
| **Macro avg** | **0.86** | **0.78** | **0.82** | **239** |
| **Weighted avg** | **0.90** | **0.91** | **0.90** | **239** |

#### Matriz de confusión LLAMA sobre el corpus de desarrollo

| Etiqueta real | Predicho 1 | Predicho 0 |
|---|---:|---:|
| Clase 1 | 24 | 16 |
| Clase 0 | 6 | 193 |

Luego, se evaluó el modelo sobre el corpus de desarrollo proporcionando los tres ejemplos más cercanos al enunciado a clasificar. Estos ejemplos fueron seleccionados mediante k-NN y *sentence embeddings* Multilingual-E5, sin garantizar la inclusión de ejemplos de ambas clases.

#### Reporte de clasificación LLAMA sobre el corpus de desarrollo con Multilingual-E5 + k-NN

| Clase | Precisión | Recall | F1-score | Soporte |
|---|---:|---:|---:|---:|
| Clase 0 | 0.93 | 0.95 | 0.94 | 199 |
| Clase 1 | 0.71 | 0.60 | 0.68 | 40 |
| **Accuracy** |  |  | **0.90** | **239** |
| **Macro avg** | **0.82** | **0.81** | **0.81** | **239** |
| **Weighted avg** | **0.90** | **0.90** | **0.90** | **239** |

#### Matriz de confusión LLAMA sobre el corpus de desarrollo con Multilingual-E5 + k-NN

| Etiqueta real | Predicho 1 | Predicho 0 |
|---|---:|---:|
| Clase 1 | 27 | 13 |
| Clase 0 | 11 | 188 |
