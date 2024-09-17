# Machine Learning Techniques For Detecting Chronic Kidney Disease

## Overview
This project focuses on applying machine learning techniques to detect Chronic Kidney Disease (CKD) using a medical dataset. The primary model used in this project is **Logistic Regression** to classify patients based on various health metrics. The dataset contains information on patients’ age, blood pressure, blood sugar levels, and other clinical variables, which are used to predict the likelihood of chronic kidney disease.

## Objectives
- **Preprocess** the medical dataset, handling missing values, encoding categorical variables, and scaling features where necessary.
- Conduct **Exploratory Data Analysis (EDA)** to uncover insights about key features and their correlation with CKD.
- Apply **Logistic Regression** to predict whether a patient has CKD or not.
- Evaluate the model's performance using metrics such as **precision**, **recall**, **F1-score**, and **accuracy**.

## Dataset
The dataset used for this project contains the following key features:
- **Age**: Age of the patient
- **Blood Pressure (bp)**: Blood pressure levels
- **Specific Gravity (sg)**: A measure of the concentration of urine
- **Albumin (al)**: A type of protein
- **Blood Sugar (su)**: Blood sugar levels
- ... and several other medical indicators.

The target variable is the **classification** label that indicates whether a patient has CKD or not.

## Key Steps
1. **Data Preprocessing**:
   - Handled missing values and inconsistencies in the dataset.
   - Encoded categorical variables like red blood cells (rbc), pus cell (pc), and others.
   - Normalized numerical features to improve model performance.
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualized important features and their distributions.
   - Checked for correlations between features and the target variable (CKD).
   
3. **Modeling with Logistic Regression**:
   - Used Logistic Regression as the primary classification model.
   - Evaluated the model with a **classification report**, obtaining perfect precision, recall, and F1-scores.

## Results
The Logistic Regression model performed with an accuracy of **100%** on the test dataset. However, it’s essential to evaluate this result further to check for potential overfitting and ensure the model generalizes well to new data.


