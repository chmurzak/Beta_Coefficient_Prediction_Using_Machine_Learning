## Project Overview 📊

This project focuses on predicting the Beta coefficient of companies from the WIG20 index using various machine learning algorithms. The companies analyzed in this project include Pekao, KGHM, and CCC. The steps undertaken in this project are as follows:

1. **Data Collection** 📂: Gathering data for Pekao, KGHM, CCC, and the WIG20 index.
2. **Data Cleaning** 🧹: Processing and cleaning the collected data to ensure accuracy.
3. **Beta Coefficient Calculation** 🔍: Calculating the Beta coefficient using appropriate parameters such as window length.
4. **Machine Learning Prediction** 🤖: Employing machine learning methods such as Linear Regression, Neural Networks, SVM, and Random Forests to predict future Beta coefficients.

---


## Data Collection 📂

The first step in our project involved collecting historical data for the companies Pekao, KGHM, and CCC, along with the WIG20 index. The data was sourced from reliable financial databases to ensure the accuracy and integrity of our analysis.

- **Pekao Data**: [https://stooq.pl/q/d/?s=peo](https://stooq.pl/q/d/?s=peo)
- **KGHM Data**: [https://stooq.pl/q/d/?s=kgh](https://stooq.pl/q/d/?s=kgh)
- **CCC Data**: [https://stooq.pl/q/d/?s=ccc](https://stooq.pl/q/d/?s=ccc)
- **WIG20 Index Data**: [https://stooq.pl/q/d/?s=wig20](https://stooq.pl/q/d/?s=wig20)

---

## Data Cleaning 🧹

Data cleaning is a crucial step to ensure that the data used for analysis is accurate and relevant. The following steps were undertaken:

1. **Handling Missing Values**: Identifying and imputing or removing missing values.
2. **Data Formatting**: Ensuring that all data points are in the correct format for analysis.
3. **Outlier Detection and Removal**: Identifying and handling outliers that could skew the results.

---

## Beta Coefficient Calculation 🔍

The Beta coefficient was calculated for each company using historical price data. The calculation involved:

1. **Choosing the Window Length**: Selecting an appropriate window length for Beta calculation.
2. **Regression Analysis**: Performing regression analysis between the stock returns of each company and the market index (WIG20).

The Beta coefficient helps in understanding the volatility of a stock in relation to the market.

---

## Machine Learning Models 🤖

Various machine learning models were used to predict the future Beta coefficient:

1. **Linear Regression**:
    - Simple and multiple linear regression models.
2. **Neural Networks**:
    - Using deep learning techniques to capture complex patterns.
3. **Support Vector Machines (SVM)**:
    - Employing SVM for regression analysis.
4. **Random Forests**:
    - Utilizing ensemble learning methods for improved accuracy.

Each model was trained on the historical data and evaluated for its prediction performance.

---

## Results 📈

The results of our analysis demonstrated the predictive capabilities of each machine learning model. Key metrics used for evaluation included:

1. **Mean Squared Error (RMSE)**: Measuring the average of the root squares of the errors.
2. **R-squared (R²)**: Determining the proportion of variance in the dependent variable predictable from the independent variable(s).

The performance of each model was compared to identify the most effective approach for Beta coefficient prediction.

---
