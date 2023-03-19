# Lyft and Uber Cab Fare Prediction

This project aims to predict the cab fare of Lyft and Uber rides based on not only the distance but also other factors such as weather conditions, time of day, and day of the week. By considering these factors, the goal is to generate a fare that improves customer trust and satisfaction without compromising the comfort of the driver.

## Problem Statement

The current fare calculation system of Lyft and Uber only considers the distance traveled, ignoring other factors that can affect the cab ride, such as bad weather, traffic conditions, time of day, and high demand during weekends or peak hours. As a result, drivers may face challenges in reaching the pick-up point, covering short distances, and have to compromise on sleep for duty, leading to high gas usage and expenditure. Customers may get frustrated if the cab cancels in the last minute, leading to dissatisfaction, extra expenditure for drivers, and low income, thus compromising Uber's business.

To overcome these issues, this project aims to predict the fare considering the above-mentioned factors to improve customer trust and satisfaction while also ensuring the driver's comfort and profitability.

## Plan of Action

The plan of action for this project includes the following steps:

Step 1: Collecting Raw Data and Data Pre-processing
The first step is to collect data from both Lyft and Uber, and pre-process it to ensure its quality, consistency, and completeness.

### Step 2: Exploratory Data Analysis
EDA involves performing initial investigations on data to discover patterns, anomalies, test hypotheses, and check assumptions using summary statistics and graphical representations. This step helps to understand the data and gather insights from it.

### Step 3: Data Preparation
Data preparation involves label encoding and binning. Label encoding converts labels into a numeric form to convert them into a machine-readable format, while binning transforms numerical variables into categorical counterparts, reducing noise, and improving accuracy of the predictive models.

### Step 4: Recursive Feature Elimination
Recursive Feature Elimination (RFE) is a wrapper-type feature selection algorithm that selects features to improve model performance.

### Step 5: Feature Selection
Feature engineering involves selecting and transforming a subset of the most relevant features for a dataset. Fewer features can improve the efficiency and effectiveness of machine learning algorithms.

### Step 6: Modelling and Testing
This step involves training a machine learning algorithm to predict the labels from the features, tuning it for business needs, and validating it on holdout data. This project explores four ML models, namely Linear Regression, Random Forest, Decision Tree, and Gradient Boosting Regressor.

### Step 7: Results
The evaluation of each algorithm is based on MAE, MSE, and RMAE metrics, and the results are presented in a tabular format, including the actual vs. predicted values and cross-validation performance.

## Conclusion

The project aims to predict Lyft and Uber cab fares based on various factors, including weather conditions, time of day, and day of the week. The results showed that the Gradient Boosting Regressor model performed the best, with an MAE of 1.017, MSE of 2.587, and RMAE of 1.608. Implementing this model can help improve customer trust and satisfaction while ensuring the comfort and profitability of the drivers.