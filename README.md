# Real-Estate-Analytics-Dashboard
Project Overview
Real-Estate-Analytics-Dashboard is a data analytics project developed in Mexico that leverages Python to visualize key performance metrics for real estate developers. The project processes and analyzes data related to property sales, inventory levels, pricing, and construction to provide actionable insights, helping developers and managers optimize their strategies.

Through data visualizations powered by Matplotlib, Seaborn, Pandas, and Power BI, this project offers an in-depth analysis of the performance of real estate developments. It assists in decision-making by uncovering historical data patterns, providing valuable insights into sales trends, inventory management, pricing strategies, and land utilization.

Features
📊 Sales vs Inventory Dashboard
Description: Visualize and compare sales against inventory for various developers.
Key Insights: Determine how quickly inventory is being sold, and identify potential underperformance or overstock.

💰 Price Distribution by Developer
Description: Display the price distribution for properties offered by each developer using a boxplot.
Key Insights: Understand the pricing strategies used by different developers and assess price variation across the market.

🏗️ Construction vs Land Area Analysis
Description: A scatter plot illustrating the relationship between land area and construction area for each property.
Key Insights: Gain insights into how developers are utilizing the land, whether they are building efficiently or under-utilizing their plots.

🔑 Developer Performance Insights
Description: A bar chart showcasing the total number of units sold by each developer.
Key Insights: Identify top-performing developers based on sales figures, and highlight areas where others may need to improve.

Technologies Used

Python: The core programming language for data processing, analysis, and visualization.
Pandas: Data manipulation and cleaning library.
Matplotlib: Visualization library used to generate various types of charts (e.g., bar charts, scatter plots).
Seaborn: Built on top of Matplotlib, this library is used to enhance the aesthetic and functionality of visualizations.
Google Colab: A cloud-based platform used to run Jupyter notebooks and analyze the dataset.
Power BI: Business analytics tool used to create interactive and visually appealing dashboards.
Dataset Information
This project uses the Total-Casas.xlsx dataset, which contains the following columns:

Ventas: Sales data of properties.
Inventario: Available inventory data.
$ Lista: The listing price of properties.
Desarrollador: Developer name or identifier.
Terreno (m2 T): Land area in square meters.
Construcción (m2 C): Construction area in square meters.
Key Metrics and Insights

Total Projects: Understand how many projects are included in the dataset.
Average Price: Compute the average price of all properties to evaluate the market's price range.
Total Sales & Inventory: Get an overview of total sales and available inventory across all developers.
Developer Performance: Assess developer performance based on units sold, providing a performance comparison.
Project Files and Folder Structure

/Data: Contains the raw data files, including property sales, inventory, pricing, and construction details.
/Visualizations: Folder containing images of the generated plots and charts from the analysis, such as sales vs. inventory, price distribution, and more.
/Scripts: Python scripts used to automate data cleaning, transformation, and visualization.


