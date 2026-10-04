# Iris Flower Classification Using Machine Learning

## Internship Track
**Data Science – Oasis Infobyte Internship**

## Project Overview

This project focuses on building a machine learning classification model to
identify the species of an Iris flower based on its physical measurements.

The Iris dataset contains measurements of four flower characteristics:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Using these measurements, the model predicts one of three Iris species:

- Setosa
- Versicolor
- Virginica

Two machine learning classification algorithms are implemented and compared:

1. Logistic Regression
2. K-Nearest Neighbours (KNN)

---

## Objective

The main objective of this project is to develop and evaluate machine learning
classification models that can accurately classify Iris flowers into their
respective species.

The project also demonstrates the complete machine learning workflow,
including:

- Data loading
- Data inspection
- Exploratory Data Analysis
- Data visualization
- Feature analysis
- Train-test splitting
- Feature scaling
- Model training
- Model evaluation
- Model comparison
- Best model selection

---

## Dataset

The Iris dataset is a built-in dataset provided by the
`scikit-learn` library, so no external dataset download is required.

### Dataset Details

- Total samples: 150
- Number of input features: 4
- Number of classes: 3
- Samples per class: 50

### Features

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal in centimeters |
| Sepal Width | Width of the sepal in centimeters |
| Petal Length | Length of the petal in centimeters |
| Petal Width | Width of the petal in centimeters |

### Target Classes

- Setosa
- Versicolor
- Virginica

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Exploratory Data Analysis

The dataset was analyzed using several EDA techniques.

### Data Inspection

The following checks were performed:

- Dataset shape
- Data types
- Missing/null values
- Descriptive statistics
- Class distribution

No missing values were found in the dataset.

### Data Visualization

The following visualizations were created:

- Species distribution chart
- Pairplot
- Box plots
- Model accuracy comparison
- Confusion matrices

---

## Feature Analysis

The pairplot and box plots show that **Petal Length** and **Petal Width**
are particularly useful for distinguishing between Iris species.

Setosa is clearly separated from the other species based on its petal
measurements. Versicolor and Virginica have some overlap, but their petal
measurements still provide strong classification information.

All four features were retained for model training.

---

## Machine Learning Models

### 1. Logistic Regression

Logistic Regression was used as one of the classification models.

The features were standardized before training to improve model performance.

### 2. K-Nearest Neighbours

K-Nearest Neighbours (KNN) was used as the second classification model.

The value of `k` was set to 5.

Feature scaling was applied because KNN is a distance-based algorithm.

---

## Train-Test Split

The dataset was divided into:

- **80% training data**
- **20% testing data**

A fixed random state was used to make the experiment reproducible.

---

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The classification reports and confusion matrices provide detailed
information about the performance of each model for all three Iris species.

---

## Model Comparison

The accuracy of Logistic Regression and K-Nearest Neighbours was compared.

The model achieving the highest test accuracy was selected as the
best-performing model.

The exact results are available in the Jupyter Notebook.

---

## Project Structure

```text
DataScience-Task1-IrisFlowerClassification/
│
├── Iris_Flower_Classification.ipynb
└── README.md