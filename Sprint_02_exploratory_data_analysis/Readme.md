# Exploring Instacart Data

## Project Description

In this project, we delve into the shopping behaviors of Instacart users by analyzing a dataset provided by Instacart. Instacart, akin to Uber Eats and DoorDash for groceries, released this data in 2017 for a Kaggle competition. Our modified version of the dataset aims to retain the original distributions while ensuring faster computation and including challenges like missing and duplicate values for a more realistic data analysis experience.

Our analysis focuses on understanding various facets of user behavior, including order timing and frequency, product preferences, and reorder habits. Through this project, we aim to glean insights into how customers interact with the Instacart platform, assisting in optimizing the shopping experience.

## Data Description

The dataset consists of five CSV files:

- instacart_orders.csv: Orders placed by users
- products.csv: Information on products
- order_products.csv: Products included in each order
- aisles.csv: Aisle information for products
- departments.csv: Department information for products

Each file contains key information necessary for a comprehensive analysis, such as order times, product names, and user ordering habits.

## System Requirements

To run this analysis, you will need:

- Python 3.13.2 or newer.
- pandas library for data manipulation.
- matplotlib library for generating plots.

These packages are essential for performing data preprocessing, analysis, and visualization tasks outlined in the EDA_final_project_template.ipynb Jupyter Notebook.

## Project Roadmap

- Data Validation: Extend validation checks to cover more edge cases in data, ensuring robust preprocessing.
- Feature Engineering: Develop new features from existing data to enhance analysis and uncover more insights.
- Interactive Dashboard: Create an interactive dashboard using Dash or Streamlit for real-time data exploration.
- Deployment: Deploy the analysis as a web application to make it accessible to a broader audience.