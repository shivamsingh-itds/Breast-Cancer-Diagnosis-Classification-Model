# Breast Cancer Diagnosis Classification using Machine Learning

## 📌 Project Overview
This project focuses on building a machine learning classification model to predict whether a breast tumor is **benign or malignant** using the **Breast Cancer Wisconsin Diagnostic Dataset**.  
The objective is to demonstrate an end-to-end ML workflow including exploratory data analysis, feature engineering, model training, and evaluation.

---

## 📂 Dataset
- **Source:** Breast Cancer Wisconsin Diagnostic Dataset
- **Target Variable:** `diagnosis`
  - `0` → Benign  
  - `1` → Malignant
- **Features:** 30 numerical tumor characteristics such as radius, texture, perimeter, area, concavity, etc.

The dataset is clean with **no missing values**, making it suitable for focused analysis and modeling.

---

## 🔍 Exploratory Data Analysis (EDA)
Key EDA steps performed:
- Target class distribution analysis
- Feature-wise comparison between benign and malignant tumors
- Correlation analysis to identify highly influential features
- Visualization using boxplots and correlation heatmaps

**Key Insight:**  
Malignant tumors generally exhibit higher values for size-related and irregularity-related features such as radius, area, and concavity.

---

## 🧠 Feature Engineering
To enhance model interpretability and capture tumor behavior, additional engineered features were created:
- `radius_area_ratio`
- `perimeter_radius_ratio`
- `area_worst_ratio`
- `concavity_ratio`
- `texture_variation`

These features help represent tumor shape, growth aggressiveness, and boundary severity.

---

## ⚙️ Machine Learning Models
Models used in this project:
- Logistic Regression (baseline)
- Random Forest Classifier
- Support Vector Machine (optional)

Feature scaling was applied for distance-based models.

---

## 📊 Model Evaluation
Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Emphasis was placed on **recall and F1-score**, considering the medical importance of minimizing false negatives.

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Environment:** Jupyter Notebook  

---

## ✅ Conclusion
This project demonstrates how structured EDA and thoughtful feature engineering can significantly improve model understanding and performance in a real-world medical classification problem.

---

## 🚀 Next Steps
- Hyperparameter tuning
- Model explainability (SHAP)
- Deployment using Streamlit

---

## 👤 Author

**Shivam Singh**
Aspiring Data Scientist | Machine Learning Enthusiast

🔗 GitHub: [https://github.com/shivamsingh-itds]
🔗 LinkedIn: [www.linkedin.com/in/shivamsinghds]

---

⭐ If you find this project helpful, feel free to star the repository!