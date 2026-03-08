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
4. Responde las siguientes preguntas de análisis en Google Colab, utilizando celdas en formato Markdown dentro del notebook.
5. Justifica tus respuestas a partir de la información, resultados y gráficos obtenidos en el notebook.
6. Finalmente, descarga el archivo del notebook (.ipynb) y súbelo al Aula para su evaluación.




## Preguntas de Análisis

### 1. Comprensión del problema

- ¿Cuál es el objetivo del modelo de machine learning presentado en el notebook?
- ¿Qué significa predecir correctamente a un estudiante de **alto riesgo**?
- ¿Por qué este problema corresponde a una **clasificación binaria**?



### 2. Interpretación de métricas del modelo

A partir de los resultados mostrados en el notebook:

- Explica qué miden las métricas **accuracy, precision, recall y F1-score** en este contexto.
- ¿Cuál de estas métricas consideras más relevante para este problema? Justifica tu respuesta.



### 3. Análisis de la matriz de confusión

Observando la matriz de confusión:

- Identifica los **verdaderos positivos, verdaderos negativos, falsos positivos y falsos negativos**.
- ¿Qué representan los **falsos positivos** y los **falsos negativos** en el contexto académico?
- ¿Cuál de estos errores consideras más grave? Justifica tu respuesta.



### 4. Evaluación del desempeño del modelo

- ¿Qué información entrega la **curva ROC**?
- ¿Cómo interpretas el valor **AUC** obtenido?
- En términos generales, ¿el modelo discrimina adecuadamente entre estudiantes de alto y bajo riesgo?


### 5. Reflexión crítica

- ¿Consideras que el modelo podría ser útil en un contexto educativo? Explica en qué situaciones.
- ¿Qué riesgos podrían existir al utilizar este modelo sin supervisión humana?
- ¿Qué mejoras (por ejemplo, nuevas variables o métricas) podrían ayudar a mejorar el modelo?


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


