📉 Telco Customer Churn Analysis

Understanding why customers leave is vital for telecom companies, as retaining existing clients is significantly more cost-effective than acquiring new ones. This project explores the Telco Customer Churn dataset to uncover key patterns behind churn and develop predictive models to anticipate customer loss.

📌 Objectives

Explore and visualize the dataset to identify important churn indicators
Handle missing values and encode categorical variables
Engineer new features like tenure bins
Train and evaluate multiple machine learning models
Hyperparameter tune the best-performing model
Derive actionable business insights
📊 Dataset Overview

Source: Kaggle - Telco Customer Churn
Features include:
Customer demographics (gender, senior citizen, partner, dependents)
Account information (tenure, contract type, payment method)
Services signed up (internet, phone, online security, etc.)
Target variable: Churn (Yes/No)
🧪 Technologies Used

Python (Pandas, NumPy)
Scikit-learn (ML modeling, preprocessing)
Seaborn & Matplotlib (visualizations)
Jupyter Notebook
⚙️ Models Applied

Logistic Regression
Random Forest
Support Vector Machines
XGBoost (if applicable)
GridSearchCV for hyperparameter tuning
🔍 Key Insights

Long-term customers with monthly contracts are less likely to churn.
Electronic check payment method correlates with higher churn.
Senior citizens and customers without tech support show higher churn risk.
📈 Sample Code Snippet

```bash
df = kagglehub.load_dataset(
    KaggleDatasetAdapter.PANDAS,
    "blastchar/telco-customer-churn",
    "WA_Fn-UseC_-Telco-Customer-Churn.csv"
)
df.head()
```

```
📂 Project Structure

Telco_customer_churn/
├── Telco_customer_churn2.ipynb
├── README.md
├── models/ (optional for saving models using joblib)
├── visuals/ (optional graphs/plots)

```
📝 How to Run

Clone the repository
Install required packages:

```bash
pip install -r requirements.txt
```
Open the notebook and follow along
🤝 Authors

Deelesh
