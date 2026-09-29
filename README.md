# Sales Data Analysis Using Python

## Project Overview

This project analyzes sales data using Python and Pandas to identify sales patterns, product performance, customer payment preferences, and city/category-wise sales.

The project follows a basic data analysis workflow:

**Data Loading → Data Cleaning → Data Analysis → Data Visualization → Business Insights**

## Technologies Used

* Python
* Pandas
* Matplotlib

## Dataset

The dataset contains 1000 sales records with information such as:

* Order ID
* Order Date
* Customer ID
* City
* Category
* Product
* Quantity
* Unit Price
* Sales
* Payment Method

## Data Cleaning

The dataset was checked for missing values using Pandas.

Missing values were handled as follows:

* Missing city values were replaced with `"unknown"`.
* Missing unit prices were calculated using `Sales / Quantity`.
* Missing payment methods were replaced with `"unknown"`.

After cleaning, the dataset contained no missing values.

## Analysis Performed

The following analysis was performed:

* Calculated total sales.
* Calculated average sales per order.
* Analyzed sales by city.
* Analyzed sales by product category.
* Identified the product with the highest total quantity sold.
* Identified the most frequently ordered products.
* Analyzed customer payment method preferences.
* Analyzed monthly sales trends.

## Data Visualizations

Three main visualizations were created using Matplotlib:

1. Sales by Category — Bar Chart
2. Sales by City — Bar Chart
3. Monthly Sales — Line Chart

## Key Business Insights

* Electronics generated the highest total sales.
* Hyderabad recorded the highest total sales among the cities.
* Headphones had the highest total quantity sold.
* Credit Card was the most frequently used payment method.
* Monthly sales varied throughout the year.

## Project Structure

```text
SalesAnalysis/
│
├── sales_data.csv
├── analysis.py
└── README.md
```

## How to Run

1. Clone the repository.

2. Install the required libraries:

```bash
pip install pandas matplotlib
```

3. Run the analysis:

```bash
python analysis.py
```

The program performs data cleaning, analysis, and generates the visualizations.

## Conclusion

This project demonstrates the use of Python and Pandas for basic data cleaning, exploratory data analysis, and visualization. It helped identify important sales patterns and business insights from the dataset.
