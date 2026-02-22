Titanic Survival Prediction – Machine Learning Project

This project uses the Titanic Dataset to build a simple predictive model using Scikit-learn.
The goal is to predict whether a passenger survived based on features such as age, gender, and class.

🚀 Project Overview

This project demonstrates a complete machine learning workflow, including:

Data preprocessing

Feature encoding

Model training

Model evaluation

Error analysis

The model used is Logistic Regression, a reliable algorithm for binary classification.

🛠️ Approach and Steps Followed
1. Data Preprocessing

Loaded the Titanic dataset and explored structure

Removed irrelevant columns (Name, Ticket, Cabin)

Handled missing values in Age (median) and Embarked (mode)

Converted categorical data (Sex, Embarked) to numerical using LabelEncoder

Split dataset into Training (80%) and Testing (20%) sets

2. Model Training

Used Logistic Regression for binary classification

Trained the model on the processed dataset

Predicted survival on the test dataset

3. Model Evaluation

Evaluated the model using:

Accuracy Score

Confusion Matrix

Classification Report (precision, recall, F1-score)

Mean Squared Error (MSE)

R² Score

📊 Model Performance

The model performed well, achieving strong accuracy on the test data

Confusion Matrix and Classification Report showed reliable performance on both classes

MSE and R² Score provided numerical insight into prediction error

Logistic Regression proved effective for this dataset due to clear patterns in features like sex and passenger class

🔍 Observations & Conclusions

Gender was one of the strongest predictors—female passengers had much higher survival rates

Passenger class had a significant impact—1st class passengers survived more often

Younger passengers tended to have better survival chances

The project successfully demonstrated the full ML pipeline: cleaning → modeling → evaluating

Results were consistent with historical accounts of the Titanic disaster
