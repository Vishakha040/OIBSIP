# Car Price Prediction Using Machine Learning

## Oasis Infobyte Data Science Internship – Task 3

### Project Overview

This project was developed as part of my Data Science Internship at Oasis Infobyte. The objective is to build a machine learning model that can predict the selling price of a used car based on various vehicle characteristics.

Car prices are influenced by several factors such as age, fuel type, brand, transmission type, and ownership history. Through this project, I explored how machine learning can be used to analyze these factors and make accurate price predictions.

The project covers the complete machine learning workflow, including data cleaning, feature engineering, exploratory data analysis, model building, evaluation, and comparison.

---

## Objective

To develop a regression model capable of predicting the selling price of a used car using historical vehicle data and machine learning techniques.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Dataset Information

The dataset contains information about used cars, including:

- Car Name
- Manufacturing Year
- Present Price
- Selling Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission Type
- Number of Previous Owners

The dataset was obtained from the CarDekho vehicle dataset, which is commonly used for machine learning and predictive analytics projects.

---

## Data Cleaning

To ensure data quality and reliability, the following preprocessing steps were performed:

- Checked for missing values
- Identified duplicate records
- Removed duplicate entries
- Standardized categorical values
- Verified data types and dataset structure

These steps helped prepare the dataset for further analysis and model training.

---

## Feature Engineering

Additional features were created to improve the predictive capability of the models.

### Car Age

A new feature called **Car Age** was calculated using the manufacturing year of the vehicle.

```
Car Age = Current Year - Year
```

This feature helps the model understand the effect of vehicle age on resale value.

### Brand Extraction

The brand name was extracted from the car name column to capture the influence of different manufacturers on selling prices.

Examples:

| Car Name | Brand |
|-----------|---------|
| Maruti Swift Dzire | Maruti |
| Hyundai i20 | Hyundai |
| Honda City | Honda |

---

## Exploratory Data Analysis

Several visualizations were created to understand the dataset and identify important patterns.

### Distribution of Selling Price

A histogram was used to study how selling prices are distributed across the dataset.

### Selling Price by Fuel Type

A box plot was created to compare selling prices among different fuel categories.

### Selling Price vs Car Age

A scatter plot was used to examine the relationship between vehicle age and selling price.

### Correlation Analysis

A correlation heatmap was generated to identify relationships among numerical variables and determine which features are most strongly associated with selling price.

---

## Data Preprocessing

Machine learning models require numerical input data. Therefore, categorical features were converted into numerical format using One-Hot Encoding.

Encoded variables include:

- Fuel Type
- Seller Type
- Transmission Type
- Brand

---

## Model Development

The dataset was divided into training and testing sets using an 80:20 ratio.

### Linear Regression

Linear Regression was used as a baseline model to establish a relationship between vehicle features and selling price.

### Random Forest Regressor

Random Forest Regressor was used as an ensemble learning model to improve prediction performance by combining multiple decision trees.

---

## Model Evaluation

The models were evaluated using the following metrics:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Measures prediction accuracy while giving greater importance to larger errors.

### R² Score

Indicates how well the model explains the variability in the target variable.

---

## Model Comparison

Both models were compared using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The comparison helped identify the model that achieved the best predictive performance on the testing dataset.

---

## Feature Importance

Feature importance analysis was performed to identify the variables that have the greatest influence on car price prediction.

This analysis provides insights into the factors that contribute most significantly to determining a vehicle's market value.

---

## Key Learnings

This project provided practical experience in:

- Data Cleaning and Preparation
- Feature Engineering
- Exploratory Data Analysis
- Data Visualization
- Regression Modeling
- Model Evaluation
- Performance Comparison
- Machine Learning Workflow Implementation

---

## Conclusion

This project demonstrates the complete process of building a machine learning solution for predicting used car prices.

Starting from raw data, the dataset was cleaned, transformed, and analyzed before training multiple regression models. The models were evaluated using standard performance metrics, and the most suitable model was identified based on prediction accuracy.

The project strengthened my understanding of machine learning concepts and provided valuable hands-on experience in applying data science techniques to a real-world problem.

---

## Author

Vishakha Chargotra

Data Science Intern  
Oasis Infobyte
