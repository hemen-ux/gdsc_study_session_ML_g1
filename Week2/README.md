# Mini Project: Housing Price Prediction using scikit-learn

## Project Goal
The goal of this mini project is to predict house prices using housing-related features such as area, number of bedrooms, bathrooms, stories, parking, and other amenities. This project demonstrates how machine learning can be applied to predict one variable from multiple input features using real-world data.

## Machine Learning Type
This problem is a supervised learning regression task. It is supervised learning because the dataset contains labeled data where the target variable (house price) is already known. It is a regression problem because the output is a continuous numerical value.

## Dataset Description
The dataset used in this project is the Housing dataset, which contains 545 records. Each record represents a house with various features including area, bedrooms, bathrooms, stories, parking, and several categorical features such as main road access, guest room availability, basement, air conditioning, preferred area, and furnishing status.

## Machine Learning Workflow
The machine learning process followed in this project includes the following steps:
1. Loading the housing dataset
2. Preprocessing the data by converting categorical values into numerical form
3. Selecting input features and the target variable
4. Splitting the dataset into training and testing sets
5. Training a Linear Regression model
6. Making predictions on unseen test data
7. Evaluating the model using error metrics

## Model Used
A Linear Regression model from the scikit-learn library is used in this project. Linear Regression is suitable for this task because it is simple, efficient, and effective for predicting continuous numerical values such as house prices.

## Model Evaluation
The performance of the model is evaluated using Mean Squared Error (MSE) and Mean Absolute Error (MAE). These metrics measure the difference between the predicted house prices and the actual prices. Lower values of these metrics indicate better model performance.

## Learning Outcome
This project helps in understanding how machine learning concepts are implemented in practice. It demonstrates how data is prepared, how a model is trained, and how predictions are evaluated using real-world housing data.

## Possible Failure Point
One possible failure point in this project is poor data quality or missing important features. If relevant factors affecting house prices are not included, the model may produce inaccurate predictions. This issue can be addressed by improving data quality and including more relevant features.
