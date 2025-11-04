# Experiment 5: COVID-19 Daily Cases Forecasting (Bivariate Analysis)
**AIM:**

To perform bivariate analysis on COVID-19 data and study the relationship between daily confirmed cases and daily deaths, using Linear Regression for prediction and simple real-time forecasting.

**ALGORITHM / PROCEDURE:**

1)Import the required Python libraries: pandas, numpy, matplotlib, and sklearn modules for model building and evaluation.
2)Load the COVID-19 dataset (CSV file) into a pandas DataFrame.
3)Select a specific country’s data (e.g., India or USA) for analysis.
4)Perform bivariate analysis by calculating the correlation between daily cases and daily deaths.
5)Visualize the relationship between daily cases and daily deaths using a scatter plot.
6)Define the input variable (X = Daily Cases) and the output variable (y = Daily Deaths).
7)Split the dataset into training and testing parts using the train_test_split() function.
8)Create and train a Linear Regression model using the training data.
9)Predict daily deaths for the test dataset using the trained model.
10)Evaluate the model performance by calculating R² (coefficient of determination) and RMSE (Root Mean Squared Error).
11)Plot a graph comparing actual deaths versus predicted deaths to visualize model accuracy.
12)Plot daily cases and daily deaths over time to observe the time trend and lag between them.
13)Generate a range of possible future case numbers and predict corresponding deaths using the trained model.


**Program**

**# Your Name
# Your Reg No.**

# Write your code here


**Output**


**Result**
The bivariate analysis shows a strong positive correlation between daily COVID-19 cases and deaths.
The linear regression model successfully predicts deaths from case counts with good accuracy (R² ≈ 0.8).
This experiment demonstrates how linear models can be used for simple real-time forecasting in public health analytics.
Display the predicted future deaths along with correlation, R², and RMSE values.
