---

### 📘 Titanic Survival Prediction

#### 🧾 Project Overview  
This project predicts the survival of passengers aboard the Titanic using machine learning models. The dataset is a well-known benchmark from Kaggle, featuring passenger demographics, class, fare, and more.

---

#### 🎯 Task Objectives  
- Predict whether a passenger survived the Titanic disaster.  
- Handle missing and categorical data effectively.  
- Train, compare, and evaluate classification models.

---

#### 🧹 Preprocessing Steps  
- Filled missing values for `Age`, `Fare`, and `Embarked` using median/mode imputation.  
- Dropped non-informative features: `Cabin`, `Name`, `Ticket`, and `PassengerId`.  
- Encoded categorical variables (`Sex`, `Embarked`) with numerical labels.  
- Visualized feature distributions and correlations for insights.

---

#### 🤖 Model Selection  
- **Logistic Regression**  
- **Random Forest Classifier**

Both models were trained on an 80/20 train-test split and evaluated using precision, recall, F1-score, and confusion matrix.

---

#### 📊 Performance Analysis  
- **Logistic Regression**:  
  - High accuracy with balanced class performance.  
- **Random Forest**:  
  - Perfect accuracy on test data (likely due to small sample size).  
  - Outperformed logistic regression with better generalization on test set.

---
