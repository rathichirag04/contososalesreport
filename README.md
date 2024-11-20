
# Contoso Sales Dashboard

### Objectives:
To provide comprehensive insights into Contoso's sales performance, profit margins, and geographical distribution through an interactive Power BI dashboard. This will enable stakeholders to make informed decisions based on real-time data visualizations and metrics.

### Description:
The Power BI dashboard for Contoso is designed to offer a detailed overview of the company's sales and profitability. It is structured into several key sections:

1. Header Section:
   - Company Logo and Name: "Contoso Report"
   - Key Metrics:
      - Sales Quantity: 13.642M
      - Discount Quantity: 1.284M
      - Net Quantity: 13.517M
      - Discount Amount: 53.476M
      - Sales Amount: $3.249bn
      - Return Amount: 41.24M
      - Cost of Goods: 1.376bn
      - Net Profit: $1.778bn
2. Slicers:
   - Year
   - Channel Name
   - Region / Country
   - State / Province
   - Brand Name
   - City
   - Product Category
   - Product Subcategory

3. Visualizations:
   - Net Profit Running Total by Date Hierarchy:
     - A bar and line chart showing Net Profit, Previous Year (PY) Net Profits, and Year-over-Year (YoY) Net Profits % for each quarter from Q1 2008 to Q4 2009.
     - A bar chart showing the Net Profit Running Total for each quarter from Q1 2007 to Q4 2009.
   - Net Profit Running Total by Brand Name:
     - A bar chart highlighting YoY New Profits for various brands, with increases and decreases marked.
   - Geography Details:
     - A table displaying Total Sales, Average Order Amount, Net Profit, and YoY New Profits for different regions and countries, including Asia, China, Pakistan, Thailand, Bhutan, Taiwan, and Australia.

![image](https://github.com/user-attachments/assets/22a59ab1-f629-4d04-a8f7-baf69358a1f8)


### Data Modelling and Relationships:
![image](https://github.com/user-attachments/assets/cb00a92d-bc9c-4ee2-ae4a-fd568826c8a8)

The data model organizes and integrates different data sources into a coherent structure, centered around the Sales table. It connects various tables, including Product Master, Channel, Store, Geography, Calendar, and DAX Measure, through key relationships. This setup enables seamless analysis and comprehensive insights into sales performance, profit margins, and geographical distribution, aligning with the objectives of the Power BI dashboard.

Here are the key tables and some fields:

1. Product Master: Brand, Category, Description
2. Channel: Channel Name, Key
3. Store: Address, Employee Count, Manager
4. Geography: City, Region, Country
5. Calendar: Date
6. Sales: Channel Key, Date, Discount Amount, Net Quantity
7. DAX Measure: Average Order Amount

This structure supports the detailed visualizations and analyses required for Contoso's sales and profitability insights.

This dashboard aims to provide a holistic view of Contoso's sales performance, helping to identify trends, measure profitability, and make strategic decisions based on detailed geographical and temporal analyses.
