# Actividad: Uso Crítico de Inteligencia Artificial para Apoyo en Programación

## Contexto de la actividad

En esta actividad trabajarás con un notebook en Google Colab que contiene fragmentos simples de código en Python relacionados con análisis de datos.

El objetivo no es evaluar tu capacidad de programar desde cero, sino **analizar cómo un asistente de inteligencia artificial puede apoyar la resolución de tareas de programación y qué limitaciones presenta**.

Durante la actividad utilizarás un asistente de IA (por ejemplo ChatGPT, Gemini, Claude u otro) para:

- formular preguntas sobre el código
- solicitar ayuda para completar o mejorar funciones
- interpretar resultados
- evaluar la calidad de las respuestas obtenidas

A lo largo del notebook deberás **documentar tu interacción con la IA**, incluyendo:

- el prompt utilizado
- la respuesta del sistema
- tu evaluación crítica del resultado
- posibles ajustes al prompt

De esta forma se busca comprender **cómo utilizar asistentes de IA de forma crítica y responsable en tareas técnicas**.

---

## Objetivo de Aprendizaje

Al finalizar esta actividad el estudiante será capaz de:

- Utilizar asistentes de inteligencia artificial para apoyar tareas de programación.
- Formular prompts claros para resolver problemas técnicos.
- Evaluar críticamente la calidad de las respuestas generadas por IA.
- Identificar limitaciones y errores en las respuestas de sistemas de IA.
- Reflexionar sobre el uso responsable de IA en contextos profesionales.

---

## Material de trabajo

- Notebook en Google Colab (provisto por el docente).
- Fragmentos de código en Python incluidos en el notebook.
- Acceso a un asistente de IA (ChatGPT, Gemini, Claude u otro).

No es necesario instalar librerías adicionales ni utilizar API.

---

## Instrucciones generales

1. Abre el notebook en Google Colab.
2. Ejecuta las celdas de código para observar su funcionamiento.
3. En algunas secciones el código estará incompleto o requerirá mejoras.
4. Utiliza un asistente de IA para ayudarte a resolver la tarea.
5. Documenta en el notebook:
   - el prompt utilizado
   - la respuesta entregada por la IA
   - tu evaluación de la respuesta
   - posibles modificaciones al prompt
6. Ejecuta el código sugerido y analiza el resultado obtenido.
7. Completa las secciones de reflexión incluidas en el notebook.

Finalmente descarga el notebook (.ipynb) y súbelo al Aula.

---

# Parte 1: Comprensión del código

El siguiente código carga un conjunto de datos y muestra algunas estadísticas básicas.

```python
import pandas as pd

data = {
    "horas_estudio": [2, 5, 1, 4, 6, 3],
    "asistencia": [60, 90, 50, 80, 95, 70],
    "resultado": [0, 1, 0, 1, 1, 0]
}

df = pd.DataFrame(data)
df.describe()
````

### Preguntas

Responde en una celda Markdown:

* ¿Qué información entrega `df.describe()`?
* ¿Qué tipo de variables contiene el dataset?

---

# Parte 2: Uso de IA para mejorar el análisis

Queremos crear un gráfico que muestre la relación entre **horas de estudio y resultado académico**.

El siguiente código está incompleto:

```python
import matplotlib.pyplot as plt

plt.scatter(df["horas_estudio"], df["resultado"])

# agregar etiquetas al gráfico
# agregar título
# mostrar gráfico
```

### Instrucciones

Utiliza un asistente de IA para completar el código.

Documenta lo siguiente:

#### Prompt utilizado

Escribe aquí el prompt que utilizaste para pedir ayuda al asistente.

#### Respuesta de la IA

Copia el código sugerido por el asistente.

#### Evaluación

Responde:

* ¿El código sugerido funcionó correctamente?
* ¿Tuviste que modificar algo?
* ¿La explicación del asistente fue clara?

---

# Parte 3: Refinamiento del prompt

Ahora intenta mejorar tu prompt inicial.

Incluye más contexto, por ejemplo:

* qué hace el código
* qué librería estás usando
* qué resultado esperas obtener

### Prompt mejorado

Escribe aquí el nuevo prompt.

### Nueva respuesta del asistente

Copia la respuesta generada.

### Comparación

Responde:

* ¿La nueva respuesta fue mejor que la anterior?
* ¿Qué diferencias observas?
* ¿Qué aprendiste sobre cómo formular prompts?

---

# Parte 4: Uso de IA para interpretar resultados

Ejecuta el gráfico generado.

Luego pregunta al asistente de IA algo como:

> ¿Qué interpretación se podría hacer de este gráfico?

### Documenta

* prompt utilizado
* respuesta del sistema

### Análisis

Responde:

* ¿La interpretación del asistente te parece correcta?
* ¿Hay afirmaciones exageradas o poco justificadas?

---

# Parte 5: Reflexión crítica sobre el uso de IA

Responde las siguientes preguntas:

* ¿En qué aspectos el asistente de IA fue útil durante esta actividad?
* ¿En qué momentos fue necesario revisar o corregir sus respuestas?
* ¿Qué riesgos existirían si un programador utilizara estas respuestas sin revisarlas?
* ¿En qué tipo de tareas técnicas consideras más útil el apoyo de IA?

---

# Entregable

* Notebook en formato `.ipynb`.
* Todas las respuestas deben estar dentro del notebook.
* Se deben incluir los prompts utilizados y las respuestas del sistema.

---

# Criterios de Evaluación

| Criterio               | Descripción                                         |
| ---------------------- | --------------------------------------------------- |
| Uso de IA              | Documenta correctamente prompts y respuestas        |
| Evaluación crítica     | Analiza de forma reflexiva las respuestas generadas |
| Comprensión del código | Explica correctamente el funcionamiento del código  |
| Reflexión final        | Identifica beneficios y riesgos del uso de IA       |
