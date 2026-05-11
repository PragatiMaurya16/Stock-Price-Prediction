# Stock-Price-Prediction

Yes Bank, a prominent player in the Indian financial sector, experienced significant volatility following the 2018 fraud case involving Rana Kapoor. This project focuses on building a machine learning regression model to predict the monthly closing price of Yes Bank stock. The dataset spans from the bank's inception through November 2020, capturing the drastic price fluctuations during the period of financial instability.

The workflow follows a rigorous Data Science lifecycle:

->Data Exploration: Understanding the distributions of Open, High, Low, and Close prices.

->Preprocessing: Handling the date format (converting strings to datetime objects) and checking for missing values or outliers.

->Feature Engineering: Dealing with multicollinearity, as stock price features (OHLC) are often highly correlated.

->Modeling: Implementing multiple regression algorithms, including Linear Regression, Lasso, and Ridge, to find the most robust predictor.

->Evaluation: Using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R^2 Score to assess performance.

The goal is to determine if predictive models can accurately capture the stock's behavior despite the external shocks caused by the fraud scandal.
