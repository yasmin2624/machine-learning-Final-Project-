# 🧠 Machine Learning Final Project

## 📝 Overview

This project consists of **two main parts**, each focusing on building and training machine learning models on different datasets to solve predictive problems.  
It covers the full workflow including **Exploratory Data Analysis (EDA)**, data preprocessing, model training, and evaluation.

---

## 🎯 Part 1: Predicting Student Performance

**Objective**:  
Build models to predict student performance in different tests (Math, Reading, Writing) based on social and personal factors.

**Dataset**:  
`StudentsPerformance.csv`

**Methodology**:

* **Exploratory Data Analysis**:  
  Examined data properties, checked for missing and duplicate values, generated descriptive statistics, and visualized variable relationships.
* **Data Preprocessing**:  
  Encoded categorical variables using `LabelEncoder` and scaled numerical features using `StandardScaler`.
* **Model Training**:  
  Trained multiple models including:
  * Linear Regression
  * Polynomial Regression
  * A simple Neural Network
  * Logistic Regression
  * Support Vector Machine (SVM)
* **Results**:  
  The Neural Network and Logistic Regression models achieved the best performance in this part of the project.

---

## ❤️ Part 2: Predicting Heart Disease

**Objective**:  
Predict the presence of heart disease based on a set of patient clinical attributes.

**Dataset**:  
`heart.csv` (from the UCI Machine Learning Repository)

**Methodology**:

* **Exploratory Data Analysis**:  
  Checked for missing or duplicate values and analyzed the distribution of key features.
* **Target Definition**:  
  Defined `target` as the dependent variable (indicating heart disease presence) and selected relevant features for prediction.
* **Model Training**:  
  Used a Logistic Regression model and evaluated it with:
  * Confusion Matrix
  * Classification Report
* **Results**:  
  The Logistic Regression model achieved high accuracy in predicting heart disease, demonstrating its effectiveness for this type of data.

---

## 🛠 Requirements

* Python 3.8+
* Jupyter Notebook

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
