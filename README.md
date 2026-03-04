# Shopify Ecommerce Data Cleaning Project

This project demonstrates a Python data cleaning workflow for processing large ecommerce datasets.

## Project Overview

The dataset contains ecommerce store information including:

- store domain
- average product price
- product category hierarchy

Example category path:

/Food & Drink/Food/Baked Goods & Desserts

## Tasks Performed

1. Merged multiple Excel files
2. Extracted main category from hierarchical category paths
3. Cleaned currency formatted price values (USD $xx.xx → numeric)
4. Split dataset into category-based files
5. Automated the process using Python and pandas

## Dataset Size

200,000 rows across multiple Excel files.

## Tools Used

- Python
- pandas
- Jupyter Notebook
- Excel

## Example Output

The cleaned dataset is automatically separated into category files such as:

- Food & Drink.xlsx
- Apparel.xlsx
- Beauty & Fitness.xlsx

## Purpose

This project demonstrates data cleaning and transformation techniques commonly used in ecommerce analytics and large dataset processing.
