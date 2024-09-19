# Diabetes Prediction Using Machine Learning

## Project Overview
This project focuses on predicting whether a patient has diabetes based on medical data, using machine learning models. The dataset used is a collection of medical records, including factors such as age, glucose levels, insulin, and more. The goal is to create a predictive model that can estimate the likelihood of diabetes based on these medical indicators.

## Dataset
The dataset consists of the following key features:

- `Pregnancies`: Number of times pregnant
- `Glucose`: Plasma glucose concentration (mg/dL)
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skinfold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg/(height in m)^2)
- `DiabetesPedigreeFunction`: A function that scores the likelihood of diabetes based on family history
- `Age`: Age (years)
- `Outcome`: Class variable (0 if non-diabetic, 1 if diabetic)

The `Outcome` column serves as the target variable for model training, but if it's not available, the model will predict the likelihood of diabetes based on the other features.

## Objective
The objective is to use machine learning to predict the likelihood of diabetes in a patient, based on medical and demographic data.

## Project Workflow

1. **Data Loading**: 
   - The dataset is loaded into a pandas DataFrame.
   
2. **Data Preprocessing**:
   - Checked for missing values.
   - Scaled the features for better performance.
   - Split the data into training and testing sets to evaluate model performance.
   
3. **Model Building**:
   - **Random Forest**: A robust ensemble learning method.
   
4. **Model Evaluation**:
   - Accuracy score to evaluate the model’s performance.
   - Confusion Matrix to analyze correct and incorrect predictions.
   - Classification report to check precision, recall, and F1-score.

5. **Prediction**: 
   - The model predicts whether the patient is diabetic (`1`) or non-diabetic (`0`) based on the medical features.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kaggle/diabetes-prediction.git

2.Navigate into the project folder:

3.Install the required dependencies:
  
  pip install -r requirements.txt
