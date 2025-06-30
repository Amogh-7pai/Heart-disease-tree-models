# Heart Disease Prediction using Decision Tree & Random Forest

This project focuses on predicting heart disease using **Decision Tree** and **Random Forest** classifiers. We use the `heart.csv` dataset and evaluate the models with metrics like accuracy, cross-validation, and feature importance.

---

## 📁 Dataset
- **File:** `heart.csv`
- **Target Variable:** `target` (0 = no disease, 1 = disease)

---

## 🧠 Models Used
- Decision Tree Classifier
- Pruned Decision Tree (with max depth control)
- Random Forest Classifier

---

## ✅ Steps Covered
- Data cleaning & preprocessing
- Train/test split and feature scaling
- Train and visualize a decision tree
- Handle overfitting with max depth
- Train and evaluate a random forest
- Plot feature importances
- Perform cross-validation

---

## 🛠️ Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📊 Results
- Random Forest outperformed single decision trees in accuracy and robustness.
- Pruning the decision tree reduced overfitting.
- Features like `cp`, `thalach`, and `oldpeak` were highly important.


