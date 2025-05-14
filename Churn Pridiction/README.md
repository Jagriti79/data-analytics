# Customer Churn Prediction

## Objective
Predict whether a customer is likely to churn (leave the company) based on historical data. This helps businesses take preventive actions and retain customers.

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Dataset
The dataset contains customer information such as:
- Demographics (age, gender, location)
- Account details (tenure, services used)
- Customer activity (support calls, contract type)
- Target variable: `Churn` (Yes/No)

> Example file: `churn_data.csv`

## Process
1. **Data Cleaning & Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Visualize churn distribution
   - Identify key patterns

3. **Model Building**
   - Train/test split
   - Algorithms: Logistic Regression, Random Forest, etc.
   - Evaluate using accuracy, precision, recall, ROC-AUC

4. **Model Interpretation**
   - Feature importance
   - Confusion matrix

## Results
- Achieved ~85% accuracy using Random Forest
- Identified key churn indicators:
  - Monthly charges
  - Contract type
  - Number of customer service calls

## How to Run
1. Clone the repo
2. Open `churn_model.ipynb` in Jupyter Notebook
3. Ensure you have the dataset (`churn_data.csv`) in the `data/` folder
4. Run all cells to see the predictions and visualizations

## Output Samples
- Confusion Matrix
- Feature Importance Bar Chart
- ROC Curve
