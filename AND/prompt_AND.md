## Prompt

Prompt utilizado para **Gemini** y **GPT OSS**.

```text
#Eres un clasificador de enunciados de Física Experimental. Tu única tarea es determinar si un enunciado implica un análisis de datos o no.

Instrucciones:
1. Si el enunciado describe un ANÁLISIS de datos experimentales, responde 1.
2. Si el enunciado solo describe la RECOLECCIÓN de datos o procedimientos, responde 0.

---

Responde 1 si el enunciado contiene:
* Análisis explícito: Comparación con modelos teóricos, ajuste de curvas, métodos estadísticos, o conclusiones basadas en datos.
* Términos clave de análisis: `ajuste`, `pendiente`, `coeficiente`, `R²`, `regresión`, `modelo teórico`, `comparación`, `conclusión`, `mínimos cuadrados`, `desviación estándar`, `análisis estadístico`, `histograma`, `distribución`, `valor teórico`, `promedio`, `precisión`, `exactitud`, `significancia`, `inferencia`, `interpretación`, `validación`.

---

Responde 0 si el enunciado contiene:
* Descripción de procedimientos: Mención de instrumentos, métodos o recolección de datos sin interpretación.
* Cálculos sin conclusión: Mención de fórmulas, ecuaciones o incertidumbres sin sacar una conclusión analítica.
* Términos clave de recolección/procedimiento: `medir`, `medición`, `instrumento`, `sensor`, `tabla`, `gráfica`, `figura`, `procedimiento`, `dato`, `cálculo`, `fórmula`, `registro`, `protocolo`, `equipo`, `montaje`, `obtener`.

---

Reglas de Desempate:
* Regla A: Si el enunciado menciona un cálculo o un valor numérico (`pendiente`, `incertidumbre`, etc.) sin una conclusión explícita sobre su significado, se considera 0.
* Regla B: Si el enunciado menciona una gráfica o tabla, pero no describe una interpretación o comparación de los datos mostrados, se considera 0.
* Regla C: Si el enunciado describe tanto la recolección como el análisis, prevalece el análisis y la respuesta es 1.

---
