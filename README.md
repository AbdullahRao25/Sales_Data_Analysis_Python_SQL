# Sales_Data_Analysis_Python_SQL

Sales-Data-Analysis

🚀 Key Features

✅ Data Cleaning: The raw sales data is cleaned and formatted.

✅ SQL Queries: Complex SQL queries are used to extract useful insights.

✅ Visualizations:

> Bar plots for total sales by product and monthly sales.
> Donut chart to visualize the top-selling products.
> Horizontal bar charts for product-wise sales percentages.
> Heatmap to visualize product ranks across different months.

🛠️ Tools & Libraries Used

1. Python – Programming language for data analysis and visualization
2. Pandas – Data wrangling and transformation
3. SQLite – In-memory SQL analysis for querying the sales data
4. Matplotlib – Visualization library for static, animated, and interactive plots
5. Seaborn – Built on Matplotlib, used for creating informative statistical plots
6. NumPy – For numerical operations and formatting

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

> Clone or download this repository to your local machine.
> Open the notebook using Jupyter or any compatible environment (e.g., VS Code).
> Update the file path for the dataset in the first code cell.
> Run the cells in order to see the analysis and visualizations.

🧠 What’s Inside the Notebook

Data Loading & Cleaning
Reads the CSV file and checks for missing values.
Renames columns to match consistent formatting.
Converts columns to the appropriate data types for analysis.
SQL Database Setup
Loads the cleaned data into an in-memory SQLite database.

Executes SQL queries to extract relevant insights such as:

1. Top-selling products
2. Best-performing months
3. Product sales percentages
4. Data Analysis
5. Calculates total sales for products and visualizes them using bar plots.
6. Formats large numbers (e.g., sales in millions) for better readability.
7. Analyzes sales trends by month and visualizes them with bar plots.
8. Ranks products by sales percentage contribution and displays them using horizontal bar charts.
9. Visualizes the product ranking across different months using a heatmap.

📷 Visualizations:

Bar Plot: Displays the top-selling products.
Donut Chart: Visualizes the sales distribution among top products.
Horizontal Bar Chart: Displays the sales percentage of each product.
Heatmap: Shows the product rank across months.


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
