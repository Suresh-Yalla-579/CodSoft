# 💻 CodSoft Internship Projects – AI/ML Developer  

This repository contains all the projects I completed during my **CodSoft Machine Learning Internship (May–June 2024)**.  
Each project demonstrates end-to-end ML workflow — from data preprocessing and model building to evaluation and interpretation.

---

## 🚀 Projects Overview  

### 📨 1. SMS Spam Detection  
**Goal:** Build a model to classify SMS messages as *Spam* or *Ham (Not Spam)*.  
**Tech Stack:** Python, Scikit-learn, NLTK, Pandas, NumPy, Matplotlib  

#### 🔹 Highlights:
- Preprocessed text using tokenization, stemming, and TF-IDF vectorization.  
- Trained models: Naive Bayes, Logistic Regression, and SVM.  
- Achieved **98% accuracy** on test data.  

#### 📊 Sample Output:
| Message | Prediction |
|----------|-------------|
| “You won a free trip!” | Spam |
| “Let’s meet tomorrow.” | Ham |

---

### 🧠 2. Customer Churn Prediction  
**Goal:** Predict whether a customer is likely to leave a telecom service provider.  
**Tech Stack:** Python, Scikit-learn, Seaborn, XGBoost, Pandas, NumPy  

#### 🔹 Highlights:
- Handled class imbalance using SMOTE.  
- Trained Random Forest and XGBoost classifiers.  
- Analyzed key churn indicators (Tenure, MonthlyCharges, ContractType).  
- Achieved **F1-score: 0.91** on validation data.  

#### 📈 Insights:
- Customers on month-to-month contracts showed higher churn rates.  
- Low tenure and high monthly charges strongly correlated with churn.  

---

### 💳 3. Credit Card Fraud Detection  
**Goal:** Detect fraudulent transactions using anomaly detection and supervised learning.  
**Tech Stack:** Python, Scikit-learn, Isolation Forest, Logistic Regression, PCA  

#### 🔹 Highlights:
- Handled extreme class imbalance (0.17% fraud).  
- Used PCA for dimensionality reduction to visualize transaction clusters.  
- Achieved **AUC-ROC score: 0.985**.  

#### 📉 Outcome:
- Improved fraud recall by 12% without increasing false positives.  
- Demonstrated scalable pipeline suitable for real-time systems.  

---

## ⚙️ Tech Stack Summary  

| Category | Tools/Frameworks |
|-----------|------------------|
| **Languages** | Python |
| **ML Libraries** | Scikit-learn, XGBoost, NLTK |
| **Visualization** | Matplotlib, Seaborn |
| **Data Handling** | Pandas, NumPy |
| **Environment** | Jupyter Notebook, Google Colab |

---

## 📂 Repository Structure  

