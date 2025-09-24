# Customer Churn Survival Analysis

This project applies **survival analysis techniques** to the Telco Customer Churn dataset.  
It explores customer retention using:
- **Exploratory Data Analysis (EDA)**
- **Kaplan-Meier Survival Curves**
- **Cox Proportional Hazards Model**
- **Customer-specific churn risk prediction**

The goal is to identify **factors affecting customer churn** and estimate **survival probabilities** for different customer groups.

---

## 📊 Dataset
The dataset used is **Telco Customer Churn** (`WA_Fn-UseC_-Telco-Customer-Churn.csv`), which contains:
- 7043 customers
- 21 columns (19 features + target variable `Churn`)

---

## ⚙️ Features
- **Data Cleaning & Preprocessing**
  - Handling missing values
  - Converting categorical variables
  - Encoding churn labels (Yes → 1, No → 0)

- **Exploratory Data Analysis**
  - Churn distribution
  - KDE plots of tenure & monthly charges
  - Categorical feature churn rates
  - Correlation heatmaps

- **Survival Analysis**
  - Kaplan-Meier estimators by feature groups
  - Cox Proportional Hazards regression
  - Customer-level churn probability prediction

---
## 💼 Business Impact

This project provides actionable insights for customer retention strategies:
- Identify high-risk customers: Predict which customers are likely to churn and target them with retention campaigns.
- Optimize marketing spend: Focus retention efforts on customers with the highest probability of leaving.
- Improve service offerings: Analyze which features (e.g., InternetService, PaymentMethod) contribute most to churn, guiding service improvements.
- Increase customer lifetime value (CLV): By reducing churn, the company can increase revenue and improve long-term profitability.
