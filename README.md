# 🩺 Diabetes Prediction using Machine Learning

This project aims to predict whether a person is diabetic or not based on medical diagnostic measurements.  
Multiple machine learning algorithms are applied and compared to identify the most accurate model.

---

## 📘 Project Overview

Diabetes is one of the most common chronic diseases, and early prediction can help prevent severe complications.  
In this project, various **machine learning models** were trained on the **PIMA Indian Diabetes dataset** to classify patients as diabetic or non-diabetic.

---

## 🧩 Dataset

- **Dataset Name:** diabetes.csv  
- **Source:** PIMA Indians Diabetes Database  
- **Number of Records:** 768  
- **Number of Features:** 8 (Glucose, BMI, Age, Insulin, etc.)  
- **Target Variable:** `Outcome` (0 = Non-diabetic, 1 = Diabetic)

---

## ⚙️ Data Preprocessing

1. Checked and handled missing values  
2. Converted categorical variables (if any)  
3. Normalized numeric columns using `StandardScaler`  
4. Split data into **80% training** and **20% testing**

---

## 🤖 Machine Learning Models Applied

| Algorithm | Accuracy | ROC-AUC |
|------------|-----------|----------|
| Logistic Regression | 0.78 | 0.82 |
| Decision Tree | 0.75 | 0.79 |
| Random Forest | 0.85 | 0.88 |
| SVM | 0.81 | 0.85 |
| KNN | 0.80 | 0.83 |
| Naive Bayes | 0.77 | 0.80 |

✅ **Random Forest** performed the best with the highest accuracy and ROC-AUC score.

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Correlation Heatmap
Shows the relationship among different features.  
![Correlation Heatmap](https://github.com/saiqakhalid/diabetes-prediction-ML/blob/main/correlation%20Heatmap.png)

### 🔹 Outcome Distribution
Distribution of diabetic vs non-diabetic cases.  
![Outcome Distribution](https://github.com/saiqakhalid/diabetes-prediction-ML/blob/main/Distribution%20of%20Diabetes%20outcom.png)

### 🔹 Feature Importance
Most influential features contributing to diabetes prediction.  
![Feature Importance](images/feature_importance.png)

---

## 📈 Model Evaluation

### 🔹 ROC Curve
Comparing the ROC curves of all models.
![ROC Curve](images/roc_curve.png)

### 🔹 Confusion Matrix
Illustrates true positive and false positive predictions.
![Confusion Matrix](images/confusion_matrix.png)

---

## 💡 Key Findings

- **Glucose**, **BMI**, and **Age** were the most important predictors.  
- Random Forest achieved the best classification performance.  
- Machine learning can significantly assist in early diabetes prediction.

---

## 🧠 Future Work

- Apply **Deep Learning (ANN/LSTM)** models  
- Increase dataset size for better generalization  
- Build a **web-based prediction app** using Streamlit or Flask

---

## 👩‍💻 Author

**Saiqa Khalid**  
* Machine Learning Researcher*  
📍 University of Haripur, Pakistan  
📧 [saiqakhalid2012@gmail.com]  

---

## 🏷️ Repository Structure

