# Machine Learning. Aprendizaje Supervisado y Procesamiento de Datos

Este repositorio contiene la implementación de un proyecto de la asignatura de Machine Learning de mi Máster en Big Data Analytics para los Negocios, enfocada en el procesamiento de datos y la aplicación de algoritmos de aprendizaje supervisado para resolver problemas de regresión y clasificación.

La implementación se realiza con los métodos de la librería scikit-learn en Python, concretamete usando el algoritmo Random Forest como modelo de entrenamiento.
## Descripción del Proyecto

El proyecto abarca dos ejercicios principales que corresponden a problemas clásicos en aprendizaje supervisado:

1. **Estimación del precio de coches usados (Regresión):**
   - Predicción del precio de venta de vehículos basándose en sus características.
   - Implementación del algoritmo **Random Forest Regressor**.
   - Optimización del modelo para alcanzar un error absoluto medio (MAE) menor a 3000€.

2. **Predicción del resultado de una campaña de marketing telefónica (Clasificación):**
   - Predicción de la probabilidad de que un cliente contrate un producto financiero ofrecido por un banco.
   - Implementación del algoritmo **Random Forest Classifier**.
   - Evaluación mediante métricas como precisión, curva ROC y AUC.
   - Análisis de estrategias para maximizar el balance económico de la campaña.

## Contenido del Repositorio

### Archivos
- **`P1_AA_MarcosTendero.ipynb`**: Jupyter notebook con la implementación de ambos ejercicios, incluyendo visualizaciones, análisis de datos y resultados.
- **`P1_AA_MarcosTendero.pdf`**: Análogo al notebook pero en formato PDF.
- **Datasets**:
  - `dataset_coches_train.csv`: Conjunto de datos de entrenamiento para el ejercicio 1.
  - `dataset_coches_test.csv`: Conjunto de datos de prueba para el ejercicio 1.
  - `dataset_marketing_train.csv`: Conjunto de datos de entrenamiento para el ejercicio 2.
  - `dataset_marketing_test.csv`: Conjunto de datos de prueba para el ejercicio 2.

### Resultados Clave
1. **Ejercicio 1: Regresión**:
   - Visualización de la distribución de precios y análisis de las variables más significativas.
   - Optimización del modelo para alcanzar un MAE de menos de 3000€.

2. **Ejercicio 2: Clasificación**:
   - Curva ROC y cálculo del AUC para evaluar el modelo.
   - Análisis de estrategias basadas en umbrales de probabilidad para maximizar el balance de la campaña.

## Requisitos

- **Lenguaje**: Python 3.8+
- **Bibliotecas**:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
 
## Autor
Marcos Tendero Carmona
