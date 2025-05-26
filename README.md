# **Heart Disease Dataset Analysis**  

This project explores **heart disease prediction** using the **UCI dataset**, emphasizing **data preprocessing**, **class imbalance correction**, and **model evaluation** to enhance predictive accuracy.  

---

## **Dataset Overview**  

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease)  
- **Dataset ID**: `45`  
- **Target Variable**: `num` (binarized: `0` = No disease, `1` = Presence of disease)  
- **Features**:  
  - **Demographics**: Age, sex  
  - **Symptoms**: Chest pain type  
  - **Clinical Measures**: Resting blood pressure, cholesterol, fasting blood sugar, ECG results, max heart rate, exercise-induced angina  
  - **Advanced Diagnostics**: ST depression (`oldpeak`), slope, number of major vessels (`ca`), thalassemia  

---

## **Tools & Libraries Used**  

- **Programming Language**: Python  
- **Libraries**:  
  - **Data Handling**: `pandas`, `numpy`  
  - **Visualization**: `matplotlib`, `seaborn`  
  - **Machine Learning**: `scikit-learn`  
  - **Class Imbalance Handling**: `imbalanced-learn` (`SMOTE`, `RandomUnderSampler`)  
  - **Dataset Access**: `ucimlrepo`  

---

## **Exploratory Data Analysis (EDA)**  

Key visualizations created to assess patterns in the dataset:  

- **Age Distribution**  
- **Age vs Heart Disease Presence**  
- **Sex Distribution by Target Variable**  
- **Histograms of Continuous Features**  
- **Class Imbalance Check**  

---

## **Data Preprocessing**  

- **Handling Missing Values**:  
  - **Numerical Features**: Imputed with column mean  
  - **Categorical Features**: Filled with most frequent category  
- **Encoding**:  
  - Converted categorical variables into numerical representations  
- **Class Balancing**:  
  - **SMOTE**: Oversampled minority class  
  - **Random Undersampling**: Reduced majority class  

---

## **Machine Learning Models**  

- **Models Evaluated**:  
  - Logistic Regression  
  - GridSearch CV 
- **Evaluation Metrics**:  
  - Accuracy  
  - Precision, Recall, F1-score  
  - Confusion Matrix  
- **Key Insights**:  
  - **SMOTE + Logistic Regression** improved minority class recall by **20%**.  
  - **Number of major vessels (`ca`)** was identified as the most influential predictor in classification outcomes.  

---

