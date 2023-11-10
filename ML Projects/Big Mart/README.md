# Sales Prediction for Big Mart Outlets

## Introduction

Company Introduction - Big Mart Corporation

Our client for this project is Big Mart Corporation, a prominent retail organization.

- Big Mart has collected 2013 sales data for 1,559 products across 10 stores in different cities. They have also defined certain attributes for each product and store.
- The objective is to build a predictive model to forecast the sales of each product in a particular outlet.
- Big Mart aims to understand which product and store attributes significantly influence sales.

Please note that the data may contain missing values as some stores may not have reported all the data due to technical glitches. Appropriate data pre-processing will be required.

## Problem Statement

The current challenge for Big Mart Corporation is:

- Predicting the sales for each product in various outlets accurately to optimize stock management and sales strategies.

## Project Details

- Collaborating with - The sales and marketing department to enhance inventory management and marketing strategies.
- Our Role - Building a predictive model using the provided datasets.
- Project Deliverables - Predict the sales of each product in a particular outlet.
- Machine Learning Task: Regression
- Target Variable: Item_Outlet_Sales
- Win Condition - No predefined quantifiable win condition; our goal is to build the most accurate sales prediction model.
- Evaluation Metric - Model performance will be assessed using the Root Mean Square Error (RMSE) value.

## Data Acquisition & Description

We are provided with a dataset that contains all the necessary information about products and outlets. This dataset includes the following columns:

- `Item_Identifier`: Unique product ID
- `Item_Weight`: Weight of the product
- `Item_Fat_Content`: Indicates whether the product is low fat or not
- `Item_Visibility`: The percentage of total display area allocated to the product in the store
- `Item_Type`: The category to which the product belongs
- `Item_MRP`: Maximum Retail Price (list price) of the product
- `Outlet_Identifier`: Unique store ID
- `Outlet_Establishment_Year`: The year in which the store was established
- `Outlet_Size`: The size of the store in terms of ground area covered
- `Outlet_Location_Type`: The type of city in which the store is located
- `Outlet_Type`: Specifies whether the outlet is a grocery store or a supermarket
- `Item_Outlet_Sales`: Sales of the product in the particular store (this is the target variable to be predicted).

The Train Set contains 8,523 rows and 12 columns, while the Test Set contains 5,681 rows and 11 columns. The Test Set does not include the `Item_Outlet_Sales` column, which needs to be predicted.

## Data Profiling & Pre-Processing

- Jupyter Notebook: [Link](https://github.com/Mihir-Ai-lab/Academic-Projects/blob/c683fe12969e2dc17c412d31ba9322731d7485f7/ML%20Projects/Big%20Mart/Big%20mart%20Sales%20Prediction.ipynb)

## Submission

The Client requested the Submission file with the following conditions:

- The submission file should be in CSV format.
- It should have 5,681 rows.
- It should contain 2 columns: `Item_Identifier`, `Outlet_Identifier`, and the predicted `Item_Outlet_Sales` values.
- The submission file should not have column names in the first row.

Based on the requirements, the submission file has been generated and can be viewed [here](https://github.com/Mihir-Ai-lab/Academic-Projects/blob/main/ML%20Projects/Big%20Mart/submission.csv).

## Thank you

- To explore other projects, please [Click Here](https://github.com/Mihir-Ai-lab/Academic-Projects/tree/main)
