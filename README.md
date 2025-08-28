# Credit Risk Modeling

This project demonstrates an **end-to-end credit risk modeling pipeline** on tabular data.  
The workflow includes **Exploratory Data Analysis (EDA)**, **Preprocessing**, and **Model Development** using both **Logistic Regression** (baseline, explainable) and **XGBoost** (non-linear, high-performance).

---

## 🔎 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Distribution of features (numeric & categorical)  
- Correlation analysis and multicollinearity checks  
- Target variable imbalance analysis  
- Initial insights on risk factors

### 2. Preprocessing
- Handling missing values  
- Encoding categorical features  
- Scaling numeric features  
- Addressing class imbalance (SMOTE used)  

### 3. Model Development
- **Logistic Regression**  
  - Cross-validation with hyperparameter tuning  
  - Probability calibration (isotonic)  
  - Cost-sensitive threshold selection  
  - Coefficient analysis for interpretability  

- **XGBoost**  
  - RandomizedSearchCV hyperparameter tuning  
  - Calibration and cost-based thresholding  
  - Feature importance (gain-based)  

---

## 📊 Results (example)

- **Logistic Regression**  
  - AUC ≈ 0.87  
  - Recall ≈ 0.83  
  - Precision ≈ 0.49  

- **XGBoost**  
  - AUC ≈ 0.94  
  - Recall ≈ 0.88  
  - Precision ≈ 0.62  

Both models achieve strong discrimination, with Logistic Regression offering interpretability and XGBoost providing higher predictive power.

---

## 🖼 Visualizations
**Logistic Regression**  
<img width="1540" height="253" alt="image" src="https://github.com/user-attachments/assets/958b0d76-c804-43a9-8233-bf6c62d5465c" />
<img width="636" height="540" alt="image" src="https://github.com/user-attachments/assets/e2aafa00-8717-44e3-8561-72da4a3627e9" />
**XGBoost**  
<img width="1299" height="802" alt="image" src="https://github.com/user-attachments/assets/77611863-04ef-452b-b776-9d63154d4df5" />


