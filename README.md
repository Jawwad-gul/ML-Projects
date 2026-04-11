# **Machine Learning & Predictive Analytics Portfolio**

Welcome to my Machine Learning portfolio. This repository contains end-to-end projects ranging from retail sales forecasting to financial risk assessment, with a focus on production-ready pipelines and model interpretability.

---

##  Projects Overview

## 1. BigMart Sales Optimization (Regression & Deployment)
**Objective:** Forecast product sales for a retail giant to optimize supply chain management.
- **Tech Stack:** Python, Scikit-Learn, XGBoost, Joblib, Gradio.
- **Highlights:** - Built a robust **Preprocessing Pipeline** (imputation, encoding, scaling) to prevent data leakage.
    - Optimized an **XGBRegressor** using **GridSearchCV** with 8-fold cross-validation.
    - **Deployment:** Integrated the trained model into a live web app.
- ### [Live Demo on Hugging Face](https://huggingface.co/spaces/jawwad1234/Retail_Sales_Forecasting_Engine)
- ![liveDemoSS](BigMartSalesPrediction/assets/BIgMartSalesEngine.png)

---

## 2. Telecom Customer Churn Prediction (Classification)
**Objective:** Predict customer attrition for a telecom provider to improve retention strategies.
- **Tech Stack:** Pandas, Matplotlib, AdaBoost, Random Forest, SVC.
- **Highlights:** - Handled dirty data (e.g., converting object-type currency strings to numeric).
    - Prioritized **Recall** and **ROC-AUC** over accuracy to minimize business loss from "false negatives."
    - Conducted comprehensive EDA to identify 'Contract Type' and 'Tenure' as key churn indicators.

---

## Credit Default Risk Prediction

**End-to-End Machine Learning Project**  
Predicting whether a credit card customer will default next month using the UCI Credit Card dataset.

### Business Problem
Banks lose huge amounts when customers default. This model helps identify high-risk customers **before** the next billing cycle so proactive steps can be taken.

### Key Challenges & How I Solved Them
- **Data Leakage**: The original dataset contained current-month features that indirectly revealed the target. I identified and removed them.
- **Time-aware Validation**: Used temporal split (older data for training, newer data for testing) instead of random split to simulate real-world conditions.
- **Model Comparison**: Started with Logistic Regression → Tuned Decision Tree → Random Forest.

### Models & Results
| Model                  | Test Accuracy | Notes |
|------------------------|---------------|-------|
| Logistic Regression    | ~79.5%        | Strong baseline after scaling |
| Decision Tree (max_depth=8) | ~80.0%   | Reduced overfitting |
| Random Forest (500 trees) | **80.5%**  | Best generalization & stability |

### What I Delivered
- Proper feature engineering & scaling
- Leakage detection and removal
- Bias–variance analysis
- Business-focused insights

**Tech Stack**: Python, Pandas, Scikit-learn, Matplotlib

Repository [CredictDefault_repo](Credit%20Default)
---

##  Core Skills
* **Machine Learning:** Supervised Learning (Regression/Classification), Hyperparameter Tuning, Model Evaluation.
* **Engineering:** Scikit-Learn Pipelines, Model Serialization (Joblib), Version Control (Git).
* **Deployment:** Building Interactive ML Apps with Gradio & Hugging Face.
* **Data Analysis:** Exploratory Data Analysis (EDA), Feature Engineering, Data Cleaning.

---

## 📬 Contact
I am currently seeking **Machine Learning Internships** in Lahore. 
- **LinkedIn:** [www.linkedin.com/in/muhammad-jawwad-gul](LinkedIn)
- **Email:** jawwadgul12@gmail.com
