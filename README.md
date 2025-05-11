#  Cardiovascular_Disease-Prediction

This project predicts the presence of Cardiovascular disease using machine learning techniques on the Cleveland heart disease dataset. The dataset contains multiple attributes, including features like age, cholesterol, resting blood pressure, and maximum heart rate achieved.

## Dataset Overview

The dataset contains medical records of patients with different attributes related to Cardiovascular disease, which is classified into four categories:

- **Goal (Target Variable):**
  - 0: No presence of Cardiovascular disease
  - 1, 2, 3, 4: Presence of Cardiovascular disease (varying severity)

- **Features:**
  - Age
  - Sex
  - Chest pain type
  - Resting blood pressure
  - Serum cholesterol
  - Fasting blood sugar
  - Electrocardiographic results
  - Maximum heart rate achieved
  - Exercise-induced angina
  - ST depression induced by exercise
  - Slope of the peak exercise ST segment
  - Number of major vessels colored by fluoroscopy
  - Thalassemia (a blood disorder)

## Project Description

Steps to achieve project outcome

1. **Data Loading:** Load and preprocess the Cleveland dataset.
2. **Exploratory Data Analysis (EDA):** Visualize the relationships between features and the target variable.
3. **Data Preprocessing:** Handle missing values and convert categorical features to numeric.
4. **Model Building:** Build a classification model using **Random Forest** to predict the presence of Cardiovascular disease.
5. **Model Evaluation:** Evaluate the model's performance using metrics like accuracy, confusion matrix, classification report, and ROC curve.

## Technologies Used

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Summary & Findings
The project successfully built and optimized a Random Forest Classifier for Cardiovascular disease prediction using the Cleveland Heart Disease Database. The model achieved 90% accuracy and provided insights into the most significant features influencing heart disease, such as Coronary Artery Disease and Chest Pain Type. The balanced performance across both classes (heart disease vs. no disease) and the model’s high precision, recall, and F1-score demonstrate its effectiveness for real-world heart disease prediction.

Link to dataset [Heart Disease Dataset page](https://archive.ics.uci.edu/dataset/45/heart+disease).

## License

This dataset is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.
