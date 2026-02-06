🌸 CodeAlpha IRIS Flower Classification Project

🧠 Overview

This project focuses on classifying Iris flowers into three species — Setosa, Versicolor, and Virginica — using a supervised machine learning approach.
The classification is performed using the Logistic Regression algorithm from Scikit-learn.
The model predicts flower species based on four important features:

•	Sepal Length

•	Sepal Width

•	Petal Length

•	Petal Width

This project demonstrates the complete machine learning workflow from data loading to model saving.

🎯 Objectives

•	Load and explore the Iris dataset

•	Perform data cleaning and preprocessing

•	Encode categorical target labels

•	Split data into training and testing sets

•	Train a Logistic Regression model

•	Evaluate model performance

•	Save the trained model using Pickle

🛠️ Technologies Used

•	Python

•	Pandas – Data handling

•	NumPy – Numerical operations

•	Matplotlib – Data visualization

•	Scikit-learn – Machine learning

•	Pickle – Model saving

📂 Dataset

Source: Iris Dataset (CSV file)

Features:

•	SepalLengthCm

•	SepalWidthCm

•	PetalLengthCm

•	PetalWidthCm

Target:

•	Species

o	Iris-setosa

o	Iris-versicolor

o	Iris-virginica

🔍 Data Preprocessing

•	Checked for missing values using isnull()

•	Checked for duplicate entries

•	Removed the Id column

•	Converted categorical species names into numerical values using LabelEncoder

•	Split the dataset into:

o	80% Training data

o	20% Testing data

🤖 Model Building

The following model was used:

•	Logistic Regression

Steps performed:

1.	Train the model using training data
2.	Predict results on test data
3.	Evaluate using:

o	Accuracy Score

o	Classification Report (precision, recall, f1-score)

📈 Results

•	The Logistic Regression model achieved high accuracy on the test dataset

•	Classification report shows good precision and recall for all three flower species

•	The model can reliably classify iris species based on input features

•	👨‍💻 Author

•	Ajinkya Dongare

AI & Data Science Student
CodeAlpha Internship Project


