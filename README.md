# elevatelabs-task-4
This repo contains tasks from my internship "ElevateLabs"
# AI & ML Internship – Task 4  
## Feature Encoding & Scaling

## 📌 Objective
The objective of this task is to preprocess the Adult Income dataset by encoding categorical features, scaling numerical features, and preparing the dataset for machine learning models.

---

## 📊 Dataset Used
- **Adult Income Dataset**

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

## 🔍 Task Overview
The following preprocessing steps were performed:

- Loaded and inspected the dataset
- Identified categorical and numerical features
- Handled missing values in categorical columns
- Applied **Label Encoding** to the target variable
- Applied **One-Hot Encoding** to non-ordinal categorical features
- Scaled numerical features using **StandardScaler**
- Compared dataset readiness before and after scaling
- Saved the fully preprocessed dataset

---

## 🔑 Encoding & Scaling Details
- **Label Encoding:** Used where order exists (target variable: income)
- **One-Hot Encoding:** Used where no order exists (categorical features)
- **Scaling:** Standardized numerical features to mean 0 and variance 1

---

## 📈 Key Observations
- All categorical features were successfully converted to numerical form
- Numerical features were standardized to the same scale
- Dataset is now suitable for distance-based and gradient-based algorithms
- No data leakage introduced during preprocessing

---

## 🤖 Machine Learning Readiness
✔ Fully numerical dataset  
✔ Scaled features for fair model contribution  
✔ Suitable for algorithms like Logistic Regression, SVM, KNN, and Neural Networks  

---

## 📁 Repository Structure
