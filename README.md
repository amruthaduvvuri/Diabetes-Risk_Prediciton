# 🧠 Diabetes Risk Prediction Model

A machine learning project that predicts the likelihood of diabetes in patients using health data from the PIMA Indian Diabetes Dataset. This project focuses on feature engineering, data preprocessing, model training, and insightful visualizations to support early healthcare intervention.

---

## 📁 Dataset

- **Source**: [Kaggle - PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Size**: 768 rows × 9 columns
- **Target Variable**: `Outcome` (0 = No diabetes, 1 = Diabetes)

---

## 🚀 Project Highlights

- Achieved **87% accuracy** and **82% precision** using Logistic Regression.
- Identified key features: `Glucose`, `BMI`, and `Age` as top predictors after correlation analysis and feature engineering.
- Visualized insights through heatmaps, ROC curves, and confusion matrices for enhanced interpretability.

---

## 📌 Key Steps

1. **Data Preprocessing**  
   - Handled missing and zero values in critical features (e.g., Glucose, BMI).  
   - Replaced with medians to preserve distribution.

2. **Exploratory Data Analysis (EDA)**  
   - Used correlation heatmaps and distribution plots to explore relationships between features.

3. **Feature Engineering & Scaling**  
   - Standardized features using `StandardScaler` for optimal model performance.

4. **Model Training & Evaluation**  
   - Trained Logistic Regression, evaluated with metrics like Accuracy, Precision, and ROC-AUC.

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn  

---

## 📊 Results

| Metric        | Value  |
|---------------|--------|
| Accuracy      | 87%    |
| Precision     | 82%    |
| ROC-AUC Score | 0.90   |

---

## 📈 Visualizations

- ✅ Correlation Heatmap  
- ✅ Confusion Matrix  
- ✅ ROC Curve  
- ✅ Feature Distributions

---
