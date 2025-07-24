#  Customer Churn Prediction

A machine learning project to analyze and predict customer churn for a telecom company using the Telco Customer Churn dataset.

---

##  Project Structure

- `Customer_Churn_Prediction.ipynb` – Jupyter/Colab notebook with data cleaning, EDA, and model building.
- `customer_churn_analysis.pdf` – Exported version of the notebook for quick reference.
- `README.md` – Project overview and documentation.

---

##  Objective

To identify key factors influencing customer churn and build a model that can predict whether a customer will churn. This enables the company to take proactive actions to retain high-risk customers.

---

##  Dataset

**Source**: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

- Rows: 7,043 customers
- Features: Demographics, service usage, account details, and churn status.

---

##  Exploratory Data Analysis (EDA)

Key findings:
- Most churned customers are on **month-to-month contracts**.
- Customers with **no Online Security or Tech Support** are more likely to churn.
- **Electronic check** is the most common payment method among churned users.
- **Short-tenure customers** churn more frequently.

Visualizations used:
- Bar plots
- Violin plots
- Pie charts
- Count plots
- Box plots

---

##  Machine Learning Model

Used **Logistic Regression** for prediction due to its simplicity and interpretability.

Steps:
- Data preprocessing: Encoding, missing value handling
- Feature selection
- Model training and evaluation

---

##  Top Features Influencing Churn

1. Contract Type
2. Tenure
3. Monthly Charges
4. Online Security
5. Tech Support
6. Payment Method

---

##  Actionable Insights

-  Target **short-tenure** customers with offers.
-  Bundle **Online Security & Tech Support** to reduce churn.
-  Promote **yearly contracts** to stabilize retention.
-  Encourage **auto-payment methods** over electronic check.

---

##  Results

- Model Accuracy: ~80%  
- ROC-AUC Score: ~0.84  
- Churn prediction enables targeted retention campaigns.

---

##  How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Priyaruchita/Customer-Churn-Analysis.git
   cd Customer-Churn-Analysis
