# Heart Disease Prediction
![heart]([link_to_your_image.png](https://partheniumprojects.com/wp-content/uploads/2018/12/heart-disease-prediction-3.png))


## Overview
This repository contains a project focused on heart disease prediction. The data, derived from heart patients, includes various health metrics such as age, blood pressure, heart rate, and more. The primary objective is to create a predictive model that accurately identifies individuals at risk of heart disease. The emphasis is on achieving a high recall to ensure no potential heart disease case is missed.

## Problem
In this project, we delve into a dataset encapsulating various health metrics from heart patients, including age, blood pressure, heart rate, and more. Our goal is to develop a predictive model capable of accurately identifying individuals with heart disease. Given the grave implications of missing a positive diagnosis, our primary emphasis is on ensuring that the model identifies all potential patients, making recall for the positive class a crucial metric.

## Objectives
The objectives of the project are as follows:

1. **Data Understanding:** Familiarize ourselves with the dataset and its features.
2. **Exploratory Data Analysis (EDA):**
    - Unveil patterns, trends, and relationships between different variables.
    - Perform univariate and bivariate analysis.
3. **Data Preprocessing:**
    - Remove irrelevant features
    - Address missing values
    - Treat outliers
    - Encode categorical variables
    - Transform skewed features to achieve normal-like distributions
    - Feature selection using RFECV
4. **Model Building:**
    - Develop and refine the prediction model using Logistic Regression.
    - Establish pipelines for models that require scaling
    - Implement and hyper parameter tunning
    - Emphasize achieving high recall for class 1, ensuring comprehensive identification of heart patients
5. **Evaluate and Compare Model Performance:** Utilize precision, recall, and F1-score to gauge models' effectiveness.

## Dataset
The dataset comprises various metrics related to heart health. The features of the dataset are described below:

| Variable Name | Description                                            |
|---------------|--------------------------------------------------------|
| age           | Age of the patient in years                            |
| sex           | Gender of the patient (0 = male, 1 = female)           |
| cp            | Chest pain type                                        |
| trestbps      | Resting blood pressure in mm Hg                        |
| chol          | Serum cholesterol in mg/dl                             |
| fbs           | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false).                              |
| restecg       | Resting electrocardiographic results                   |
| thalach       | Maximum heart rate achieved during a stress test       |
| exang         | Exercise-induced angina                                |
| oldpeak       | ST depression induced by exercise relative to rest     |
| slope         | Slope of the peak exercise ST segment                  |
| ca            | Number of major vessels colored by fluoroscopy         |
| thal          | Thalium stress test result, 3 = normal; 6 = fixed defect; 7 = reversible defect.                             |
| heart_diagnosis       | Diagnosis of heart disease (angiographic disease status) (0 = No heart disease, >0 = heart disease).                                   |

## File Descriptions
- `heart disease Prediction using Logistic Reg.ipynb`: Jupyter notebook containing all the data exploration, visualization, modeling, and evaluation code.
- `heart_disease.csv`: CSV file containing the heart disease data.
- `README.md`: This file, providing an overview of the project.

## How to Run
1. Clone this repository.
2. Open the `heart disease Prediction using Logistic Reg.ipynb` notebook in Jupyter.
3. Run all cells in the notebook.
