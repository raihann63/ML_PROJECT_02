# ML_PROJECT_02
# Credit Mix Prediction Project

## Overview
This project aims to predict the credit mix category for customers based on their financial data. The goal is to provide actionable insights that can help improve customers' credit health. The dataset contains various financial attributes of customers, and the model will classify the credit mix into different categories.

## Table of Contents
- [Dataset Overview](#dataset-overview)
- [Project Workflow](#project-workflow)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Building](#model-building)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Final Performance and Cross-Validation](#final-performance-and-cross-validation)
- [Actionable Insights](#actionable-insights)
- [Installation](#installation)
- [Usage](#usage)

## Dataset Overview
- **Source**: The dataset can be accessed from [this link](https://raw.githubusercontent.com/rashakil-ds/Public-Datasets/refs/heads/main/Bank%20Data.csv).
- **Columns**:
  - `ID`: Unique identifier for each record.
  - `Customer_ID`: Identifier for the customer.
  - `Month`: Month of the record.
  - `Name`: Name of the customer.
  - `Age`: Age of the customer.
  - `Occupation`: Customer's occupation.
  - `Annual_Income`: Annual income of the customer.
  - `Monthly_Inhand_Salary`: Monthly salary after deductions.
  - `Num_Bank_Accounts`: Number of bank accounts held.
  - `Num_Credit_Card`: Number of credit cards held.
  - `Credit_Mix`: Target variable indicating the credit mix category.
  - Other financial attributes related to credit history and behavior.

### Sample Data
| ID      | Customer_ID | Month     | Name          | Age | Occupation | Annual_Income | Monthly_Inhand_Salary | ... | Credit_Mix |
|---------|-------------|-----------|---------------|-----|------------|----------------|-----------------------|-----|------------|
| 0x160a  | CUS_0xd40   | September | Aaron Maashoh | 23  | Scientist  | 19114.12       | 1824.84               | ... | Good       |
| 0x160b  | CUS_0xd40   | October   | Aaron Maashoh | 24  | Scientist  | 19114.12       | 1824.84               | ... | Good       |

## Project Workflow
The project follows a structured workflow to ensure a systematic approach to data analysis and model building.

### 1. Data Preprocessing
- Handle missing and invalid values in the dataset.
- Encode categorical variables appropriately.
- Scale and normalize numeric features for uniformity.
- Detect and address outliers to improve model stability.

### 2. Exploratory Data Analysis (EDA)
- Perform descriptive statistics to understand the data distribution.
- Visualize relationships between features and the target variable.
- Analyze correlations and identify trends or anomalies in the data.

### 3. Model Building
- Initialize and train multiple models (e.g., Random Forest, SVM, KNN).
- Evaluate model performance using metrics such as accuracy, precision, recall, and F1 score.

### 4. Hyperparameter Tuning
- Use GridSearchCV to find the best hyperparameters for each model.
- Retrain models using optimal hyperparameters.

### 5. Final Performance and Cross-Validation
- Evaluate the final performance of each model using cross-validation scores.
- Compare results to select the best-performing model.

### 6. Actionable Insights
- Provide recommendations based on the model insights and analysis.
- Suggest actionable steps to improve outcomes or address any gaps identified during the project.

## Conclusion
This project provides a comprehensive approach to predicting credit mix categories based on customer financial data. The insights generated can help customers improve their credit health and make informed financial decisions.
