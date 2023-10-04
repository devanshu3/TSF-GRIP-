## Student Score Prediction

This Python program demonstrates a simple linear regression model to predict a student's percentage score based on the number of hours they studied. It uses the scikit-learn library for machine learning and pandas for data manipulation.

## Description

This program showcases a simple linear regression task, which involves predicting a student's percentage score using only two variables: the number of hours a student studied and the percentage score they achieved in an exam. Linear regression is a fundamental machine learning algorithm for modeling linear relationships between variables.

## Prerequisites

You'll need the following software and libraries installed:

- Python 3.x
- scikit-learn
- pandas
- matplotlib

You can install the required libraries using pip: pip install scikit-learn, pandas, matplotlib 

## Usage

The code is organized as follows:

**Importing Libraries:** We begin by importing the necessary libraries, including scikit-learn for machine learning, pandas for data manipulation, and matplotlib for data visualization.

**Reading the Data:** We fetch the student score dataset from a remote URL and load it into a pandas DataFrame.

**Data Visualization**
A scatter plot is generated to visualize the relationship between the number of hours studied and the percentage scores achieved by students. The plot helps us observe that there is a positive linear relationship between these variables.

**Data Preprocessing**
The data is divided into input attributes (X) and target labels (y). This step prepares the data for model training, as machine learning models require input features and target values.

**Model Training**
We split the data into training and testing sets (80% training, 20% testing) and create a linear regression model using scikit-learn's LinearRegression class. The model is then trained using the training data.

**Making Predictions:** We use the trained model to make predictions on the testing data and display the results.

**Model Evaluation**
After training, we evaluate the model's performance by calculating several metrics:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared (R²) score
These metrics help us understand how well the model fits the data and predicts student scores.

## Acknowledgments

The dataset used in this program is available at this link.
This program serves as an educational example of linear regression in machine learning.
