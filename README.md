# Customer Churn Prediction using Machine Learning

## About the Project

This project focuses on predicting whether a telecom customer is likely to leave the service (churn). The main goal was to understand the factors that influence customer churn and build machine learning models that can predict it.

I completed this project by following the complete machine learning workflow, starting from data cleaning and exploration to model building and evaluation.

---

## Dataset

- **Dataset:** IBM Telco Customer Churn Dataset
- **Total Records:** 7,043 Customers
- **Target Variable:** Churn (Yes / No)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

```
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Feature Engineering
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Business Recommendations
```
### 1. Data Cleaning
- Loaded the dataset
- Checked data types
- Handled missing values
- Converted `TotalCharges` to numeric values
- Removed null records

### 2. Exploratory Data Analysis (EDA)

Performed analysis on different customer features such as:

- Gender
- Senior Citizen
- Partner
- Dependents
- Contract Type
- Internet Service
- Payment Method
- Paperless Billing
- Monthly Charges
- Total Charges
- Customer Tenure

I also created different visualizations like bar charts, histograms, box plots, and a correlation heatmap to understand customer behavior.

---

### 3. Data Preprocessing

- Converted categorical columns into numerical values
- Applied Binary Encoding
- Applied One-Hot Encoding
- Split the dataset into Training and Testing sets (80:20)

---

### 4. Machine Learning Models

I trained and compared the following models:

- Logistic Regression
- Decision Tree
- Random Forest

---

## Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **78.89%** |
| Decision Tree | **71.15%** |
| Random Forest | **77.25%** |

Among all the models, Logistic Regression gave the best accuracy on this dataset.

---

## Important Features

Based on the Random Forest model, some of the most important features affecting customer churn were:

- Total Charges
- Monthly Charges
- Customer Tenure
- Fiber Optic Internet Service
- Electronic Check Payment Method
- Contract Type
- Online Security
- Tech Support

---

## Business Insights

From the analysis, I observed that:

- Customers with month-to-month contracts were more likely to churn.
- Customers with shorter tenure had a higher churn rate.
- Customers paying higher monthly charges were more likely to leave.
- Fiber Optic customers showed a higher churn rate.
- Customers using Electronic Check churned more than customers using automatic payment methods.
- Customers with partners and dependents were less likely to churn.

---

## Business Recommendations

Based on these findings, telecom companies can:

- Encourage customers to choose long-term contracts.
- Improve customer engagement during the first year of subscription.
- Provide attractive offers for customers with higher monthly charges.
- Improve customer support for Fiber Optic users.
- Encourage automatic payment methods by offering discounts or cashback.
- Focus retention campaigns on customers who are at high risk of churning.

---

## Project Structure

```
customer-churn-prediction/
│
├── Customer_Churn_Prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── customer_churn_model.pkl
├── requirements.txt
└── README.md
```

---

## What I Learned

This project helped me understand the complete machine learning workflow, including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Training
- Model Evaluation
- Comparing Multiple Machine Learning Models
- Drawing Business Insights from Data

It also improved my understanding of how data analysis can help businesses make better decisions.

---

## Future Improvements

In the future, I would like to:

- Perform Hyperparameter Tuning
- Try Gradient Boosting and XGBoost
- Deploy the model using Streamlit
- Build an interactive dashboard for predictions

---

## Author

**Likhith**

Aspiring Data Analyst | Machine Learning Enthusiast
