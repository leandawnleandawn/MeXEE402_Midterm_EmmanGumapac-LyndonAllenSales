# MeXEE402_Midterm_EmmanGumapac-LyndonAllenSales
MEXEE 402 Midterms Examination


# INTRODUCTION
Linear Regression and Logistic Regression are both statistical models used for prediction. However, they are employed in different scenarios based on the type of data and the nature of the prediction task.

Linear Regression predicts a continuous numerical value (e.g., house price, temperature). A linear equation: y = mx + b, where y is the predicted value, x is the independent variable, m is the slope, and b is the intercept. Linear relationship between variables, normally distributed residuals, and homoscedasticity (equal variance of residuals). Predicting sales figures, estimating property values, forecasting stock prices.

Logistic Regression predicts a categorical outcome (e.g., whether a customer will churn, if an email is spam). a logistic function: p(y=1) = 1 / (1 + exp(-z)), where p(y=1) is the probability of the outcome being 1, and z is a linear combination of the independent variables. Linear relationship between the log-odds of the outcome and the independent variables. Classifying medical diagnoses, predicting customer behavior, evaluating credit risk.

In summary Linear Regression is suitable for predicting continuous quantities. Logistic Regression is suitable for predicting categorical outcomes, especially when the outcome is binary (e.g., yes/no, true/false).

# DATASET DESCRIPTION 

### Linear Regression Dataset
The dataset provides insights into the relationship between advertising expenditures and sales. Specifically, it examines how investments in TV, radio, and newspaper advertising can influence sales outcomes. By analyzing the data using linear regression, we can identify the correlation between these advertising channels and sales figures. This analysis helps us understand which advertising mediums are most effective in driving sales and allocate resources accordingly.

### Logistic Regression Dataset
The dataset employs logistic regression to analyze how various physicochemical properties of red wine influence its quality. By examining factors such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, and others, the model identifies which characteristics are significant indicators of high-quality wine. This analysis can be valuable for winemakers in understanding how to optimize their production processes to create wines that meet or exceed consumer expectations.

# PROJECT OBJECTIVES
### General Objectives
Understand the fundamentals: Gain a deep understanding of the concepts, assumptions, and limitations of linear and logistic regression.
Compare and contrast: Analyze the key differences between the two models, including their applications, strengths, and weaknesses.
Implement and evaluate: Build and evaluate regression models using real-world datasets to assess their predictive performance.

#### Data exploration:
Collect relevant datasets for both linear and logistic regression tasks.
Clean and preprocess the data to ensure its suitability for analysis.
Explore the relationships between variables and identify potential outliers or anomalies.

#### Model building and training:
Develop linear regression models to predict continuous outcomes (e.g., house prices, sales figures).
Construct logistic regression models to predict categorical outcomes (e.g., customer churn, email spam).
Experiment with different model configurations and hyperparameters to optimize performance.

#### Model evaluation:
Employ appropriate metrics to assess the accuracy and reliability of the models.
Use techniques like cross-validation to prevent overfitting and evaluate generalization performance.
Interpret the model coefficients to understand the importance of different variables.

#### Real-world application:
Apply the learned knowledge to solve real-world problems using regression analysis.
Identify potential use cases in various domains (e.g., finance, healthcare, marketing).
Evaluate the impact and benefits of using regression models in these contexts.

# RESULTS AND DISCUSSION

### Linear Regression

The independent variables are the TV, Radio, and Newspaper.

The Dependent Variable is the Sales.

Using Linear Regression we found out that the accuraacy score of the model is around, 80-94 Percent, which is an acceptable value for Machine Learning Models.

Visualization: 

![image](https://github.com/user-attachments/assets/896f0a26-b431-46ae-9a2c-2f11344554da)

Based on the 

### Logistic Regression

The Independent Variables are the characteristics of the wine, and the dependent variables are the binary values of good wine and bad wine

Since the following data's output has uunique values from 3 to 8, these must be converted into 0 and 1 only.

The Results of the regression showss a 70-75 percent accuracy score based on the Heat Map Created

![image](https://github.com/user-attachments/assets/59767be0-fe24-4fb0-911c-61943684b0df)

# References

[1] https://www.kaggle.com/datasets/ashydv/advertising-dataset
[2] https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009
