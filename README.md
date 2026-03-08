# Stroke-prediction (the file contains in Dutch language)

Machine learning project to predict the likelihood of stroke using patient health data. 
The goal of this project is to analyze medical and demographic variables and build 
classification models that can identify people who may have a higher risk of stroke.

## Project Overview

Stroke is one of the leading causes of death and disability worldwide. Early prediction 
can help with prevention and medical intervention. In this project, different machine 
learning models are used to analyze patient data and predict whether a person is likely 
to experience a stroke.

The project was developed as part of the Applied Data Science & Artificial Intelligence program.

## Dataset

The dataset contains information about patients, including demographic and health-related 
features such as:

- age
- gender
- hypertension
- heart disease
- average glucose level
- BMI
- smoking status
- work type
- residence type

The target variable is **stroke**, where:
- 1 = patient had a stroke
- 0 = patient did not have a stroke

Files in this repository:

- `train.csv` → training dataset used to train the models  
- `test.csv` → dataset used for predictions  

## Methods

The project includes the following steps:

1. Data exploration and analysis (EDA)
2. Data preprocessing and cleaning
3. Feature analysis
4. Training classification models
5. Model evaluation and comparison

Several machine learning techniques can be used, such as:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Trees
- Random Forest
- Gradient Boosting

## Evaluation

Models are evaluated using common classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Because the dataset is imbalanced (stroke cases are rare), the **F1-score** is an important metric for evaluating model performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure
