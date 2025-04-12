# 📊 Data Standardization in Machine Learning

This project demonstrates the importance and implementation of **data standardization**, a preprocessing technique essential for many machine learning models to perform optimally.

---

## 🧠 What This Project Covers

- Why standardization is important
- Handling features with different scales
- Effects of standardization on model performance
- Using `StandardScaler` from `scikit-learn`

---

## 📝 Notebook Overview

The notebook `Data_standardization.ipynb` walks through:

1. **Loading Data**  
   Using the famous `iris` dataset from `sklearn`.

2. **Feature Scaling**  
   Applying `StandardScaler` to bring all features to the same scale.

3. **Comparison Before & After Scaling**  
   Showing the transformation with summary statistics and plots.

4. **Model Training & Evaluation**  
   Logistic Regression performance before and after standardization to highlight the impact.

---

## 📌 Key Libraries Used

```python
import pandas as pd
import numpy as np
from sklearn.datasets import load_iris
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score
