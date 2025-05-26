# Ecommerce Data Analysis (SQL + Python)

This project presents a complete data analysis workflow for an ecommerce dataset using both **SQL** and **Python**. The goal is to explore, clean, and analyze the data to extract actionable insights about user behavior, sales trends, and product performance.

## Project Overview

The analysis focuses on answering key business questions such as:
- What are the most profitable products?
- How do sales vary across different regions?
- What time periods show the highest customer activity?
- Are there patterns in payment methods or product categories?

## Technologies Used

- **Python** (Pandas, Matplotlib, Seaborn)
- **SQL** (via SQLite or other SQL-compatible engines)
- **Jupyter Notebook** (for interactive exploration and reporting)

## Key Steps

1. **Data Loading**  
   Data is loaded and briefly inspected to understand structure and quality.

2. **Data Cleaning**  
   Missing values are handled, data types are corrected, and duplicates are removed.

3. **Exploratory Data Analysis (EDA)**  
   Visualizations and statistics are used to explore trends and correlations in the dataset.

4. **SQL Queries**  
   Key business questions are answered using raw SQL queries embedded in Python.

5. **Insight Generation**  
   Business-related insights are summarized at the end of the analysis.

## Highlights and Insights

- **Customer Distribution**:
  - Orders came from a variety of cities and states, showing wide market penetration.

- **Sales Trends**:
  - Highest number of orders occurred in **2018**.
  - Monthly order patterns reveal seasonal peaks and business growth.
  - **Total sales by category** highlight the most profitable product groups.

- **Revenue Insights**:
  - A few product categories contribute a large portion of the revenue.
  - Top-performing **sellers** were identified and ranked based on revenue.

- **Customer Behavior**:
  - A significant portion of orders were paid using **installments**.
  - Average number of products per order varies by city.
  - **No repeat purchases** were observed within a 6-month window, resulting in a **retention rate of 0%**.

- **Product Performance**:
  - Weak negative **correlation (-0.11)** between product price and number of purchases:
    - Lower-priced items tend to sell more frequently.

- **Top Customers**:
  - The top 3 highest-spending customers were identified for each year.

## Folder Contents

- `Ecommerce(SQL+Python) Data analysis.ipynb`: The main Jupyter notebook containing all analysis.
- `README.md`: Project documentation.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/MontyDevelop/Ecommerce-data-analysis.git

