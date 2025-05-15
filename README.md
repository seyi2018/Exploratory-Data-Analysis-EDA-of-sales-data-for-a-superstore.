# Superstore Sales Analysis

## Overview

This project provides an Exploratory Data Analysis (EDA) of sales data for a superstore. The analysis aims to uncover key trends and patterns in sales performance across different dimensions, such as market, region, product category, and customer segment. The insights derived from this analysis can help the superstore management make informed business decisions, optimize sales strategies, and improve overall profitability.

## Dataset

The dataset used in this project is stored in an Excel file named `SUPERDATA.xlsx`. It contains sales transaction data with the following key features:

* **State:** The state where the sales transaction occurred.
* **Country:** The country where the sales transaction occurred.
* **Postal Code:** The postal code of the customer.
* **Market:** The market segment to which the transaction belongs.
* **Region:** The region where the sales transaction occurred.
* **Product ID:** The unique identifier for the product.
* **Category:** The product category.
* **Sub-Category:** The product sub-category.
* **Product Name:** The name of the product.
* **Sales:** The sales amount for the transaction.
* **Quantity:** The quantity of products sold.
* **Discount:** The discount applied to the transaction.
* **Profit:** The profit earned from the transaction.
* **Shipping Cost:** The cost of shipping the product.
* **Order Priority:** The priority of the order.
* **Customer ID:** The unique identifier for the customer.
* **Customer Name:** The name of the customer.
* **Segment**: The segment the customer belongs to.
* **Order ID:** The unique identifier for the order.
* **Order Date:** The date when the order was placed.
* **Ship Date**: The date when the order was shipped.
* **Ship Mode**: The mode of shipping

## Analysis Steps

The following steps were performed in this analysis:

1.  **Importing Libraries:**
    * Imported necessary Python libraries, including pandas for data manipulation, numpy for numerical operations, matplotlib for basic plotting, and seaborn for enhanced visualizations.

2.  **Loading the Dataset:**
    * Loaded the dataset from the `SUPERDATA.xlsx` file into a pandas DataFrame using `pd.read_excel()`.

3.  **Data Exploration**
    * Previewed the first few rows of the dataframe using `df.head()`
    * Previewed the last few rows of the dataframe using `df.tail()`

4.  **Data Cleaning and Preprocessing:**
    * Inspected the data for inconsistencies.
    * Checked for missing values.
    * Checked for duplicate entries.
    * Corrected data types if needed.

5.  **Exploratory Data Analysis (EDA):**
    * Visualized the distribution of sales, profit, and shipping costs.
    * Analyzed sales performance by market and region.
    * Examined the performance of different product categories and sub-categories.
    * Investigated the relationship between discount and profit.
    * Analyzed customer segments

## Challenges Faced and How They Were Overcome

* **Large Dataset:** The dataset was relatively large, requiring efficient data handling and processing techniques. Pandas was used to efficiently manage and manipulate the data.
* **Data inconsistencies:** The data had some inconsistencies, which were addressed during the data cleaning phase.

## Instructions on How to Run the Code

1.  **Prerequisites:**

    * Python 3.x
    * pandas
    * numpy
    * matplotlib
    * seaborn

    Install the required libraries using pip:

    `pip install pandas numpy matplotlib seaborn`

2.  **Running the Notebook:**

    * Download the `DAVID_DAUDU_SUPER_DATA_PROJET.ipynb` notebook and the `SUPERDATA.xlsx` file.
    * Ensure that the `SUPERDATA.xlsx` file is in the same directory as the notebook, or provide the correct path to the file in the notebook.
    * Open the `DAVID_DAUDU_SUPER_DATA_PROJET.ipynb` file using Jupyter Notebook or JupyterLab.
    * Run the cells sequentially to execute the code and reproduce the results.

## Code Comments

The code within the `DAVID_DAUDU_SUPER_DATA_PROJET.ipynb` notebook is commented to explain the purpose of each step, making it easier to follow the analysis and understand the process.
