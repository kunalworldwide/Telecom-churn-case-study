# Telecom Churn Prediction

In the telecom industry, customer churn (i.e., customers switching to a different service provider) is a significant challenge. The cost of acquiring new customers is much higher than retaining existing ones. Therefore, telecom companies aim to predict which customers are at high risk of churn to implement targeted retention strategies.

This project analyzes customer-level data from a leading telecom firm to build predictive models for identifying customers at high risk of churn. The goal is to identify the main indicators of churn and develop strategies to reduce customer churn.

## Dataset Description

The dataset used in this project contains customer-level data from the telecom industry, focusing on the Indian and Southeast Asian market. The dataset includes information about customers' usage, revenue, and other relevant factors. 

## Churn Definition

Churn is defined as customers who have not used any services (such as outgoing calls, internet, SMS, etc.) for a certain period of time. This usage-based definition is particularly relevant for prepaid customers who can stop using the services without notice.

## High-Value Churn

Approximately 80% of the telecom industry's revenue comes from the top 20% of customers, known as high-value customers. Reducing churn among these high-value customers can significantly minimize revenue loss. In this project, we focus on predicting churn only among high-value customers.

## Project Goals

The main objectives of this project are as follows:

1. Analyze the telecom dataset to gain insights into customer behavior and patterns.
2. Identify the main indicators of churn among high-value customers.
3. Build predictive models to accurately predict churn among high-value customers.
4. Evaluate the performance of the models and select the most effective one for churn prediction.
5. Provide business insights and recommendations based on the analysis.

## Contents

The project includes the following files:

- `telecom_churn_data.csv`: The dataset containing customer-level data.
- `telecom_churn.ipynb`: Jupyter Notebook with data preprocessing and feature engineering with churn prediction models and evaluation. 
- `README.md`: This file, providing an overview of the project.

## Usage

To reproduce the analysis and run the code, follow these steps:

1. Download the dataset (`telecom_churn_data.csv`) and place it in the same directory as the Jupyter Notebooks.
2. Open `telecom_churn.ipynb` and run the cells to preprocess the data and engineer relevant features to build and evaluate churn prediction models
3. Explore the results, insights, and recommendations provided in the notebooks.

## Conclusion

This project aims to help telecom companies in predicting customer churn among high-value customers. By understanding the main factors contributing to churn and implementing targeted retention strategies, telecom companies can reduce revenue leakage and improve customer retention.

For detailed analysis, code implementation, and model evaluation, please refer to the Jupyter Notebooks included in this repository.

