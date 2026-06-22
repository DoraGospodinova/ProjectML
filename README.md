# ProjectML
# Comparative Analysis of Machine Learning Models for Heart Disease Prediction Using MLflow

## Project Overview

This project presents the implementation and comparison of several machine learning algorithms for predicting the presence of heart disease based on patient medical data.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, feature importance analysis, and experiment tracking using MLflow.

## Dataset

The project uses the **Heart Disease (Cleveland) Dataset** from the UCI Machine Learning Repository.

The dataset contains clinical features such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise Induced Angina
* ST Depression (Oldpeak)
* Number of Major Vessels
* Thalassemia

The target variable indicates whether heart disease is present or absent.

## Machine Learning Models

The following supervised learning algorithms were implemented and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

## Project Workflow

* Data loading
* Data preprocessing
* Exploratory Data Analysis (EDA)
* Train/Test split
* Feature scaling
* Model training
* Model evaluation
* Model comparison
* Feature importance analysis
* MLflow experiment tracking

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## Technologies

* Python 3.11
* Jupyter Notebook
* pandas
* NumPy
* scikit-learn
* matplotlib
* seaborn
* MLflow

## Running the Project

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Launch the MLflow tracking server:

```bash
mlflow ui
```

Open your browser and navigate to:

http://127.0.0.1:5000