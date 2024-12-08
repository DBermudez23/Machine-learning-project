# Clasificación de Países según Riesgo Energético

Este repositorio contiene el desarrollo completo del proyecto final del Bootcamp Talento Tech, enfocado en la clasificación de países según su nivel de riesgo energético mediante el uso de técnicas avanzadas de machine learning.

## Descripción

El proyecto aborda un problema crítico para la sostenibilidad global: identificar y clasificar países según su riesgo energético en categorías de **Alto**, **Medio** y **Bajo** riesgo. Esto se logra utilizando datos públicos sobre consumo energético, energías renovables, acceso a combustibles limpios, entre otros factores.

El modelo desarrollado combina técnicas de limpieza de datos, ingeniería de características, reducción de dimensionalidad con PCA y algoritmos de clasificación como Random Forest y Árboles de Decisión. También incluye estrategias para abordar el desbalance de clases mediante SMOTE y GridSearchCV para la optimización de hiperparámetros.

## Estructura del Proyecto

- **01_Introducción**: Contexto del problema, objetivos y relevancia global.
- **02_Preparación de Datos**: Limpieza, imputación de valores faltantes y reducción de dimensionalidad.
- **03_Modelado**: Entrenamiento de modelos de clasificación (Random Forest, Árboles de Decisión).
- **04_Evaluación**: Métricas como Accuracy, Matriz de Confusión, F1-Score y curvas ROC-AUC.
- **05_Optimización**: Uso de GridSearchCV para encontrar los mejores hiperparámetros.

## Requisitos

- **Python 3.8+**
- Bibliotecas utilizadas:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `imbalanced-learn`

Para instalar todas las dependencias:
```bash
pip install -r requirements.txt

Ejecución

    Clona este repositorio:

git clone https://github.com/usuario/repositorio.git

Ejecuta el archivo Jupyter Notebook:

    jupyter notebook Final_project_talento_tech.ipynb

Resultados

    Precisión del modelo: 98.5%
    ROC-AUC promedio: 99.7%
    Visualización del modelo de Árbol de Decisión optimizado.

Contribuciones

Se aceptan contribuciones para mejorar el análisis o incorporar nuevos modelos. Por favor, crea un issue o envía un pull request.
