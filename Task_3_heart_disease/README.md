# 🫀 UCI Heart Disease Prediction — Internship Project

This project was part of my internship assignment where the goal was to **analyze the UCI Heart Disease dataset**, perform **data cleaning**, conduct **exploratory data analysis (EDA)**, and build **classification models** to predict heart disease.

---

## 📌 Instructions Followed

1. **Clean the dataset** (handle missing values if any).
2. **Perform EDA** to identify patterns, trends, and relationships.
3. **Train classification models** — Logistic Regression and Decision Tree.
4. **Evaluate models** using:
   - Accuracy
   - ROC Curve
   - Confusion Matrix
5. **Highlight important features** affecting prediction.

---

## 📊 Exploratory Data Analysis (EDA) — Key Observations

1. The **minimum age** to have heart disease starts from **28 years old**.
2. Most people get heart disease between **ages 53–54**.
3. Both **males and females** suffer from heart disease mostly between **54–55 years**.
4. The dataset has **78.91% males** and **21.09% females**.
5. Males are **274.23% more than females** in the dataset.
6. **Highest number of people** are from **Cleveland (304)**, lowest from **Switzerland (123)**.
7. **Highest number of females** are from **Cleveland (97)**, lowest from **Switzerland (6)**.
8. **Highest number of males** are from **Hungary (212)**, lowest from **Switzerland (113)**.
9. **Most common chest pain type** for males is **asymptomatic angina**.
10. Females also experience **asymptomatic angina** frequently.
11. The highest asymptomatic angina cases are from **Cleveland**, followed by **VA Long Beach**, least in **Switzerland**.
12. Both **males and females** face asymptomatic angina most often at **ages 56–57**, with **47 reported cases**.
13. Removed an **outlier in trestbps** where value was `0`.
14. Did **not remove outliers in chol** where value is `0` (not an outlier).
15. **trestbps** and **chol** show a **close relationship** (observed via scatter plot).
16. **Decision Tree Accuracy:** **62%**
17. **Logistic Regression Accuracy:** **50%**

---

## ⚙️ Models and Evaluation

### **1. Decision Tree Classifier**
- Accuracy: **62%**
- Metrics:
  - Confusion Matrix
  - ROC Curve
  - Feature Importance

### **2. Logistic Regression**
- Accuracy: **50%**
- Metrics:
  - Confusion Matrix
  - ROC Curve
  - Coefficient-based Feature Importance

---

## 📈 Metrics Used
- **Accuracy Score** → Measures correct predictions.
- **Confusion Matrix** → Shows prediction breakdown.
- **ROC Curve & AUC** → Measures classification performance.
- **Feature Importance** → Identifies most impactful features.

---

## 📦 Libraries Used
- **pandas** → Data loading and preprocessing  
- **numpy** → Numerical operations  
- **matplotlib** & **seaborn** → Data visualization  
- **scikit-learn** → Machine learning models and evaluation metrics  
- **joblib** → Saving trained models  

---

## 📌 Conclusion
This project provided hands-on experience in:
- **Data cleaning** and handling outliers.
- **Exploratory Data Analysis** to uncover trends in health data.
- **Model training and evaluation** for classification problems.
- **Feature importance analysis** to identify impactful health indicators.

While the Decision Tree achieved **62% accuracy** and Logistic Regression **50%**, the performance can be improved by:
- Applying **hyperparameter tuning**.
- Using **ensemble models** like Random Forest or Gradient Boosting.
- Performing **feature engineering** to capture hidden patterns.

---

## 📁 Dataset
The dataset used is the **UCI Heart Disease dataset** — publicly available [here](https://archive.ics.uci.edu/ml/datasets/heart+Disease).

---

## 🚀 How to Run
```bash
# Clone this repository
git clone https://github.com/yourusername/uci-heart-disease-prediction.git

# Install dependencies
pip install -r requirements.txt

# Run the script
python main.py
