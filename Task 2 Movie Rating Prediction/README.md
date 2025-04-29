---

### 📘 Movie Rating Prediction

#### 🧾 Project Overview  
This project predicts IMDb movie ratings based on various features like genre, director, and cast. It tackles a regression problem with missing data and categorical encoding challenges.

---

#### 🎯 Task Objectives  
- Predict IMDb ratings of movies using metadata.  
- Handle missing values and encode categorical variables.  
- Compare multiple regression models.

---

#### 🧹 Preprocessing Steps  
- Dropped rows with excessive missing values.  
- Imputed missing numerical and categorical values.  
- Encoded all categorical columns using `LabelEncoder`.  
- Engineered new features: average rating by `Director` and `Genre`.  
- Scaled features using `StandardScaler`.

---

#### 🤖 Model Selection  
- **Random Forest Regressor**  
- **Gradient Boosting Regressor**  
- **Linear Regression**  
- **SVR (RBF Kernel)**

---

#### 📊 Performance Analysis  
- **Best Model**: Gradient Boosting  
  - RMSE: ~0.73  
  - R² Score: ~0.58  
- Bar plots used to visualize model performance metrics.

---
