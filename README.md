# Breast-cancer-dataset
analyzing the breast cancer dataset
# 🔍 Breast Cancer Classification with Logistic Regression

## 📌 Overview
This project is part of an AI & ML internship task where I built a **binary classification model** using **Logistic Regression** to detect whether a tumor is benign or malignant based on clinical features.
---
## 📂 Dataset
- **Name**: Breast Cancer Wisconsin Diagnostic Dataset  
- **Source**: [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)  
- **Target**: `diagnosis` → Malignant (M = 1) or Benign (B = 0)
---
## 🧰 Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
---
## 📈 Workflow
1. **Loaded and cleaned** the dataset
2. **Converted** categorical diagnosis labels to binary values
3. **Standardized** features using `StandardScaler`
4. **Split** the dataset into training and testing sets
5. **Trained** a logistic regression model
6. **Evaluated** model performance with:
   - Confusion matrix
   - Precision, Recall, F1-Score
   - ROC-AUC score
   - ROC Curve visualization
---
## 📊 Model Evaluation
| Metric          | Score     |
|------------------|-----------|
| Accuracy         | 0.96      |
| Precision        | 0.95      |
| Recall           | 0.97      |
| F1-Score         | 0.96      |
| ROC-AUC Score    | 0.99      |
---
## 📉 ROC Curve  
![ROC Curve](./roc_curve.png) <!-- Optional if you've saved your plot -->
---
👩‍💻 Author
Name: Kaviya Varshini  
Institute: Avinashilingam Institute, Coimbatore  
Program: B.E- Artificial Intelligence and Data Science  
