# SaberPro-Performance-Prediction

Proyecto de Machine Learning orientado a la predicción del rendimiento académico (categorías: Baja, Media-baja, Media-alta, Alta) en las pruebas Saber Pro, basado en variables sociodemográficas y académicas.

## Descripción
Desarrollo de un modelo de clasificación para identificar patrones de éxito académico. El proyecto abarca el ciclo completo de ciencia de datos, desde la limpieza y exploración hasta la optimización de hiperparámetros y evaluación de modelos.

## Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Técnicas:** Preprocesamiento de datos (OneHotEncoder, StandardScaler), Clasificación, Validación Cruzada y ajuste con GridSearchCV.

## Etapas del Proyecto
1. **Limpieza y Preprocesamiento:** Manejo de valores faltantes, codificación de variables categóricas y normalización.
2. **Análisis Exploratorio (EDA):** Visualización de datos para identificar correlaciones y distribución del target (RENDIMIENTO_GLOBAL).
3. **Modelado:** Entrenamiento y comparativa de modelos de clasificación.
4. **Optimización:** Búsqueda de hiperparámetros óptimos mediante `GridSearchCV`.
5. **Evaluación:** Medición del desempeño mediante métricas como precisión, recall y validación cruzada.

## Resultados
El modelo permite identificar las variables determinantes en el rendimiento académico de los estudiantes, proporcionando una herramienta para la toma de decisiones basada en datos.
