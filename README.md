# Blinkit’s Sales at a Glance: Interactive Power BI Dashboard
### Project Overview:
The goal of the project is to create an interactive sales dashboard for Blinkit, an online grocery delivery platform. The dashboard will provide actionable insights into sales performance, customer behavior, product trends, and operational efficiency. It will serve key stakeholders, such as management, sales teams, and operations, to help them make data-driven decisions to improve performance.
### Purpose and Performance Targets:
- Provide a clear, real-time overview of Blinkit’s total sales, order volume, and revenue trends.
- Identify top-selling products, low-performing items, and inventory status to improve stock management and prevent shortages or overstocking.
- Visualize sales distribution by region, city, or delivery zone, helping Blinkit identify high-performing areas and growth opportunities.
### Data Source:
The primary dataset used for analysis is "Blinkit_Data.xlsx" file, containing the detail information of the products, outlets and orders.
### Tools
- Excel spreadsheets – Data cleaning
- SQL – Data Analysis
- Power BI Desktop [version 2.126.927.0] – Creating report
### Data Cleaning and Preparation:
- Data loading and Inspection
- Handling missing values
- Data cleaning and formatting
### Exploratory Data Analysis:
EDA involved exploring the sales data to answer the key questions such as:
- What is the variance in sales across different product categories?
- What products have the highest sales revenue? Are there any seasonal products that spike at certain times of the year?
- Which regions, cities, or delivery zones have the highest sales volume?
### Data Analysis
Analyzing Total sales , no. of items, average sales and average rating using SQL.
```sql
Select sum(sales) as Total_sales from Blinkit_Data;
```
```sql
select count(item type) as NO_OF_Items from Blinkit_Data;
```
```sql
select avg(sales) as AVG_Sales from Blinkit_Data;
```
```sql
select avg(rating) as AVG_Rating from Blinkit_Data;
```
### Insights and Findings:
- The outlet location in tier 3 cities have more sales.
- The sales of fruits, vegetabales and snacks have been more than the rest.
### Analyzed metrics:
- Total sales
- No. of items
- Average Sales
- Average Rating
### Visuals and Dashboards:
- KPI Card: Total sales, No. of items, Average sales and Average rating.
- Item Type: Analyzing the item types based on the metrics.
- Fat Content: Analyzing the fat content in the items based on the metrics.
- Fat by Outlet: Analyzing the fat content in the items of different outlets based on the metrics
- Outlet Establishment: Analyzing the total sales of the outlets from the time of establishment till the present date.
- Outlet Size:Analyzing the total sales based on the outlet sizes.
- Outlet Location: Analyzing the total sales based on the outlet locations.
- Outlet Type: Analyzing the outlet types based on the metrics.
### User Interactive features:
- Filters: Allows the user to filter ny outlet location, size and item type.
- Slicers: Provides options such as total sales, no. of items, average sales and average rating.
### Recommendations:
- Run flash sales or limited-time promotions on popular products, especially during peak times like weekends or holidays.
- Collaborate with local farmers, artisans, or specialty food vendors to offer unique, local products that are exclusive to Blinkit.
### Project Phases and Milestones:
- Data Collection and Preparation: October 2023- November 2023
- Dashboard Design and Development: December 2023- February 2024
## Report Snapshots (Power BI Desktop)

![Screenshot 2024-09-26 215535](https://github.com/user-attachments/assets/e1ff88b0-a152-4051-a246-003b41a5445d)



  


