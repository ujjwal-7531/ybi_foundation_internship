# 🧠 Breast Cancer Diagnosis with Deep Learning

This project applies a deep learning model to classify breast cancer tumors as **malignant** or **benign** using the [Breast Cancer Wisconsin Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).

The goal is to demonstrate how deep learning techniques (using TensorFlow/Keras) can be used to solve binary classification problems in medical diagnostics.

---

## 📁 Files

- `main.ipynb` – Jupyter Notebook containing all the preprocessing, model building, training, evaluation, and predictions.
- `Cancer_Data.csv` – Dataset containing features and diagnosis information of breast cancer biopsies.

---

## 📊 Dataset Summary

- **Features**: 30 numerical features such as radius, texture, smoothness, etc.
- **Target**: `diagnosis` (Benign = 0, Malignant = 1)
- **Total samples**: ~569

---

## ⚙️ How It Works

1. **Load the dataset**
2. **Encode the target variable** (`diagnosis`) using `LabelEncoder`
3. **Scale features** with `StandardScaler`
4. **Split data** into training and test sets
5. **Build a deep learning model** with TensorFlow/Keras
6. **Train the model** using the training data
7. **Evaluate performance** on the test set
8. **Make predictions** and analyze results

---
