🚗 CodeAlpha Car Price Prediction Project

🧠 Overview

This project aims to predict the selling price of a car based on various features such as year, present price, kilometers driven, fuel type, seller type, and transmission.
The prediction is performed using a Linear Regression machine learning model.

The project demonstrates the end-to-end workflow of a machine learning application including data preprocessing, model training, evaluation, and saving the trained model for future use.

🎯 Objectives

•	Load and explore the car price dataset

•	Perform data preprocessing and feature encoding

•	Split the dataset into training and testing sets

•	Train a Linear Regression model

•	Evaluate the model performance

•	Save the trained model using Pickle

🛠️ Technologies Used

•	Python

•	Pandas – Data handling

•	NumPy – Numerical operations

•	Matplotlib – Visualization

•	Scikit-learn – Machine learning

•	Pickle – Model saving

📂 Dataset

Source: Car Price Dataset (CSV file)

Features:

•	Year

•	Present_Price

•	Kms_Driven

•	Fuel_Type

•	Seller_Type

•	Transmission

•	Owner

Target Variable:

•	Selling_Price

🔍 Data Preprocessing

•	Checked for missing values and duplicates

•	Removed unnecessary columns

•	Converted categorical variables (Fuel_Type, Seller_Type, Transmission) into numerical form

•	Selected important features for training

•	Split the dataset into:

  - 80% Training data

  - 20% Testing data

🤖 Model Building

The following model was used:

•	Linear Regression

Steps performed:

1.	Train the model using training data
2.	Predict car prices on test data
3.	Evaluate the model using:

  - R² Score

  - Model accuracy

📈 Results

•	The Linear Regression model achieved good accuracy on the test dataset

•	The model can predict car selling prices based on given input features

•	Predictions are reasonably close to actual values

👨‍💻 Author

•	Ajinkya Dongare
      AI & Data Science Student
      CodeAlpha Internship Project


