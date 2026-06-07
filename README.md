# 💳 Credit Card Fraud Detection Using Supervised Machine Learning

## 📖 Overview

Financial fraud is one of the most significant challenges faced by modern digital payment systems. Traditional rule-based fraud detection methods often struggle to adapt to evolving fraudulent patterns.

This project implements and evaluates multiple supervised machine learning algorithms for detecting fraudulent credit card transactions using a highly imbalanced real-world dataset. Special emphasis is placed on improving fraud detection performance through class balancing and model optimization techniques.

---

## 🎯 Objectives

* Detect fraudulent credit card transactions using machine learning.
* Handle severe class imbalance using SMOTE.
* Compare the performance of multiple classification algorithms.
* Optimize model performance using GridSearchCV.
* Evaluate models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

---

## 📊 Dataset

**Source:** Kaggle Credit Card Fraud Detection Dataset

### Dataset Statistics

| Metric                  | Value   |
| ----------------------- | ------- |
| Total Transactions      | 284,807 |
| Fraudulent Transactions | 492     |
| Fraud Percentage        | 0.172%  |

The dataset contains anonymized transaction features generated using PCA transformation to preserve confidentiality.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Imbalanced-Learn (SMOTE)
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔬 Methodology

### Data Preprocessing

* Feature scaling using StandardScaler
* Dataset exploration and cleaning
* Handling class imbalance with SMOTE

### Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

### Hyperparameter Optimization

GridSearchCV with Stratified K-Fold Cross Validation was applied to improve model performance.

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix
* ROC Curves

---

## 🏆 Results

| Model               | Accuracy | ROC-AUC |
| ------------------- | -------- | ------- |
| Logistic Regression | 98%      | 0.9975  |
| Decision Tree       | 100%     | 0.9985  |
| Random Forest       | 100%     | 0.9999  |

### Key Findings

✅ Random Forest achieved the highest overall performance.

✅ SMOTE significantly improved minority-class prediction.

✅ Ensemble learning methods demonstrated superior fraud detection capability.

✅ Logistic Regression remained computationally efficient while maintaining strong performance.

---

## 📂 Repository Structure

```text
credit-card-fraud-detection/
│
├── Fraud_Detection_Final.ipynb
├── README.md
├── requirements.txt
└── Research_FraudDetection_IEEE.pdf
```

---

## 🚀 Future Enhancements

* Deep Learning Models (LSTM, Autoencoders)
* Real-Time Fraud Detection Systems
* Explainable AI (XAI)
* Large-Scale Financial Transaction Analysis

---

## 👩‍💻 Authors

**Aakansha Saroj**
B.Tech Electronics & Communication Engineering (AI)
Indira Gandhi Delhi Technical University for Women (IGDTUW)

**Diksha Lanjiwar**
B.Tech Electronics & Communication Engineering (AI)
Indira Gandhi Delhi Technical University for Women (IGDTUW)

---

## ⭐ Research Contribution

This project was developed as part of an academic research study exploring the effectiveness of supervised machine learning techniques in fraud detection systems and their potential application in real-world financial environments.

