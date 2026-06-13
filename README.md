# Customer-Churn-Analysis

## Project Overview

Customer churn is a critical business problem that directly impacts revenue and customer retention. This project analyzes customer behavior data from a telecommunications company to identify key factors influencing customer churn and provide actionable recommendations for improving retention.

Using Python, Pandas, NumPy, Matplotlib, and Machine Learning techniques, the project performs data cleaning, exploratory data analysis (EDA), customer segmentation, churn driver identification, and churn prediction.

---

## Objectives

* Analyze customer behavior and identify patterns associated with churn.
* Perform data cleaning and preprocessing on customer data.
* Conduct exploratory data analysis (EDA) to uncover trends.
* Visualize churn patterns using Matplotlib.
* Identify key drivers contributing to customer churn.
* Build a machine learning model to predict churn.
* Generate business recommendations to improve customer retention.

---

## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains customer demographic information, account details, services subscribed, billing information, and churn status.

### Features

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract Type
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges
* Churn (Target Variable)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Cleaning & Preprocessing

* Handled missing values in TotalCharges.
* Converted data types where required.
* Removed unnecessary columns.
* Encoded categorical variables for machine learning.

### 2. Exploratory Data Analysis (EDA)

* Churn distribution analysis.
* Contract type analysis.
* Payment method analysis.
* Customer tenure analysis.
* Monthly charges analysis.
* Internet service analysis.
* Customer segmentation analysis.

### 3. Churn Driver Analysis

Identified major factors influencing customer churn:

* Contract Type
* Customer Tenure
* Monthly Charges
* Payment Method
* Internet Service Type

### 4. Churn Prediction

Implemented a Random Forest Classifier to predict customer churn.

Model evaluation metrics:

* Accuracy Score
* Precision
* Recall
* F1-Score

### 5. Business Recommendations

Generated data-driven recommendations to improve customer retention and reduce churn risk.

---

## Key Insights

### Contract Type

Customers with Month-to-Month contracts exhibit significantly higher churn rates compared to customers with long-term contracts.

### Customer Tenure

New customers and customers with lower tenure are more likely to churn than long-term customers.

### Monthly Charges

Higher monthly charges are associated with increased churn probability.

### Payment Method

Customers using Electronic Check payment methods demonstrate higher churn rates.

### Value-Added Services

Customers utilizing Online Security and Tech Support services tend to remain with the company longer.

---

## Machine Learning Results

Random Forest Classifier was used to predict customer churn based on customer demographics, services, and billing information.

Typical model performance:

* Accuracy: 78% – 82%
* Good capability to identify high-risk customers

---

## Business Recommendations

1. Encourage customers to migrate from Month-to-Month contracts to annual plans.
2. Strengthen onboarding and engagement during the first 12 months.
3. Provide loyalty rewards and retention offers to high-risk customers.
4. Promote automatic payment methods.
5. Increase adoption of value-added services such as Tech Support and Online Security.
6. Implement proactive retention campaigns using predictive analytics.

---

## Project Structure

```text
Customer-Churn-Analysis/
│
├── data/
│   └── Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Customer_Churn_Analysis.ipynb
│
├── requirements.txt
├── README.md
└── Customer_Churn_Analysis_Report
```

---

## Results

The analysis successfully identified key factors driving customer churn and demonstrated how machine learning can be used to predict at-risk customers. The findings provide valuable insights that can help businesses improve customer retention strategies and reduce revenue loss caused by churn.

---

## Author

**Rithika Rani R**

Aspiring Data Analyst skilled in Python, SQL, Power BI, Excel, Data Visualization, and Machine Learning.
