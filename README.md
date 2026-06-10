# Iris Flower Classification

## Overview
The Iris Flower Classification project is a machine learning application that predicts the species of an iris flower based on its physical measurements. It is one of the most popular beginner-friendly classification problems in machine learning and is widely used for learning data analysis, visualization, model training, and evaluation.

## Dataset Description
The project uses the Iris dataset, which contains measurements of iris flowers from three different species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

### Features
The dataset includes the following input features:

1. Sepal Length (cm)
2. Sepal Width (cm)
3. Petal Length (cm)
4. Petal Width (cm)

### Target Variable
The target variable is the flower species.

## Dataset Statistics

| Attribute | Value |
|-----------|--------|
| Total Samples | 150 |
| Features | 4 |
| Classes | 3 |
| Samples per Class | 50 |

## Project Objective
The objective of this project is to build a machine learning model that can accurately classify iris flowers into their respective species based on sepal and petal measurements.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Workflow

### 1. Data Collection
Load the Iris dataset from Scikit-learn or a CSV file.

### 2. Data Exploration
- Analyze dataset structure
- Check for missing values
- Generate statistical summaries
- Visualize feature distributions

### 3. Data Preprocessing
- Feature selection
- Data normalization/scaling (if required)
- Train-test split

### 4. Model Training
Train classification models such as:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

### 5. Model Evaluation
Evaluate performance using:
- Accuracy Score
- Confusion Matrix
- Classification Report
- Cross Validation

### 6. Prediction
Use the trained model to predict the species of new iris flowers.

## Example Input

```python
Sepal Length = 5.1
Sepal Width = 3.5
Petal Length = 1.4
Petal Width = 0.2
