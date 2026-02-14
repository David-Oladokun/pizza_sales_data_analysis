# Analyzing Pizza Sales Data
This project presents a comprehensive exploratory data analysis (EDA) of a pizza restaurant’s transactional sales data. The dataset contains detailed information about customer orders, product characteristics, pricing, quantities sold, timestamps, and ingredients.

The primary objective of this analysis is to transform raw transactional data into meaningful business insights that can support strategic decision-making. By integrating multiple related datasets and performing detailed analysis, this project demonstrates how data analytics can improve operational efficiency, revenue optimization, and customer understanding in the food service industry.

# Business Problem

Restaurants generate large volumes of transactional data daily, yet many businesses fail to leverage this data for strategic insights. Understanding customer demand patterns, product performance, peak business hours, and revenue drivers is essential for improving profitability.

# This project aims to answer key business questions such as:
- How much revenue does the business generate?
- What are the peak hours of customer activity?
- Which products drive the highest sales?
- Are there underperforming menu items?
- What seasonal patterns exist in revenue?
- Which days of the week generate the most income?

# Dataset Description
The analysis uses four relational datasets:

1️. Orders: Contains order timestamps.
- order_id
- date
- time

2️. Order Details: Contains product quantities per order.
- order_details_id
- order_id
- pizza_id
- quantity

3️. Pizzas: Contains pricing and size information.
- pizza_id
- pizza_type_id
- size
- price

4️. Pizza Types: Contains product names, categories, and ingredients.
- pizza_type_id
- name
- category
- ingredients
# These datasets were merged into a single dataframe using relational keys to enable comprehensive analysis.

# Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

# Data Processing Workflow
The project followed a structured analytical workflow:
- Data loading and inspection
- Data cleaning and formatting
- Dataset merging using relational keys
- Feature engineering (revenue calculation, time extraction)
- Exploratory data analysis
- Visualization of trends and patterns
- Business insight generation

# Key Analysis Performed
The following metrics and insights were derived:
- Total Revenue Generated
- Total Quantity of Pizzas Sold
- Total Number of Orders
- Number of Pizza Types Offered
- Average Pizza Price
- Peak Sales Hours
- Sales Distribution by Day of Week
- Monthly Sales Trends
- Top 5 Bestselling Pizzas
- Bottom 5 Performing Pizzas
- Underperforming Product Identification

# Key Insights
Several important business insights emerged:
- Sales peak during evening hours, indicating strong dinner demand.
- Certain days of the week outperform others, suggesting behavioral purchasing patterns.
- A small number of pizza types contribute disproportionately to total revenue.
- Some menu items consistently underperform and may require promotion or replacement.
- Monthly sales variations indicate potential seasonal demand fluctuations.
# These findings demonstrate the value of data analytics in operational planning and decision-making.

# Business Recommendations
Based on the analysis, the following recommendations can be made:
- Increase staffing during peak evening hours.
- Promote underperforming pizzas through discounts or marketing campaigns.
- Focus marketing efforts on high-performing products.
- Optimize inventory planning using sales trends.
- Consider menu redesign based on product performance.
