# PySpark Commodity Price Prediction Project
## Overview
This project serves as an introduction to PySpark, exploring its key features and capabilities. It focuses on predicting commodity prices, specifically for oil and gas, using historical data on futures contracts. This exercise demonstrates PySpark's potential in big data manipulation, transformation, and predictive analytics.

## Why PySpark?
### Scalability: PySpark can handle large-scale data processing, overcoming memory limitations found in pandas.
### Big Data Engine: Built on top of Spark, it offers a robust platform for distributed data processing.
### In-Memory Computation: Faster data processing due to its in-memory computation capabilities.
## Project Steps
### Data Exploration
#### Load Data: Utilized PySpark's DataFrame API to load and inspect the dataset.
#### Null Value Handling: Checked and managed null values effectively.
### Data Transformation
#### One-Hot Encoding: Converted categorical variables into a form that could be provided to ML algorithms.
#### Feature Engineering: Created new features like price change and percentage change.
### Model Building
#### Train-Test Split: Partitioned the data into training and testing sets.
#### Linear Regression: Employed a simple linear regression model for price prediction.
### Model Evaluation
#### Metrics: Utilized RMSE to evaluate the model's performance.
## Key Takeaways
#### Learned the basics of PySpark DataFrame operations and MLlib for machine learning.
#### Understood the advantages of using PySpark over traditional libraries for big data projects.
#### Gained practical experience in data preprocessing, feature engineering, and model evaluation in a PySpark environment.
