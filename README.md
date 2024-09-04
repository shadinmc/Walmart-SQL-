# Walmart Sales Database Project

## Overview

This project is centered around creating and managing a SQL database named `walmartSales` to analyze sales data from a hypothetical Walmart branch. The database is designed to store detailed sales records, including transaction details, product information, customer demographics, and more. It allows for comprehensive analysis of sales trends, customer behavior, product performance, and revenue generation.

## Table of Contents

- [Overview](#overview)
- [Database Structure](#database-structure)
- [Data Transformation](#data-transformation)
- [Queries](#queries)
- [Use Cases](#use-cases)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [License](#license)

## Database Structure

The `walmartSales` database contains a single table named `sales` with the following columns:

- `invoice_id`: Unique identifier for each transaction
- `branch`: Store branch identifier
- `city`: City where the transaction occurred
- `customer_type`: Type of customer (e.g., Member, Normal)
- `gender`: Gender of the customer
- `product_line`: Category of the product sold
- `unit_price`: Price per unit of the product
- `quantity`: Number of units sold
- `tax_pct`: Tax percentage applied to the transaction
- `total`: Total amount of the transaction
- `date`: Date of the transaction
- `time`: Time of the transaction
- `payment`: Payment method used
- `cogs`: Cost of goods sold
- `gross_margin_pct`: Gross margin percentage
- `gross_income`: Gross income from the transaction
- `rating`: Customer rating of the transaction

## Data Transformation

To enhance the data analysis capabilities, additional columns were added:

- `time_of_day`: Categorizes transactions into "Morning," "Afternoon," and "Evening" based on the time.
- `day_name`: Stores the day of the week when the transaction occurred.
- `month_name`: Stores the name of the month when the transaction occurred.

## Queries

The project includes various SQL queries that analyze the sales data, such as:

- Identifying the most popular product lines and those with the highest revenue.
- Analyzing the impact of the time of day on sales and customer ratings.
- Determining the city with the largest tax contribution.
- Finding the customer type that generates the most revenue.

## Use Cases

- **Sales Analysis:** Understand sales patterns over time and across different locations.
- **Customer Insights:** Gain insights into customer demographics and behavior.
- **Revenue Optimization:** Identify opportunities to increase revenue and reduce costs.
- **Operational Efficiency:** Make data-driven decisions to improve store operations.

## How to Run

1. **Set up the Database:**
   - Run the SQL script to create the `walmartSales` database and the `sales` table.

2. **Populate the Table:**
   - Insert data into the `sales` table (sample data not included in this repository).

3. **Run Queries:**
   - Use the provided SQL queries to analyze the data.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
