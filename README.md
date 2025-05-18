# Heart Disease Dataset Analysis

This project explores the UCI Heart Disease dataset, focusing on data preprocessing, visualization, and handling class imbalance using techniques like SMOTE and random undersampling.

## 📂 Dataset

- **Source**: UCI Machine Learning Repository  
- **Dataset Name**: Heart Disease (ID: 45)  
- **Features**: Age, sex, chest pain type, blood pressure, cholesterol, fasting blood sugar, ECG results, max heart rate, exercise-induced angina, oldpeak, slope, number of vessels colored, thalassemia  
- **Target**: `num` (presence of heart disease)

## 🛠️ Tools and Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- imbalanced-learn (`SMOTE`, `RandomUnderSampler`)
- ucimlrepo (for loading the dataset)

## 📊 Visualizations

- Age distribution
- Age distribution by heart disease status
- Sex distribution
- Class distribution of target variable
- Histograms of numerical features

## 🔄 Preprocessing

- Imputation of missing numerical values (mean strategy)
- Imputation of missing categorical values (most frequent strategy)
- Class balancing:
  - **SMOTE**: Oversampling the minority class
  - **Random Undersampling**: Reducing the majority class

## 🧪 Modeling (optional section if you add ML later)

You can include classifiers like Logistic Regression, Random Forest, etc., to predict heart disease presence.

## 📁 Project Structure

```
heart-disease-analysis/
│
├── heart_disease_analysis.ipynb
├── README.md
├── requirements.txt (optional)
```

## 🚀 How to Run

1. Clone the repository
2. Set up a virtual environment (optional but recommended)
3. Install dependencies:  
   ```
   pip install -r requirements.txt
   ```
4. Run the notebook:  
   Open `heart_disease_analysis.ipynb` in JupyterLab or VS Code.

## 📌 Notes

- The target `num` is binarized (0 = no disease, 1 = disease).
- Dataset contains some categorical columns represented as `object` and needs conversion if used in modeling.

## 📚 References

- [UCI ML Repository - Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
