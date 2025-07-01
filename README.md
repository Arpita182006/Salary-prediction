# Salary-prediction
Salary prediction by the no. of years of experience using simple linear regression

💼 Salary Prediction using Simple Linear Regression
📌 Overview
This project demonstrates a simple linear regression model built with Python to predict salary based on years of experience. The dataset used contains salary data for employees along with their experience in years.

📊 Dataset
Name: Salary_Data.csv

Features:

YearsExperience (Independent variable)

Salary (Dependent variable)

Contains 30 observations (rows).

🧠 Objective
To create a machine learning model that predicts an employee’s salary based on their years of experience using Simple Linear Regression.

⚙️ Tools & Libraries
Python

Pandas

NumPy

Matplotlib

Seaborn

scikit-learn

🧪 Steps Performed
Import Libraries
Standard libraries for data handling, visualization, and model training.

Load Dataset
Used pandas to read the CSV file.

Visualize the Data
Created a scatter plot of years of experience vs. salary.

Split Data

80% training data

20% testing data
Used train_test_split from sklearn.

Train the Model
Used LinearRegression from sklearn.linear_model to train on the training data.

Make Predictions

Predicted salary for 10 years of experience.

Visualized the regression line.

User Input

Accepted user input for years of experience.

Predicted the salary based on the trained model.

📈 Visualization
Blue dots: Actual data points

Red line: Regression line (best-fit line)

🔍 Sample Output
sql
Copy
Edit
Enter year of experience: 10
Your salary must be close to: 122988
