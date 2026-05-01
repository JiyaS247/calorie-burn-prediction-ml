# Problem Statement
To predict the number of calories burned based on daily physical activity data such as steps, distance, and activity levels. 
This is a supervised regression problem where the target variable is continuous (calories burned). 

# Dataset Description
The project uses the Daily Activity (Fitbit Fitness Tracker) dataset containing 599 records and 10 features. 
It includes steps, distance, activity minutes (active/sedentary), and calories burned representing real-world user activity. 

# Steps Performed
Data preprocessing included handling missing values, removing outliers, encoding, and feature engineering (TotalActiveMinutes). 
EDA was done using plots, followed by train-test split and model training for prediction. 

# Models Used
Linear Regression was used as a baseline model to understand linear relationships in the data. 
Random Forest Regressor was used to capture complex and non-linear patterns for better accuracy. 

# Results
Model performance was evaluated using R² score and Mean Squared Error (MSE). 
Random Forest performed better than Linear Regression due to its ability to model complex relationships. [R² (~60%) and MSE (~229k)]

# Limitations
Limited features in the dataset may reduce prediction accuracy and real-world applicability. 
Challenges included handling missing values and correctly interpreting evaluation metrics. 

# Future Improvements
Add more features like heart rate, BMI, age, and sleep data to improve model performance. 
Apply advanced models like Gradient Boosting/XGBoost and perform hyperparameter tuning. 
