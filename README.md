# 🧠 Stroke Prevention Analytics - Machine Learning End-to-End

**Caso de Estudio 02:** Desarrollo de modelos supervisados (Regresión y Clasificación) para la predicción y prevención de derrames cerebrales en el sector asegurador (HealthTech).

## 👥 Equipo de Trabajo
* Einar Guillen
* Huascar Duran
* Leonardo Ibarra
* Leandro Colque
* Octavio Luna

## 🎯 Objetivos del Proyecto
1. **Regresión:** Estimar el nivel medio de glucosa (`avg_glucose_level`) utilizando Regresión Lineal y características polinómicas con regularización Ridge.
2. **Clasificación:** Predecir el riesgo de derrame cerebral (`stroke`) mediante Regresión Logística, aplicando balanceo de pesos y ajuste de umbral operativo para priorizar el Recall.

## 📂 Estructura del Repositorio
* `/notebooks`: Contiene el Jupyter Notebook (`.ipynb`) con el código completo, desde el EDA y la creación de Pipelines (`ColumnTransformer`), hasta el entrenamiento y evaluación de los modelos.
* `/report`: Contiene el informe técnico detallado en formato PDF (análisis de métricas, justificación de leakage clínico y trade-offs).
* `/slides`: Contiene la presentación ejecutiva del proyecto.

## ⚙️ Requisitos y Reproducibilidad
Para reproducir este proyecto, se requiere Python 3.10+ y las siguientes librerías:
* `pandas`
* `numpy`
* `scikit-learn`
* `matplotlib`
* `seaborn`

*Nota: El dataset original no se incluye en este repositorio por buenas prácticas. Puede ser descargado directamente desde [Kaggle: Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) y debe colocarse en la raíz del proyecto para ejecutar el notebook.*
