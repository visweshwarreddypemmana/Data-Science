---

### 📘 Sales Prediction

#### 🧾 Project Overview  
This project predicts car purchase amounts based on customer demographic and financial data. It uses regression models to analyze how features like income, age, and debt influence purchasing behavior.

---

#### 🎯 Task Objectives  
- Predict the **car purchase amount** a customer is likely to make.  
- Perform exploratory data analysis (EDA) and visualize feature relationships.  
- Train and compare regression models for performance.

---

#### 🧹 Preprocessing Steps  
- Loaded dataset with features such as `age`, `annual salary`, `credit card debt`, and `net worth`.  
- Checked for and confirmed **no missing values**.  
- Performed **feature scaling** using `StandardScaler`.  
- Split the dataset into **training** and **testing** sets (80/20 split).

---

#### 🤖 Model Selection  
- **Linear Regression**  
- **Random Forest Regressor**

Each model was trained and evaluated on the same dataset split using **R² score** and visual comparison of predictions.

---

#### 📊 Performance Analysis  
- **Linear Regression**:  
  - R² Score: **~0.99999** (overfit)  
- **Random Forest Regressor**:  
  - R² Score: **~0.95**  
  - Performed better in generalization with more stability across test samples.

Performance was visualized using line plots comparing actual vs predicted values.

---
