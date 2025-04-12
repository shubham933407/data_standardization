# data_standardization
# Data Standardization in Machine Learning

This project focuses on **Data Standardization**, a crucial preprocessing step in machine learning workflows. It ensures that features have a common scale without distorting differences in the ranges of values.

## 📁 Files Included

- `Data_standardization.ipynb`: The main notebook demonstrating standardization techniques using `sklearn`, `pandas`, and `numpy`.

## 📌 Key Concepts Covered

- What is Data Standardization?
- Why standardization is important in ML models like SVM, Logistic Regression, and KNN.
- Implementing:
  - Z-score normalization
  - Min-Max scaling
  - StandardScaler from `sklearn`

## 🧪 Sample Workflow

```python
from sklearn.preprocessing import StandardScaler
scaler = StandardScaler()
scaled_data = scaler.fit_transform(data)
o
