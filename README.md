# netflix

Overview
This project aims to predict Netflix's stock prices using machine learning techniques, specifically regression analysis. By leveraging historical stock data sourced from Kaggle, the model provides insights into future stock performance, which can be valuable for investors and analysts.

Data Source
The dataset utilized in this project is retrieved from Kaggle, containing historical stock price data for Netflix, including features such as daily opening, closing, high, and low prices, trading volume, and other market indicators.

Data Preprocessing: The initial step involves cleaning and preprocessing the data. This includes handling missing values, normalizing features, and splitting the dataset into training and testing sets.

Model Selection: A linear regression model is employed due to its simplicity and effectiveness in capturing linear relationships between features and stock prices. The model is trained using the training dataset, and various techniques like cross-validation are applied to ensure its accuracy.

Integration with Flask
To make the prediction model accessible to users, a Flask web application is developed. This application allows users to interact with the model and obtain predictions based on various input parameters.
