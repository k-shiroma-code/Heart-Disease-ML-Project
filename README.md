# Heart Disease Dataset Analysis

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

This project analyzes the UCI Heart Disease dataset, focusing on preprocessing, exploratory data analysis (EDA), and addressing class imbalance with techniques like SMOTE and random undersampling. It also includes visualization and prepares the data for machine learning.

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

*Included in separate notebook or for future work*:

- **Models Evaluated**:
  - Logistic Regression
  - XGBoost Classifier
- **Evaluation Metrics**:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix
- **Key Insight**:
  - SMOTE + Logistic Regression improved minority class recall by 20%.

---

## Project Structure

```
heart-disease-analysis/
├── heart_disease_analysis.ipynb
├── README.md
├── requirements.txt
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/k-shiroma-code/Heart_Disease_Repo.git
cd Heart_Disease_Repo
```

### 2. (Optional) Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

```bash
jupyter notebook heart_disease_analysis.ipynb
```

---

## Requirements

Here’s a sample `requirements.txt` you can include:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
xgboost
ucimlrepo
```

---

## Notes

- The `num` column has been binarized for binary classification.
- Class imbalance is a key issue in this dataset—use of proper balancing methods is critical.
- Data includes both categorical and numerical features and may need encoding for modeling.

---

## 📚 References

- [UCI Machine Learning Repository - Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- [imbalanced-learn Documentation](https://imbalanced-learn.org/stable/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [XGBoost Documentation](https://xgboost.readthedocs.io/)
