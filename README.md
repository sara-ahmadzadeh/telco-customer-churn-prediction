# Telco Customer Churn Prediction

Predicting customer churn for a telecommunications company using machine learning.

## 📋 Project Overview

This project predicts customer churn for a telecommunications company using machine learning. The goal is to identify at-risk customers so the business can proactively retain them. This is a classic binary classification problem, perfect for demonstrating a full data science workflow.

- **Accuracy Achieved:** 81.1% (Random Forest Classifier)
- **Key Insight:** Contract type and tenure are the strongest predictors of churn.

## 🛠️ Tech Stack

- **Language:** Python 3.10
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook / Google Colab
- **Version Control:** Git & GitHub

## 📁 Project Structure

telco-customer-chur-prediction</br>
├── data/ # Data files (raw and processed)</br>
├── notebooks/ # Jupyter notebooks for EDA and modeling</br>
├── src/ # Reusable Python modules</br>
├── models/ # Saved models</br>
└── reports/ # Figures and final reports</br>

</br>
</br>

## 🚀 Getting Started

1.  Clone this repository.
2.  Install dependencies: `pip install -r requirements.txt`
3.  Run the notebooks in order:
    - `01_eda_exploration_v2.ipynb`: Data cleaning, exploration, and visualization.
    - `03_model_building.ipynb`: Feature engineering, model training, and evaluation.

## 📊 Key Results

### Model Performance
- **Logistic Regression:** 80.4%
- **Decision Tree:** 79.4%
- **Random Forest:** **81.1%** (Best Performing Model)

### Most Important Features (Churn Drivers)
1.  **Contract:** Month-to-month customers are much more likely to churn.
2.  **Tenure:** Newer customers (0-12 months) are at highest risk.
3.  **Total Charges:** Lower total charges correlate with higher churn.

## 🧠 What I Learned & Next Steps

- **Feature Engineering:** Creating `tenure_group` (e.g., 0-1yr, 1-2yrs) helped the model capture non-linear patterns.
- **Next Steps:** Improve the model by exploring hyperparameter tuning and other algorithms like XGBoost.

## 🤝 Connect with Me

[LinkedIn](https://www.linkedin.com/in/sara-ahmadzadeh-916788b3/)
[GitHub](https://github.com/sara-ahmadzadeh)
