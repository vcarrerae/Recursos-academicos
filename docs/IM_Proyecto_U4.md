# [IM] Evaluación de la unidad 4

---

La evaluación de la Unidad 4 se llevará a cabo a partir del desarrollo de un proyecto por equipos de **cuatro personas**. Cada equipo debe de elegir **uno** de los problemas de tal manera que **no puede haber dos equipos resolviendo el mismo problema**. 

Por favor, indique en el canal general de Teams (dónde se publica esta tarea) qué problema desea abordar. 

Una vez que un equipo se compromete con un problema, deberá desarrollar lo que indique el mismo. Los entregables para la unidad serán:

- Un reporte de investigación completo que debe contener:
    - Portada (Obligatoria)
    - Resumen (10)
    - Marco teórico (15)
    - Metodología (25)
    - Resultados (35)
    - Conclusiones (10)
    - Bibliografía (5)
    - Evidencia de que se hicieron las mediciones (indispensable)

Puede encontrar instrucciones detalladas para la redacción del reporte en el siguiente [**enlace**](Manual%20de%20reportes%20de%20investigaci%C3%B3n%20376fcd2155c78003a935ed67b1785453.md).

- El reporte así como el código deben entregarse en una sola libreta de Google Colab (asegúrese de que los permisos sean públicos) dónde se muestren claramente los datos en formato de tabla con su respectivo análisis.

De manera que los reportes funcionen como evidencia de la unidad, la sección de resultados del reporte deberá de contener:

- Diagramas de dispersión entre las variables con su respectivo análisis.
- Coeficiente de correlación entre las variables y su implicación/significado.
- Uso del método de mínimos cuadrados para encontrar los parámetros de la recta de regresión.
- Ecuación de la recta de regresión lineal y la interpretación de los componentes de ésta.
- Sólo se permite el uso de las librerías: math, matplotlib, seaborn, scipy.stats y pandas.
- **Todos los reportes serán analizados con un detector de plagio e IA. Si el detector arroja más de un 30% de plagio ó uso de IA en el texto, el reporte será considerado inválido.**

# Problema General

1. Seleccionar el experimento de Human Benchmark con el que desea experimentar (sólo un equipo por cada experimento).
    1. Reaction time
    2. Sequence memory
    3. Aim trainer
    4. Number memory
    5. Verbal memory
    6. Chimp test
    7. Visual memory
    8. Typing
2. Planear un experimento para determinar la relación entre dos variables.
    1. Seleccionar una variable continua (para regresión lineal): Horas de sueño de la noche anterior, nivel de estrés aproximado (1-10), consumo de cafeína (sí/no), consumo de bebida energética (sí/no) ó número de intento.
    2. Seleccionar una variable categórica (para regresión logística): consumo de cafeína en las últimas dos horas (sí/no), consumo de bebida energética en las últimas dos horas (sí/no).
    3. Analizar cuál es la variable dependiente (respuesta) en su experimento: tiempo de reacción, secuencia máxima de memoria, cantidad de palabras escritas (sólo una).
    4. Proponer una relación entre las variables (de manera cualitativa: ¿qué espera que pase con la variable dependiente en función del consumo de cafeína?)
3. Llevar a cabo el experimento hasta conseguir un conjunto de al menos 50 datos. 
4. Determinar la ecuación de regresión lineal. 
5. Interpretar el significado de los coeficientes. 
6. Obtener el gráfico de dispersión de las variables continuas con la línea de regresión superpuesta. 
7. Obtener el gráfico de dispersión entre la variable categórica y la variable del experimento.
8. Graficar la curva sigmoide clásica a través de SciPy.
9. Interpretar cada uno de los gráficos.
