---

### 📘 Credit Card Fraud Detection

#### 🧾 Project Overview  
This project detects fraudulent credit card transactions using a real, anonymized dataset. Due to severe class imbalance, SMOTE was used for oversampling the minority class.

---

#### 🎯 Task Objectives  
- Build a binary classifier to detect fraud.  
- Address class imbalance with SMOTE.  
- Evaluate models using AUC, precision, and recall.

---

#### 🧹 Preprocessing Steps  
- Verified dataset shape: 284,807 records with 30+ features.  
- Applied `StandardScaler` to `Amount`.  
- Dropped `Time` and original `Amount` features.  
- Split data and applied **SMOTE** on training set to balance classes.

---

#### 🤖 Model Selection  
- **Logistic Regression**  
- **Random Forest Classifier**

Each model was evaluated on a held-out test set using ROC AUC and classification metrics.

---

#### 📊 Performance Analysis  
- **Random Forest Classifier**:  
  - ROC AUC Score: 0.9737  
  - Precision & Recall significantly improved over baseline  
- Plotted **ROC curves** for both models

---
