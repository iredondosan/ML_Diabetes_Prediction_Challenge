## ML Challenge: Aprendizaje Supervisado y No Supervisado
### 1. Contexto
La tarea consiste en resolver un challenge de Machine Learning en equipo aplicando los conocimientos adquiridos en el módulo de Aprendizaje Supervisado y No Supervisado, así como los modelos descritos en el documento MLpedia.
El challenge simula un caso real de Data Science, donde no existe una única solución correcta, sino decisiones justificadas en base a datos, métricas y criterios técnicos.
### 2. Objetivo
Diseñar, implementar y evaluar una solución completa de Machine Learning, desde la exploración de los datos hasta la evaluación del modelo final. Seleccionar uno o varios modelos de ML (supervisados y/o no supervisados) y justificar su elección. Demostrar capacidad de análisis crítico, experimentación, validación y comunicación técnica.
### 3. Organización del trabajo
Trabajo en equipos de 4 personas.
Todos los miembros deben contribuir activamente (el reparto de
tareas debe quedar reflejado).
El código debe ser original, reproducible y comprensible.
### 4. Alcance técnico mínimo esperado
Cada equipo deberá cubrir, como mínimo, las siguientes fases:
#### 4.1. Análisis y comprensión del problema
- Comprensión del objetivo del challenge.
- Identificación del tipo de problema:
    - Supervisado (clasificación / regresión).
    - No supervisado (clustering, detección de anomalías, etc.).
- Suposiciones iniciales y riesgos.
#### 4.2. Exploración y análisis de datos (EDA)
- Análisis estadístico básico.
- Distribuciones, correlaciones y outliers. Visualizaciones relevantes.
- Primeras hipótesis basadas en los datos.
#### 4.3. Preprocesamiento
- Limpieza de datos (nulos, duplicados, inconsistencias).
- Transformaciones necesarias:
    - Escalado / normalización.
    - Codificación de variables categóricas.
- Justificación de cada decisión.
#### 4.4. Selección y entrenamiento de modelos
- Elección de al menos un modelo de ML visto en clase o en MLpedia.
- Justificación de por qué ese modelo es adecuado para el problema.
- Entrenamiento del modelo.
- Opcional pero valorado:
    - Comparativa entre varios modelos (opcional pero valorado).
    - Uso combinado de modelos supervisados y no supervisados.
#### 4.5. Optimización
- Ajuste de hiperparámetros (Grid Search, Random Search u otro método).
- Uso de validación cruzada cuando sea pertinente. Evitar sobreajuste.
#### 4.6. Evaluación
- Elección adecuada de métricas según el problema.
- Análisis de resultados.
- Interpretación de errores.
- Visualización de resultados (curvas, matrices, clusters, etc.).
#### 4.7. Conclusiones
- Qué ha funcionado y qué no.
- Limitaciones del enfoque.
- Posibles mejoras o siguientes pasos.
### 5. Formato del entregable
#### 5.1 Entregable principal (obligatorio)
#### Repositorio de código (GitHub (o semejante) o ZIP estructurado) con:
```text
/project
├── data/            # Datos (o instrucciones para obtenerlos)
├── notebooks/       # Jupyter Notebooks (EDA, modelado, evaluación)
├── results/         # Figuras, métricas, outputs
├── README.md        # Resumen y presentación del código
└── requirements.txt # Dependencias / librerías
```

#### ¡Importante!
- Código ejecutable y ordenado.
- Comentarios claros (no excesivos).
- Uso correcto de librerías estándar (numpy, pandas, sklearn, etc.).
- Reproducibilidad (semillas aleatorias cuando aplique).
#### 5.2 Informe técnico (obligatorio)
#### Formato: PDF (≈ 8–12 páginas).
#### Debe incluir:
1. Introducción y contexto del problema.
2. Descripción del dataset.
3. Metodología seguida.
4. Modelos utilizados y justificación.
5. Resultados y evaluación.
6. Conclusiones.
7. Reparto de tareas del equipo.
#### ¡Importante!
- En el informe no se debe incluir código, sino referencias al mismo cuando sea necesario. Es decir, el informe no sustituye al código: lo complementa.
5.3 Defensa oral
- Duración: 10–15 minutos por equipo.
- Todos los miembros deben intervenir.
- Enfocada en:
    - Decisiones clave.
    - Resultados.
    - Aprendizajes.
#### ¡Importante!
- La presentación debe ser una explicación oral del informe y de todo
el trabajo. No hace falta añadir código.
- Lo que quiero es que me expliqueis en grupo, qué hicisteis, por qué,
para qué, cómo y qué resultados obtuvisteis.