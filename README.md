***Cardiovascular Disease (CVD) Prediction***

**Project Overview**

This project focuses on predicting Cardiovascular Disease (CVD) using machine learning. CVD is one of the leading causes of death worldwide, and early detection can help reduce risks and save lives.

I used the Cardiovascular Disease dataset from Kaggle, cleaned it, and built models to check if a person may have CVD based on health factors such as age, blood pressure, cholesterol, and lifestyle habits.

**Steps in the Project**

*Data Collection & Cleaning*

- Dataset had over 70,000 patient records.

- Removed unrealistic values (like negative blood pressure or extremely low weights).

- Converted age from days into years.

- Removed outliers for better accuracy.

*Exploratory Data Analysis (EDA)*

- Looked at patterns and distributions of age, blood pressure, cholesterol, etc.

- Used plots and statistics to better understand the data.

*Model Building* 

Built three machine learning models:

- Logistic Regression

- Decision Tree

- Random Forest

Tuned hyperparameters to improve performance.

*Model Evaluation*

- Compared models using accuracy, precision, recall, F1 score, and ROC-AUC.

- Logistic Regression performed the best overall.

**Key Results**

Top Risk Factors Identified:

- Systolic Blood Pressure

- Age

- Cholesterol Levels

Best Model: Logistic Regression (slightly better than Decision Tree and Random Forest).

Performance: All models gave similar results, with ROC-AUC around 0.78.

**Tools & Libraries Used**

- Python

- Scikit-learn

- Matplotlib

- Pandas & NumPy

- Google Colab

**Dataset**

- Source: [Cardiovascular Disease Dataset on Kaggle](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)

**Conclusion**

This project showed that machine learning can help predict CVD and highlight the most important risk factors. Even with simple models, valuable insights can be gained. With more data and advanced techniques, predictions could be made even stronger.
