# Intership-Task-4

## Data Analysis for E-Commerce Internship Task
### Project Overview
This project completes the 

Data Analyst Internship Task from Elevate Labs. The primary objective was to use data analysis techniques to extract business insights from a structured e-commerce dataset. While the initial task suggested using SQL, this project was completed using Python's Pandas library within a Google Colab environment to overcome data import challenges.


The analysis focuses on cleaning raw transactional data and performing key calculations to understand customer behavior, product performance, and sales trends.

Tools and Libraries
Environment: Google Colab

Primary Library: Pandas

Language: Python

Methodology
The project followed these key steps:

Data Loading: The e-commerce dataset was loaded from a .csv file into a Pandas DataFrame. An ISO-8859-1 encoding was used to handle special characters.

Data Cleaning:

A DateTime column was created by combining the Order_Date and Time columns.

Rows with missing Customer_Id values were removed to ensure data integrity.

The Sales and Quantity columns were converted to a numeric data type for accurate calculations.

Data Analysis: Several key business questions were answered by manipulating the cleaned DataFrame:

Customer Purchase History: Filtered the dataset to view the complete transaction history for a specific customer.

Sales by Category: Grouped the data by Product_Category and calculated the total sales for each, identifying the most profitable categories.

Top-Selling Products: Determined the best-selling products by grouping by Product and summing the total Quantity sold.

Repository Contents
Your_Notebook_Name.ipynb: The main Google Colab notebook containing all Python code for data loading, cleaning, analysis, and the resulting outputs.

data/ecommerce.csv: The raw dataset used for this analysis.

How to Run the Project
Download the repository or clone it to your local machine.

Open Google Colab.

Go to File > Upload notebook and select the .ipynb file from this repository.

In the Colab notebook, upload the ecommerce.csv file to the session storage using the file-browser on the left sidebar.

Run the cells sequentially to see the entire process from data cleaning to final analysis.
