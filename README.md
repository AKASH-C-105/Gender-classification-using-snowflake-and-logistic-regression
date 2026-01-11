# Gender Classification using Snowflake & Machine Learning

This project demonstrates an **end-to-end Machine Learning workflow** where data is fetched securely from **Snowflake**, processed using **Python**, and trained using a **Logistic Regression** model for gender classification.

The project is designed with **security best practices**, ensuring that Snowflake credentials are never exposed in the codebase.

---

## 🔹 Project Overview

- Data Source: Snowflake Cloud Data Warehouse  
- ML Model: Logistic Regression  
- Language: Python  
- Libraries: pandas, numpy, scikit-learn, snowflake-connector-python  
- Platform Ready: GitHub & Kaggle  

---

## 🔹 Workflow

1. Securely connect to Snowflake
2. Fetch and load data into Pandas
3. Perform data preprocessing & feature encoding
4. Train Logistic Regression model
5. Evaluate model performance

---

## 🔹 Technologies Used

- Snowflake
- Python
- Pandas & NumPy
- Scikit-learn
- Jupyter Notebook

---

## 🔐 Credential Management (Important)

⚠️ **Snowflake credentials are NOT hardcoded.**

This project uses **environment variables** to securely store sensitive information such as:
- Username
- Password
- Account
- Warehouse
- Database
- Schema

---
