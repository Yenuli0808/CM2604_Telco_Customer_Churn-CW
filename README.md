# CM2604_Telco_Customer_Churn-CW
Machine Learning coursework - Customer Churn Prediction

## 📌 Overview

This repository contains the coursework project for **CM2604** focusing on **Telco Customer Churn Prediction**. The goal of this project is to build and evaluate machine learning models that can accurately predict whether a customer will churn (leave the service), based on historical telecom customer data.

Customer churn prediction helps telecom companies identify at-risk customers and take actions to improve retention rates.

---

## 🧠 Problem Statement

Customer churn happens when customers stop using a company’s services. For a telecom provider, reducing churn is crucial because retaining an existing customer is usually more cost-effective than acquiring a new one.

The project involves:
- Data exploration and cleaning
- Feature engineering
- Model building
- Evaluation and comparison of machine learning techniques

---

## 📁 Project Structure

CM2604_Telco_Customer_Churn-CW/
├── data/ # Dataset files
├── notebooks/ # Jupyter notebooks for EDA & modeling
├── reports/ # Plots, analysis reports
├── .gitignore
├── README.md
└── requirements.txt # Python dependencies


---

## 📊 Dataset

The dataset used contains customer information from a telecommunications company, including:
- Demographics (e.g., gender, age)
- Services subscribed (e.g., phone, internet, support)
- Contract type and tenure
- Billing and payment information
- Target label: **Churn** (Yes/No)

The dataset typically has fields like:
- `customerID`
- `gender`
- `SeniorCitizen`
- `Partner`
- `Dependents`
- `tenure`
- `MonthlyCharges`
- `TotalCharges`
- `Churn`

This is a well-known dataset used for churn analysis and is commonly available from sources such as Kaggle and IBM sample datasets. :contentReference[oaicite:1]{index=1}

---

## 🛠 Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/Yenuli0808/CM2604_Telco_Customer_Churn-CW.git
2. Navigate into the directory

cd CM2604_Telco_Customer_Churn-CW

3. Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate    # macOS/Linux
venv\Scripts\activate       # Windows

4. Install dependencies

pip install -r requirements.txt

## 🔎 Project Workflow

### 1️⃣ Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Train-test split

### 2️⃣ Exploratory Data Analysis (EDA)
- Churn distribution analysis
- Feature correlation analysis
- Data visualization

### 3️⃣ Model Development
The following classification algorithms were implemented:

- Decision Tree (Tuned and Not Tuned)
- NN Model (Manually Hyperparameter Tuned and Not Tuned)

### 4️⃣ Model Evaluation
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

The best performing model was selected based on overall performance and generalization ability.

Done SMOTE as the data set was imbalanced but for final evaluation to choose the best model it was not used as it synthetic data and proned to overfitt when i try to use the method. SO i tried this as only a experimental method

