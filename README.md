# Sales Data Analysis Project

## Project Overview
This project involves an in-depth analysis of a sales dataset sourced from Kaggle. The primary objective is to uncover actionable business insights from the data using Python for data cleaning, manipulation, and visualization, and SQL for querying the dataset. By analyzing key metrics such as product performance, regional sales, and time-based trends, this project aims to provide valuable business intelligence to support decision-making.

## Dataset Structure
The dataset consists of **9,994 records** and contains the following columns:

| Column Name   | Non-null Count | Data Type         | Description                                                  |
|---------------|----------------|-------------------|--------------------------------------------------------------|
| `order_id`    | 9994           | int64             | Unique identifier for each order.                            |
| `order_date`  | 9994           | datetime64[ns]    | Date when the order was placed.                              |
| `ship_mode`   | 9988           | object            | The shipping mode selected for the order.                    |
| `segment`     | 9994           | object            | Customer segment (e.g., Consumer, Corporate).                |
| `country`     | 9994           | object            | Country where the order was placed.                          |
| `city`        | 9994           | object            | City where the order was placed.                             |
| `state`       | 9994           | object            | State where the order was placed.                            |
| `postal_code` | 9994           | int64             | Postal code for the delivery address.                        |
| `region`      | 9994           | object            | Region where the order was placed.                           |
| `category`    | 9994           | object            | Product category (e.g., Furniture, Technology).              |
| `sub_category`| 9994           | object            | Product sub-category (e.g., Phones, Chairs).                 |
| `product_id`  | 9994           | object            | Unique identifier for each product.                          |
| `quantity`    | 9994           | int64             | Quantity of the product ordered.                             |
| `discount`    | 9994           | float64           | Discount applied to the order.                               |
| `sale_price`  | 9994           | float64           | Sale price of the product after discounts.                   |
| `profit`      | 9994           | float64           | Profit earned from the sale.                                 |

### Key Attributes:
- **Order Details**: `order_id`, `order_date`, `ship_mode`
- **Customer Information**: `segment`, `country`, `city`, `state`, `postal_code`, `region`
- **Product Information**: `category`, `sub_category`, `product_id`
- **Sales Metrics**: `quantity`, `discount`, `sale_price`, `profit`

## Data Cleaning Process
The dataset required several steps of data cleaning to ensure accuracy and consistency:
- **Handling Missing Values**: Addressed missing values in `ship_mode` by filling them or removing affected rows.
- **Data Type Validation**: Ensured each column has the correct data type for further analysis.
- **Removing Duplicates**: Eliminated duplicate records to avoid skewing analysis results.
- **Normalizing Data**: Standardized certain fields (e.g., date formats, categorical values) for consistent processing.

## Analytical Insights
The analysis was conducted using a combination of SQL queries and Python-based visualizations, focusing on the following key insights:

### SQL Queries:
1. **Top 10 Highest Revenue Generating Products**: Identified the products contributing most to overall revenue.
2. **Top 5 Highest Selling Products by Region**: Analyzed which products perform best in each region.
3. **Month-over-Month Growth Comparison for 2022 and 2023 Sales**: Assessed growth patterns and trends over time.
4. **Highest Sales Month for Each Category**: Determined the peak sales month for each product category.
5. **Sub-Category with Highest Growth by Profit in 2023 Compared to 2022**: Identified product sub-categories showing the most significant profit growth.

### Visualizations:
Using Python libraries like Matplotlib and Seaborn, the following visual insights were generated:
- **Sales Trends Over Time**: Line charts to illustrate sales growth or decline month-over-month.
- **Regional Sales Distribution**: Bar charts showing how different regions perform in terms of sales.
- **Category and Sub-Category Performance**: Pie charts and bar graphs depicting the distribution of sales across product categories and sub-categories.
- **Customer Segmentation Analysis**: Visualized how different customer segments (e.g., Consumer, Corporate) contribute to revenue and profit.

## Tools and Technologies
- **Python**: Used for data cleaning, analysis, and visualization (Pandas, NumPy, Matplotlib, Seaborn).
- **SQL**: SQL queries were used to extract meaningful insights from the dataset.
- **Jupyter Notebook**: The analysis was conducted within a Jupyter notebook, combining code, visualizations, and explanations in one place.

## How to Use
### SQL Query Execution:
1. Import the dataset (`orders.csv`) into a database (MySQL, PostgreSQL, etc.).
2. Run the queries from the `Retails SQL-Query.sql` file to retrieve key insights.


## Key Insights and Conclusions
By analyzing the sales data, several insights were derived:
- **Best-Selling Products**: Identification of top-selling and high-revenue products.
- **Regional Insights**: Understanding which regions contribute the most to sales and profit.
- **Growth Analysis**: Month-over-month growth rates, highlighting seasonal trends.
- **Customer Segmentation**: Insights into how different customer segments behave, allowing for targeted marketing strategies.
- **Profit Analysis**: Exploration of the products and sub-categories driving the most profit growth.


