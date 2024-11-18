#Bulldozer Sale Price Prediction

This project aims to predict the future sale price of bulldozers using historical sales data. It is a time-series regression problem solved with RandomForestRegressor.

Key Highlights

* Problem: Predicting bulldozer prices based on characteristics and past sales.
Data:
	•	Train.csv: Sales data up to 2011 (~400,000 examples, including SalePrice as the target).
	•	Valid.csv: Sales data from Jan 1, 2012, to Apr 30, 2012 (~12,000 examples).
	•	Test.csv: Sales data from May 1, 2012, to Nov 2012 (~12,000 examples, no SalePrice).
	•	Evaluation Metric: Root Mean Squared Logarithmic Error (RMSLE).

Workflow:

   1. Data cleaning and preprocessing.
   2. Feature engineering to handle time-series data.
   3. Model training and evaluation using **RandomForestRegressor**.
   4. Fine-tuning the model to minimize RMSLE.

This project showcases the application of time-series regression techniques and machine learning tools to solve real-world problems.

NOTE: The data could be collected from Kaggle: https://www.kaggle.com/code/radhakrishnasp/bulldozer-price-prediction/notebook
