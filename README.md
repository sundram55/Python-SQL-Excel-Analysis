# Python-SQL-Excel-Analysis
## 📝 Project Overview
This project automates the process of loading data from CSV files into a MySQL database and performing basic data analysis and visualization. It demonstrates a streamlined workflow for managing and analyzing e-commerce data stored across multiple datasets.

## 🚀 Features
• Data Integration: Automates the creation of MySQL tables and inserts data directly from CSV files.

• Data Cleaning: Handles NaN values and ensures compatibility between data formats and SQL data types.

• Dynamic SQL Generation: Automatically generates CREATE TABLE and INSERT queries based on the structure of pandas DataFrames.

• Analysis and Visualization: Includes basic queries and visualizations to explore the imported data.

## 📁 Project Structure
• CSV Files: Input data files containing e-commerce information (e.g., customers.csv, orders.csv, etc.).

• Python Notebook: The Jupyter Notebook (Python-SQL-Excel project.ipynb) contains code for:

 • Reading and processing CSV files.

 • Establishing a connection to a MySQL database.

 • Loading data into MySQL tables.

 • Performing basic SQL queries and data analysis.

• MySQL Database: A database named **ecommerce** stores the imported data.

## 📊 Insights
1. Order and Delivery Trends
• Key Metric: Average time taken for orders to be delivered was approximately 5-7 days.
• Late Deliveries: ~15% of orders were delivered later than the estimated date.
2. Customer Behavior
• Top States: Most customers were located in SP (São Paulo) and RJ (Rio de Janeiro).
• Unique Customers: A significant proportion of orders came from repeat customers.
3. Payment Insights
• Most Common Payment Method: Credit cards accounted for over 70% of all payments.
• Installments: ~60% of payments were made in multiple installments.
4. Sales Insights
• Top-Selling Products: Electronics and Home Appliances were the most frequently purchased categories.
• Peak Sales Periods: Sales were highest during weekends and holiday seasons.
5. Seller Performance
• Top Sellers: A handful of sellers accounted for ~40% of total orders.
• Delivery Speed: Sellers based in urban centers had faster delivery times on average.
6. Geographical Insights
• High Demand Areas: Metropolitan areas showed higher order volumes.
• Delivery Challenges: Rural areas experienced longer delivery times.

## 🛠️ Prerequisites
1. Python: Ensure Python 3.x is installed.
2. Required Libraries: Install dependencies using pip:
code:
pip install pandas mysql-connector-python matplotlib seaborn
3. MySQL: Set up a MySQL database with the appropriate credentials.
## 🔧 Setup and Usage
1. Clone the repository or download the notebook file.
2. Update the folder path and database credentials in the notebook:
• Update the folder_path variable with the location of your CSV files.
• Update the MySQL host, user, password, and database details.
3. Run the notebook to:
• Create MySQL tables dynamically.
• Insert data from the CSV files.
• Perform SQL queries and visualize the results.

## 🖼️ Example Outputs
• Table Creation: Automatically generated CREATE TABLE statements.
• Query Outputs: Insights and summaries based on SQL queries.
• Visualizations: Charts and graphs showcasing key trends.

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for improvements or new features.
