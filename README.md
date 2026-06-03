# Disaster-Event-Severity-Prediction-System_Spirit2

# 🚀 Model Building and Evaluation

## 📌 Overview

In this phase of the project, multiple machine learning classification models were trained and evaluated to predict whether a disaster event is classified as a major disaster (`is_major_disaster`). The dataset was preprocessed, encoded, scaled where necessary, and split into training and testing sets before model training.

---

## 🤖 Models Implemented

The following classification algorithms were trained and compared:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine (SVM)
5. Naive Bayes Classifier

---

## 📊 Model Performance Comparison

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 99.93%   |
| Decision Tree       | 100.00%  |
| Random Forest       | 99.93%   |
| SVM                 | 99.93%   |
| Naive Bayes         | 94.78%   |

---

## 🔍 Overfitting and Underfitting Analysis

Training and testing accuracies were compared to evaluate model generalization and detect potential overfitting or underfitting.

| Model               | Training Accuracy | Testing Accuracy | Overfitting?   | Remarks                                    |
| ------------------- | ----------------- | ---------------- | -------------- | ------------------------------------------ |
| Logistic Regression | 99.98%            | 99.93%           | ❌ No           | Excellent generalization                   |
| Decision Tree       | 100.00%           | 100.00%          | ❌ No           | Perfect performance on synthetic dataset   |
| Random Forest       | 100.00%           | 99.93%           | ⚠️ Very Slight | Negligible overfitting                     |
| SVM                 | 99.98%            | 99.93%           | ❌ No           | Strong and stable performance              |
| Naive Bayes         | 94.03%            | 94.78%           | ❌ No           | Lower performance due to model assumptions |

---

## 🎯 Key Findings

✅ Decision Tree achieved the highest accuracy of **100%**.

✅ Logistic Regression, Random Forest, and SVM also demonstrated excellent performance with approximately **99.93% accuracy**.

✅ Naive Bayes showed comparatively lower accuracy due to its assumption of feature independence.

✅ No significant overfitting or underfitting was observed across the trained models.

✅ Features such as **Severity Level**, **Affected Population**, and **Infrastructure Damage Index** were highly influential in predicting major disasters.

---

## 🏆 Best Model

**Decision Tree Classifier**

* Accuracy: **100.00%**
* Perfect classification on the test dataset
* Easily interpretable and suitable for explaining decision rules

---

## 📝 Conclusion

The Decision Tree Classifier emerged as the best-performing model for predicting major disaster events. The exceptionally high performance can be attributed to the strong relationships between the predictor variables and the target variable within this synthetic dataset. Overall, the models demonstrated excellent predictive capability and strong generalization performance.

---

## ⏭️ Next Steps

* 🔄 Cross Validation
* 📈 Feature Importance Analysis
* ⚙️ Hyperparameter Tuning
* 📉 Confusion Matrix Visualization
* 🌐 Model Deployment using Streamlit
