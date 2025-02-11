# 🌍 Classification of Countries by Energy Risk

This repository contains the complete development of the final project for the **Bootcamp Talento Tech**, focused on classifying countries based on their energy risk levels using advanced machine learning techniques.

## 📌 Description

The project addresses a critical issue for global sustainability: identifying and classifying countries according to their **High**, **Medium**, or **Low** energy risk. This is achieved using public data on energy consumption, renewable energy, access to clean fuels, among other factors.

The developed model integrates **data cleaning**, **feature engineering**, **dimensionality reduction with PCA**, and classification algorithms such as **Random Forest** and **Decision Trees**. Additionally, it includes strategies to handle **class imbalance using SMOTE** and **hyperparameter optimization with GridSearchCV**.

## 📂 Project Structure

- **01_Introduction**: Problem context, objectives, and global relevance.
- **02_Data Preparation**: Data cleaning, missing value imputation, and dimensionality reduction.
- **03_Modeling**: Training classification models (Random Forest, Decision Trees).
- **04_Evaluation**: Metrics such as Accuracy, Confusion Matrix, F1-Score, and ROC-AUC curves.
- **05_Optimization**: Using GridSearchCV to find the best hyperparameters.

## 🔧 Requirements

- **Python 3.8+**
- Required libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `imbalanced-learn`

To install all dependencies:
```bash
pip install -r requirements.txt


Execution:

    Clone this repository:

git clone https://github.com/usuario/repositorio.git

Execute the Jupyter Notebook file:

    jupyter notebook Final_project_talento_tech.ipynb

Results:

    Precisión del modelo: 98.5%
    ROC-AUC promedio: 99.7%
    Visualización del modelo de Árbol de Decisión optimizado.

Contributions:

Contributions are accepted to improve the analysis or incorporate new models. Please create an issue or submit a pull request.
