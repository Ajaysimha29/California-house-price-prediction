#California House Price Prediction
California Houses

Project Overview
This project is a California house price prediction system that utilizes machine learning techniques, specifically Linear Regression and Random Forest. The primary objective is to predict house prices in California based on various features such as location, number of bedrooms, population, and more. The project demonstrates how different regression models perform and why Random Forest was chosen for its high accuracy.

Table of Contents
Dataset
Models Used
Performance Comparison
Getting Started
Usage
Contributing
License
Dataset
The dataset used for this project is the California Housing dataset, which contains various features related to housing in different districts of California. These features include median income, housing median age, total rooms, total bedrooms, population, households, and more. The target variable is the median house value for California districts.

Models Used
Two regression models were implemented for house price prediction:

Linear Regression: This is a simple linear model that attempts to establish a linear relationship between the features and the target variable. It serves as a baseline model for comparison.

Random Forest: A Random Forest regression model was employed for higher accuracy. Random Forest is an ensemble learning method that combines multiple decision trees to make more accurate predictions.

Performance Comparison
To determine the best model for house price prediction, both Linear Regression and Random Forest models were evaluated based on various performance metrics, including Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2). Random Forest outperformed Linear Regression in terms of accuracy, making it the chosen model for this project.

Getting Started
To run the code and experiments in this project:

Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/Ajaysimha29/california-house-price-prediction.git
Install the required Python packages by running:

Copy code
pip install -r requirements.txt
Open and run the Jupyter notebooks to explore the data, models, and predictions.

Usage
You can use the models for California house price prediction by following the instructions in the respective model notebooks (linear_regression_model.ipynb and random_forest_model.ipynb).

Contributing
Contributions to this project are welcome. If you have suggestions, found issues, or want to extend the functionality, please open an issue or create a pull request.

License
This project is licensed under the MIT License. You are free to use and modify the code, but please provide proper attribution and consider the licenses of any external data sources used.

