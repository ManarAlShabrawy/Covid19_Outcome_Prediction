# Covid19_Outcome_Prediction

This repository contains a Jupyter Notebook for the **COVID-19 Outcome Prediction** project. In this project, we design different classifiers to predict the outcome (death/recovered) when a new person is admitted to the hospital. The following classifiers are used: K-Nearest Neighbors, Logistic Regression, Naïve Bayes, Decision Trees, and Support Vector Machines. A comparison of their performances is presented at the end.

## Project Overview

The main goal of this project is to predict whether a patient will recover or die after being admitted to the hospital due to COVID-19. To achieve this, we utilize a dataset containing 14 major variables that are likely to impact the outcome. The dataset is divided into three partitions: training, validation, and testing.

## Table of Contents

- **Importing Libraries:** Initial setup where necessary libraries and modules are imported.
- **Loading the Data:** The dataset is loaded and divided into predictor variables (X) and the target variable (Y).
- **Data Exploration:**
  - **Gender Distribution:** The distribution of patients across different genders is analyzed.
  - **Age Distribution:** The range of ages for patients in the dataset is visualized.
  - **Correlation Analysis:** The correlation between different variables in the dataset is visualized.
- **Data Balancing:**
  - **Imbalanced Classes:** The class distribution of the target variable is visualized.
  - **SMOTE Technique:** Synthetic Minority Over-sampling Technique (SMOTE) is applied to balance the classes.
- **Data Splitting and Normalization:**
  - The data is split into training and testing sets.
  - Data normalization is performed using StandardScaler.
- **Classifier Implementation and Evaluation:**
  - **K-Nearest Neighbor (KNN):**
    - Model training using grid search for optimal hyperparameters.
    - Performance metrics (precision, recall, F1-score, accuracy) are calculated and visualized.
    - ROC curve and AUC are plotted.
  - **Logistic Regression (LR):**
    - Model training using grid search for optimal hyperparameters.
    - Performance metrics (precision, recall, F1-score, accuracy) are calculated and visualized.
    - ROC curve and AUC are plotted.
  - **Naïve Bayes (GNB):**
    - Model training using grid search for optimal hyperparameters.
    - Performance metrics (precision, recall, F1-score, accuracy) are calculated and visualized.
    - ROC curve and AUC are plotted.
  - **Decision Tree (DT):**
    - Model training using grid search for optimal hyperparameters.
    - Performance metrics (precision, recall, F1-score, accuracy) are calculated and visualized.
    - ROC curve and AUC are plotted.
    - Visualization of the trained Decision Tree.
  - **Support Vector Machine (SVC):**
    - Model training using grid search for optimal hyperparameters.
    - Performance metrics (precision, recall, F1-score, accuracy) are calculated and visualized.
    - ROC curve and AUC are plotted.
- **Classifier Comparison:**
  - A summary table comparing the accuracy, precision, recall, F1-score, and ROC/AUC for all classifiers.

## How to Use

1. Clone this repository to your local machine using:  
   ```
   git clone https://github.com/your-username/covid-19-outcome-prediction.git
   ```

2. Navigate to the cloned repository's directory:
   ```
   cd covid-19-outcome-prediction
   ```

3. Open the Jupyter Notebook `COVID-19_Outcome_Prediction.ipynb` using Jupyter Notebook or Jupyter Lab.

4. Run the notebook cells in sequential order to load the data, implement classifiers, and evaluate their performance.

## Requirements

The project relies on the following libraries and modules:

- pandas
- numpy
- matplotlib
- sklearn
- seaborn
- imblearn
- yellowbrick
