# Machine Learning Final Project

## Overview
This project analyzes a **Students Performance** dataset and builds predictive regression models to estimate student scores.  
The goal is to explore data, clean it, and implement machine learning techniques to identify relationships between various factors and student performance.

## Features
- **Data Cleaning**  
  Handling missing values, duplicates, and ensuring correct data types.

- **Exploratory Data Analysis (EDA)**  
  - Statistical summaries  
  - Histograms, scatter plots, correlation heatmaps  

- **Feature Engineering**  
  - Label Encoding of categorical variables  
  - Feature scaling (StandardScaler)  
  - Polynomial feature generation for non-linear modeling  

- **Machine Learning Models**  
  - Linear Regression  
  - Polynomial Regression  

- **Model Evaluation**  
  - Mean Squared Error (MSE)  
  - R-squared (R²) score  

## Project Structure
machine-learning-Final-Project-/
│
├── Untitled58(3).ipynb # Jupyter Notebook with full code and analysis
├── Report.pdf # Detailed report discussing methodology and findings
├── README.md # This file
└── dataset/StudentsPerformance.csv # Dataset used in the project

## Requirements
- Python 3.x
- Libraries:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
Usage
Clone the repository:

git clone https://github.com/yasmin2624/machine-learning-Final-Project-.git
Open the Jupyter Notebook:

jupyter notebook Untitled58(3).ipynb
Run all cells sequentially to reproduce the analysis and model results.

Results
The analysis highlights trends and correlations between demographic/socioeconomic factors and academic scores.

Polynomial regression provided improved fit for some relationships compared to simple linear regression.

Evaluation metrics (MSE and R²) demonstrate the performance and reliability of the trained models.
