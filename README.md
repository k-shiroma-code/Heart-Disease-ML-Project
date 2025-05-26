# Heart Disease Dataset Analysis

This project explores heart disease prediction using the UCI dataset, focusing on preprocessing, class imbalance correction, and model evaluation to improve predictive accuracy.

---

## Dataset Overview

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Dataset ID**: 45  
- **Target Variable**: `num` (binarized: 0 = no disease, 1 = presence of disease)
- **Features**:
  - Age, sex, chest pain type
  - Resting blood pressure, cholesterol
  - Fasting blood sugar, ECG results
  - Max heart rate, exercise-induced angina
  - ST depression (`oldpeak`), slope, number of vessels, thalassemia

---

## Tools and Libraries Used

- **Language**: Python  
- **Libraries**:
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `xgboost`
  - Class Imbalance Handling: `imbalanced-learn` (`SMOTE`, `RandomUnderSampler`)
  - Dataset Access: `ucimlrepo`

---

## Exploratory Data Analysis (EDA)

The following visualizations were created to explore the dataset:

- Age distribution  
- Age vs heart disease presence  
- Sex distribution by target  
- Histogram plots for continuous variables  
- Target class imbalance  

---

## Data Preprocessing

- **Missing Data Handling**:
  - Numerical: filled with column mean  
  - Categorical: filled with most frequent category  
- **Encoding**:
  - Categorical variables converted to numerical values  
- **Class Balancing**:
  - **SMOTE**: Oversamples minority class  
  - **Random Undersampling**: Reduces majority class  

---

## Machine Learning Models

- **Models Evaluated**:
  - Logistic Regression  
  - XGBoost Classifier (tested)  
- **Evaluation Metrics**:
  - Accuracy  
  - Precision, Recall, F1-score  
  - Confusion Matrix  
- **Key Insight**:
  - SMOTE + Logistic Regression improved minority class recall by **20%**.  

---

## Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost ucimlrepo
