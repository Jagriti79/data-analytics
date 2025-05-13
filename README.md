# Customer Churn Prediction Tool

A Google Colab-based churn prediction tool that allows users to **upload a CSV file** and receive predictions using a **pre-trained machine learning model**. Ideal for business analysts and data science learners who want to test churn modeling interactively.

---

## Overview

This project uses a machine learning model trained to predict customer churn based on historical data. The notebook is designed to run in **Google Colab**, making it simple to use with no local setup required.

Users can:
- Upload their own dataset
- Automatically preprocess and validate input
- Generate predictions (churned or not)
- Download the prediction results

---

## How to Use

1. **Open the notebook** in [Google Colab](https://colab.research.google.com/).
2. **Upload your CSV file** containing customer data.
3. The tool will:
   - Load and preprocess the data
   - Run the pre-trained model
   - Output churn predictions
4. Optionally, **download the results** as a new CSV file.

---

##  Model Details

- **Algorithm:** Random Forest / Logistic Regression (customizable)
- **Input:** Customer demographic and usage features
- **Output:** `Churn` prediction (Yes/No or 1/0)
- **Training Dataset:** [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn) (or your custom dataset)

---

##  Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Pickle (for model serialization)
- Google Colab
- Matplotlib / Seaborn (optional for visualizations)

---
