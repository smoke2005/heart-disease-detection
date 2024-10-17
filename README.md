# Heart Attack Risk Prediction

## Project Overview

This project involves developing machine learning models to predict the risk of heart attack in patients based on medical data. The model uses several medical features and classifies patients into risk categories, helping in early diagnosis and treatment.

## Table of Contents
- [Aim](#aim)
- [Features Offered](#features-offered)
- [Libraries Used](#libraries-used)
- [Integration/Execution Sequence](#integrationexecution-sequence)
- [Files Used](#files-used)
- [Compilers Used](#compilers-used)
- [Acknowledgements](#acknowledgements)

## Aim

The Heart Attack Risk Prediction system aims to classify patients based on their likelihood of suffering from a heart attack. By using machine learning techniques, the project seeks to provide an accurate, interpretable, and efficient solution to help healthcare providers make informed decisions.

## Features Offered
- Data preprocessing, including handling of missing values and outlier removal.
- Exploratory Data Analysis (EDA) for better understanding of medical attributes.
- Logistic Regression model for binary classification (heart attack: yes/no).
- Probability prediction of heart attack risk.
- Visualization of data distribution, outlier detection, and correlation matrix.
- Model evaluation metrics like Accuracy, Precision, Recall, and F1 Score.

## Libraries Used
- **Python Standard Libraries:**
  - `pandas`: For handling datasets and data manipulation.
  - `numpy`: For mathematical operations and handling arrays.
  - `matplotlib` & `seaborn`: For data visualization.
  - `scikit-learn`: For machine learning model building, training, and evaluation.
  
- **Custom Functions:**
  - Data preprocessing, outlier detection, visualization, and model evaluation functions.

## Integration/Execution Sequence
1. **Data Preprocessing**  
   Handles missing values by filling them with the mean, removes outliers, and standardizes the data.
   
2. **Exploratory Data Analysis (EDA)**  
   Visualizes key features such as Age, Cholesterol, Chest Pain type, and Blood Pressure to gain insights into the dataset.
   
3. **Model Building**  
   Logistic Regression is chosen for heart attack prediction due to its suitability for binary classification tasks. The dataset is split into training and testing sets.
   
4. **Model Evaluation**  
   The model’s performance is evaluated using various metrics like accuracy, precision, recall, and F1 score. A confusion matrix is also generated to assess prediction accuracy.

5. **Prediction and Result Visualization**  
   The results are visualized using a confusion matrix, and probability scores are provided for each prediction.

## Files Used
- **Dataset File**: heart.csv Contains patient data with medical attributes and heart disease status.
- Source code is a jupyter notebook that contains the code.

## Compilers Used
- Python 3.x using Jupyter Notebook

## Acknowledgements
This project was developed as a part of [UCS2202 – Foundations of Data Science] in the Second Semester of the B.E. Computer Science and Engineering program offered by SSN Institutions.
