# OIBSIP_Datascience_Task5
Car Price Prediction with Machine Learning

1. Project Overview

This project focuses on predicting the selling price of used cars using Machine Learning regression techniques. The model analyses car details to estimate an appropriate price.

2. Project Objective

The main objective is to develop a regression model that can predict the selling price of a used car based on features such as brand, age, kilometres driven, fuel type and transmission.

3. Dataset Description

The project uses the "Vehicle dataset from CarDekho" from Kaggle. The dataset contains details of used cars, including:

	•	Car Name
	•	Year of Manufacture
	•	Selling Price
	•	Kilometres Driven
	•	Fuel Type
	•	Seller Type
	•	Transmission
	•	Owner

4. Technologies Used

	•	Python
	•	Jupyter Notebook
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Seaborn
	•	Scikit-learn

5. Data Preprocessing

The dataset was examined to understand its structure and data quality. Null values and duplicate rows were handled, and inconsistent categorical values (such as differences in capitalisation) were corrected. Unrealistic values were removed.

Feature engineering was performed to create new features: car age (calculated from the year column) and brand (extracted from the car name). Categorical variables were encoded using One-Hot Encoding and ordinal encoding.

6. Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the relationships between car features and selling price.

Visualizations were used to identify patterns, including:

	•	Distribution of selling prices
	•	Selling price by fuel type (box plots)
	•	Selling price vs car age (scatter plot)
	•	Price by brand and price vs kilometres driven
	•	Feature correlation heatmap

7. Machine Learning

Regression algorithms were implemented to predict the selling price based on the selected features. The data was split into training and testing sets, and the following models were trained:

	•	Linear Regression
	•	Random Forest Regressor
	•	Gradient Boosting Regressor

8. Model Evaluation

The trained models were evaluated using appropriate regression evaluation metrics, including Mean Absolute Error (MAE), Root Mean Squared Error (RMSE) and R² score. Cross-validation was used to compare the models more reliably, and a feature importance chart was created for the best-performing model.

9. Conclusion

This project demonstrates how Machine Learning regression techniques can be used to predict used car prices based on car details.

It provided practical experience in data cleaning, feature engineering, exploratory data analysis, encoding categorical variables and machine learning model evaluation.

10. Internship

Organization: Oasis Infobyte

Domain: Data Science

Task: Car Price Prediction with Machine Learning
