# 📊 Customer Churn Prediction & Retention Analytics

> **Predict customer churn. Understand the reasons. Turn data into retention insights.**

An end-to-end **Machine Learning and Data Analytics project** that analyzes customer behavior, identifies patterns associated with churn, compares classification models, and presents business-oriented insights through **Power BI**.

The project combines **Python, Exploratory Data Analysis, Machine Learning, and Business Intelligence** to move from raw customer data to actionable churn insights.

---

## 🎯 Project Objective

Customer churn is one of the major challenges faced by subscription-based businesses.

The goal of this project is to:

* Analyze customer behavior and service usage
* Identify patterns associated with customer churn
* Prepare and clean the customer dataset
* Build machine learning classification models
* Compare model performance using multiple evaluation metrics
* Understand important factors associated with churn
* Present analytical findings through an interactive Power BI dashboard

---

## 🗂️ Dataset

The project uses the **Telco Customer Churn dataset** containing information about **7,043 customers and 21 original columns**.

The dataset includes information such as:

* Customer demographics
* Customer tenure
* Phone and internet services
* Online security and backup services
* Contract type
* Payment method
* Monthly charges
* Total charges
* Churn status

### Target Variable

`Churn`

* `Yes` → Customer churned
* `No` → Customer remained

---

## 🔍 Project Workflow

```text
Raw Customer Data
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Feature Preparation
        ↓
Machine Learning
        ↓
Model Evaluation
        ↓
Churn Analysis
        ↓
Power BI Dashboard
        ↓
Business Insights
```

---

## 🧹 Data Preparation

The project includes preprocessing steps required to prepare the customer data for analysis and machine learning.

Key tasks include:

* Handling missing/inconsistent values
* Removing unnecessary identifiers
* Converting data into suitable formats
* Encoding categorical variables
* Preparing features and target variables
* Creating a cleaned dataset for further analysis

The processed dataset is available as:

`cleaned_customer_churn.csv`

---

## 📈 Exploratory Data Analysis

EDA was performed to understand customer behavior and investigate relationships between customer characteristics and churn.

The analysis explores factors including:

* Churn distribution
* Customer tenure
* Contract type
* Monthly charges
* Total charges
* Internet services
* Payment methods
* Customer services and subscriptions

Visualization tools used include:

* Matplotlib
* Seaborn

---

## 🤖 Machine Learning

Multiple classification algorithms were explored to predict whether a customer is likely to churn.

### Models

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

Hyperparameter tuning was also explored using:

`GridSearchCV`

---

## 📊 Model Evaluation

Rather than relying only on accuracy, the models are evaluated using multiple classification metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix
* Classification Report
* ROC Curve

This provides a broader view of model performance, particularly because correctly identifying potential churners is important in a churn prediction problem.

---

## 📊 Power BI Dashboard

The project also includes a Power BI dashboard designed to communicate customer churn patterns and business insights visually.

The dashboard helps explore:

* Overall churn behavior
* Customer characteristics
* Service-related patterns
* Contract and payment behavior
* Charges and customer tenure
* Potential customer segments requiring attention

Power BI file:

`powerbi dashboard.pbix`

---

## 🛠️ Technologies Used

| Category              | Tools               |
| --------------------- | ------------------- |
| Programming           | Python              |
| Data Manipulation     | Pandas, NumPy       |
| Visualization         | Matplotlib, Seaborn |
| Machine Learning      | Scikit-learn        |
| Model Saving          | Joblib              |
| Business Intelligence | Power BI            |
| Development           | Jupyter Notebook    |
| Dataset               | CSV / Excel         |

---

## 📁 Repository Structure

```text
Customer-Churn-Prediction/
│
├── Customer_Churn.ipynb
│
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── cleaned_customer_churn.csv
├── 02 Customer Churn-Dataset.xlsx
│
├── customer_churn_model.pkl
│
├── powerbi dashboard.pbix
│
├── Customer-Churn-Prediction-and-Analysis.pptx
├── report_1.pdf
│
└── README.md
```

---

## 💡 Key Learning Outcomes

This project helped me strengthen my understanding of:

* Data cleaning and preprocessing
* Exploratory Data Analysis
* Categorical feature encoding
* Classification algorithms
* Model evaluation
* Hyperparameter tuning
* Model persistence
* Data visualization
* Business-oriented data storytelling
* Connecting machine learning with business analytics

One of the main takeaways from the project was that **building a prediction model is only one part of Data Science**.

The more important step is connecting:

```text
Data → Model → Insights → Business Decisions
```

---

## 🚀 Future Improvements

Potential improvements for the project include:

* Building a dedicated prediction web application
* Adding probability-based churn risk scoring
* Introducing model explainability using SHAP
* Adding automated preprocessing pipelines
* Performing cross-validation and more extensive hyperparameter optimization
* Deploying the model as an API
* Creating customer-level retention recommendations
* Adding automated model monitoring

---

## 👨‍💻 Author

**Lakshmi Mallesh**

B.Tech CSE | Data Science

Interested in **Data Science, Machine Learning, AI, and Analytics**.

---

## ⭐ Project

If you find this project useful or interesting, consider giving the repository a ⭐.

**GitHub:**
https://github.com/lakshmimallesh-dev/Customer-Churn-Prediction

---

### 📌 Project Focus

`Data Science` • `Machine Learning` • `Customer Analytics` • `Classification` • `EDA` • `Power BI` • `Python`
