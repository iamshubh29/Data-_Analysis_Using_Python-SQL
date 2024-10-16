# Sales Data Analysis Project

## Project Overview
This project involves a thorough analysis of a sales dataset sourced directly from Kaggle. The analysis utilizes Python for data cleaning, manipulation, and visualization, along with SQL for querying insights. The primary aim is to derive actionable business intelligence from the sales data, exploring various metrics and trends.

## Dataset Structure
The dataset contains **9,994 records** with the following columns:

| Index | Column Name    | Non-null Count | Data Type         |
|-------|----------------|----------------|--------------------|
| 0     | order_id       | 9994           | int64              |
| 1     | order_date     | 9994           | datetime64[ns]     |
| 2     | ship_mode      | 9988           | object             |
| 3     | segment        | 9994           | object             |
| 4     | country        | 9994           | object             |
| 5     | city           | 9994           | object             |
| 6     | state          | 9994           | object             |
| 7     | postal_code    | 9994           | int64              |
| 8     | region         | 9994           | object             |
| 9     | category       | 9994           | object             |
| 10    | sub_category   | 9994           | object             |
| 11    | product_id     | 9994           | object             |
| 12    | quantity       | 9994           | int64              |
| 13    | discount       | 9994           | float64            |
| 14    | sale_price     | 9994           | float64            |
| 15    | profit         | 9994           | float64            |

**Key Attributes:**
- **Order Details**: `order_id`, `order_date`, `ship_mode`
- **Customer Information**: `segment`, `country`, `city`, `state`, `postal_code`, `region`
- **Product Information**: `category`, `sub_category`, `product_id`
- **Sales Metrics**: `quantity`, `discount`, `sale_price`, `profit`

## Data Cleaning Process
The data cleaning process involves:
- **Handling Missing Values**: Addressing the missing entries in `ship_mode`.
- **Data Type Validation**: Ensuring each column has the correct data type for analysis.
- **Removing Duplicates**: Checking for and eliminating any duplicate records.
- **Normalizing Data**: Standardizing formats for easier analysis.

## Analytical Insights
The analysis performed on the dataset includes several key SQL queries, as well as visual representations to enhance understanding of the data. 

### SQL Queries
1. **Top 10 Highest Revenue Generating Products**
2. **Top 5 Highest Selling Products in Each Region**
3. **Month-over-Month Growth Comparison for 2022 and 2023 Sales**
4. **Highest Sales Month for Each Category**
5. **Sub-Category with Highest Growth by Profit in 2023 Compared to 2022**

### Visualizations
Graphs and charts were generated using libraries such as Matplotlib and Seaborn to provide visual insights into the following:
- Sales trends over time
- Distribution of sales by region and category
  
