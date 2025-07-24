# 🧪 Breast Cancer Classification using Random Forest

This project uses a **Random Forest Classifier** to predict whether a breast cancer tumor is **malignant** or **benign**.

The model is built and evaluated using **scikit-learn** on the popular Breast Cancer Wisconsin Dataset.

---

## 📁 Files

- `main.ipynb` – Jupyter Notebook containing data preprocessing, model training, evaluation, and predictions.
- `Cancer_Data.csv` – Dataset containing features and labels for tumor samples.

---

## 📊 Dataset Overview

- **Source**: [UCI ML Repository – Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Instances**: 569
- **Features**: 30 numeric features related to:
  - radius, texture, perimeter, area, smoothness, compactness, etc.
- **Target**: `diagnosis`
  - `M` = Malignant
  - `B` = Benign

---

## ⚙️ What This Notebook Does

1. Loads the dataset (`Cancer_Data.csv`)
2. Encodes the `diagnosis` column using `LabelEncoder` (`M` → 1, `B` → 0)
3. Scales the features using `StandardScaler`
4. Splits the dataset into training and test sets
5. Trains a **Random Forest Classifier**
6. Evaluates model performance using accuracy score
7. Makes predictions on the test set

---
