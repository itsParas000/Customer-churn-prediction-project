# Customer Churn Prediction
Predicts telecom customer churn using a Random Forest model.

## Tools
- Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- MySQL: Data storage
- SQLAlchemy: Database connection

## Key Findings
- Achieved 79.4% accuracy in predicting churn.
- Tenure, monthly charges, and contract type are key predictors.

## How to Run
1. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn sqlalchemy mysql-connector-python`
2. Set up MySQL database with `sql/create_table.sql`.
3. Run `notebooks/Customer Churn Prediction.ipynb`.
