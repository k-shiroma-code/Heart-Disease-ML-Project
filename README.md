# Heart_Disease-Prediction

This project predicts the presence of heart disease using machine learning techniques on the Cleveland heart disease dataset. The dataset contains multiple attributes, including features like age, cholesterol, resting blood pressure, and maximum heart rate achieved.

## Dataset Overview

The dataset contains medical records of patients with different attributes related to heart disease, which is classified into four categories:

- **Goal (Target Variable):**
  - 0: No presence of heart disease
  - 1, 2, 3, 4: Presence of heart disease (varying severity)

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

In this project, we perform the following steps:

1. **Data Loading:** Load and preprocess the Cleveland dataset.
2. **Exploratory Data Analysis (EDA):** Visualize the relationships between features and the target variable.
3. **Data Preprocessing:** Handle missing values and convert categorical features to numeric.
4. **Model Building:** Build a classification model using **Random Forest** to predict the presence of heart disease.
5. **Model Evaluation:** Evaluate the model's performance using metrics like accuracy, confusion matrix, classification report, and ROC curve.

## Technologies Used

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Link to dataset [Heart Disease Dataset page](https://archive.ics.uci.edu/dataset/45/heart+disease).

## License

This dataset is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

This project itself is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
