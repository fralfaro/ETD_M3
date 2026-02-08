# Actividad: Análisis e Interpretación de un Modelo de Machine Learning

## Contexto de la actividad

En esta actividad trabajarás con un notebook en Google Colab que implementa un modelo de **clasificación supervisada** para predecir el riesgo académico de estudiantes.

El problema abordado es un caso típico de **clasificación binaria**, donde:

- `0` representa estudiantes de **bajo riesgo académico**
- `1` representa estudiantes de **alto riesgo académico**

El modelo utilizado es un **Random Forest**, entrenado a partir de variables académicas y/o contextuales previamente exploradas mediante Análisis Exploratorio de Datos (EDA).

El código del modelo ya se encuentra completamente implementado. El foco de esta actividad no es programar, sino **comprender el comportamiento del modelo, interpretar sus métricas y reflexionar sobre su uso en un contexto real**.



## Objetivo de Aprendizaje

Al finalizar esta actividad, el estudiante será capaz de:

- Comprender el objetivo de un modelo de clasificación binaria.
- Interpretar métricas de evaluación de modelos de machine learning.
- Analizar una matriz de confusión y los distintos tipos de errores.
- Evaluar críticamente el desempeño del modelo en un contexto aplicado.
- Reflexionar sobre implicancias éticas y prácticas del uso del modelo.



## Material de trabajo

- Notebook en Google Colab (provisto por el docente).
- Conjunto de datos preprocesado y dividido en conjuntos de entrenamiento y prueba.
- Modelo Random Forest ya entrenado.

No es necesario modificar el código del notebook.



## Descripción general del modelo

El modelo entrenado corresponde a un **Random Forest Classifier**, configurado con los siguientes parámetros principales:

- Número de árboles: 300
- Profundidad máxima de los árboles: 5
- Tamaño mínimo de hojas: 20

El modelo predice la probabilidad de que un estudiante pertenezca a la categoría de **alto riesgo académico**.



## Instrucciones

1. Accede al notebook en Google Colab utilizando el enlace proporcionado.
2. Ejecuta todas las celdas en el orden indicado.
3. Observa con atención:
   - Las métricas de evaluación del modelo.
   - La matriz de confusión.
   - La curva ROC y el valor AUC.
4. Responde las preguntas de análisis que se presentan a continuación.
5. Fundamenta tus respuestas utilizando exclusivamente los resultados observados en el notebook.



## Preguntas de Análisis

### 1. Comprensión del problema

- ¿Cuál es el objetivo principal del modelo de machine learning?
- ¿Qué significa predecir correctamente un estudiante de alto riesgo?
- ¿Por qué este problema se considera una tarea de clasificación binaria?


### 2. Interpretación de métricas

A partir de los valores mostrados en el notebook:

- ¿Qué mide la métrica **accuracy** en este contexto?
- ¿Qué información entrega la **precision** para la clase de alto riesgo?
- ¿Qué significa un valor bajo o alto de **recall** en este problema?
- ¿Por qué el **F1-score** puede ser más informativo que la accuracy?


### 3. Análisis de la matriz de confusión

Utilizando la matriz de confusión:

- Identifica los **verdaderos positivos**, **verdaderos negativos**, **falsos positivos** y **falsos negativos**.
- ¿Qué representa un **falso positivo** en este contexto académico?
- ¿Qué representa un **falso negativo**?
- ¿Cuál de estos errores consideras más grave? Justifica tu respuesta.


### 4. Curva ROC y AUC

- ¿Qué información entrega la curva ROC?
- ¿Qué interpretación tiene el valor AUC obtenido?
- ¿El modelo discrimina adecuadamente entre estudiantes de alto y bajo riesgo?



### 5. Evaluación crítica del modelo

- ¿Consideras que el modelo funciona bien? Fundamenta tu respuesta.
- ¿En qué escenarios este modelo podría ser útil?
- ¿Qué riesgos existen al utilizar este modelo sin supervisión humana?


### 6. Reflexión y mejoras

- ¿Qué otras variables podrían mejorar el desempeño del modelo?
- ¿Qué métricas adicionales podrían ser relevantes en este problema?
- ¿Qué aspectos éticos deben considerarse al usar modelos predictivos en educación?



## Entregable

- Documento en formato Markdown o PDF.
- Extensión máxima: 2 a 3 páginas.
- Respuestas claras, bien estructuradas y argumentadas.



## Criterios de Evaluación

| Criterio | Logrado (100%) | Adecuado (80%) | Básico (60%) | Insuficiente (0%) |
|--------|----------------|----------------|---------------|-------------------|
| Comprensión del problema | Explica correctamente el objetivo y el contexto del modelo | Explicación general correcta | Explicación superficial | No comprende el problema |
| Interpretación de métricas | Interpreta correctamente todas las métricas | Interpreta la mayoría de las métricas | Interpretación parcial | Interpretación incorrecta |
| Análisis de errores | Analiza correctamente falsos positivos y negativos | Análisis adecuado con leves omisiones | Análisis superficial | No analiza los errores |
| Evaluación del modelo | Evaluación crítica bien fundamentada | Evaluación adecuada | Evaluación poco justificada | No evalúa el modelo |
| Reflexión y propuestas | Propone mejoras y reflexiones relevantes | Propone algunas mejoras | Propuestas poco claras | No propone mejoras |

> **Puntaje total: 100 puntos**


## Consideraciones finales

- No se evaluará la modificación del código.
- El énfasis está en la interpretación y razonamiento.
- No existen respuestas únicas, pero sí respuestas mejor fundamentadas que otras.


