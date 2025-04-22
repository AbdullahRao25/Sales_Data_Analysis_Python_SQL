# Sales_Data_Analysis_Python_SQL

Sales-Data-Analysis

🚀 Key Features

✅ Data Cleaning: The raw sales data is cleaned and formatted.
✅ SQL Queries: Complex SQL queries are used to extract useful insights.
✅ Visualizations:

Bar plots for total sales by product and monthly sales.
Donut chart to visualize the top-selling products.
Horizontal bar charts for product-wise sales percentages.
Heatmap to visualize product ranks across different months.

🛠️ Tools & Libraries Used

Python – Programming language for data analysis and visualization
Pandas – Data wrangling and transformation
SQLite – In-memory SQL analysis for querying the sales data
Matplotlib – Visualization library for static, animated, and interactive plots
Seaborn – Built on Matplotlib, used for creating informative statistical plots
NumPy – For numerical operations and formatting

📁 Dataset This analysis uses a .csv file containing the following columns:

Order ID
Product
Quantity Ordered
Price Each
Order Date
Purchase Address
Month Name, Month Number
Sales (calculated)

📌 How to Use the Notebook

Clone or download this repository to your local machine.
Open the notebook using Jupyter or any compatible environment (e.g., VS Code).
Update the file path for the dataset in the first code cell.
Run the cells in order to see the analysis and visualizations.

🧠 What’s Inside the Notebook

Data Loading & Cleaning
Reads the CSV file and checks for missing values.
Renames columns to match consistent formatting.
Converts columns to the appropriate data types for analysis.
SQL Database Setup
Loads the cleaned data into an in-memory SQLite database.

Executes SQL queries to extract relevant insights such as:

Top-selling products
Best-performing months
Product sales percentages
Data Analysis
Calculates total sales for products and visualizes them using bar plots.
Formats large numbers (e.g., sales in millions) for better readability.
Analyzes sales trends by month and visualizes them with bar plots.
Ranks products by sales percentage contribution and displays them using horizontal bar charts.
Visualizes the product ranking across different months using a heatmap.

Visualizations

Bar Plot: Displays the top-selling products.
Donut Chart: Visualizes the sales distribution among top products.
Horizontal Bar Chart: Displays the sales percentage of each product.
Heatmap: Shows the product rank across months.

📷 Sample Visuals

Bar plot of top products by sales.
Donut chart of sales distribution.
Heatmap of product ranks across months.

📈 Example Visuals

Total Sales by Product
Sales by Month
Product Rank by Month (Heatmap)

🙌 Contribution

Feel free to fork the repository and contribute! Whether it’s new visualizations, performance improvements, or adding features like predictions or machine learning, pull requests are welcome.

📬 Contact 

For questions, feedback, or collaboration opportunities, feel free to reach out via GitHub Issues or at Exploringrao@gmail.com || Abdullahkaimkhaani@gmail.com

📋 Folder Structure

Sales-Data-Analysis/ │ ├── Sales_Data_Analysis.ipynb ├── Sales data (worked upon).csv └── README.md
