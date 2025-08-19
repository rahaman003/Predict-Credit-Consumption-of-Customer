Business Context

•	The credit card industry is highly data-rich, with customer demographic, behavioral, and transactional information.

•	Banks aim to understand customer spending behavior to:

	Build targeted marketing campaigns.
 
	Improve customer relationship management (CRM).
 
	Customize offers and services.
 
	Grow sales and revenue.
 
•	Specifically, predicting future credit card consumption allows the bank to:

	Identify high-potential customers.
 
	Optimize credit limits and risk exposure.
 
	Design personalized financial products.
 
________________________________________

Available Data

Three datasets were provided:

1.	CustomerDemographics.csv
   
	Features: ID, Account Type, Gender, Age, Income Level, Employment Tenure, Bank Tenure, Region Code, Net Banking usage, Avg Days Between Transactions.

2.	CustomerBehaviorData.csv
   
	Features: Past 3 months’ (April, May, June) credit/debit card spends & transaction counts, card limit, loans (active/closed), investments, debit/credit amounts, max credit amounts, loan enquiries, EMI active.

3.	CreditConsumptionData.csv
   
	Target variable: cc_cons = Average Credit Card Spend in next 3 months (July–September).

	Note: Missing for some customers → need to be predicted.

________________________________________

Expectations

You are expected to:

1.	Data Exploration & Cleaning
   
	Handle missing values, outliers, and data inconsistencies.

	Derive insights into customer demographics & behavior.

	Feature engineering if necessary.

2.	Model Development
   
	Train ML models (Regression, DecisionTreeRegressor, Random Forest) using customers with non-missing cc_cons.

	Validate model performance using Root Mean Square Percentage Error (RMSPE).

3.	Model Documentation
   
	Provide detailed EDA, modeling process, and evaluation outputs with clear commentary.

4.	Final Deliverables
   
	Well-documented code notebook.

	Insights from EDA & feature importance.

	Predicted cc_cons values for customers where it was missing.

	A final model summary & interpretation for business stakeholders.
