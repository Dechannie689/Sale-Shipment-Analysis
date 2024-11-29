# Sale & Shipment Analysis - Power BI
## 1. Abstract
This dashboard visualizes key insights to provide a comprehensive overview of sales & shipment performance in Power BI, leveraging a dataset sourced from [HERE](https://drive.google.com/drive/folders/1sNHbkw6k1TcuiePujyqh3pWCCi9CXa9c?usp=drive_link). 
- The Sales Performance Dashboard highlights sales trends over the last few years, as well as details about sales team performance. Monitor employee performance & progress by YoY reports for top-performing sales executives, plotted by both revenue earned and items sold. Analyze each sales location individually with interactive maps, including countries and top regional customers.
- The Shipment Performance Dashboard delivers a detailed analysis of annual shipping performance. Gain a clear overview of shipment delays and enhance understanding of high-value customers to optimize operations and build stronger relationships.

## 2. Methodology
### a. Data Model
Created a calendar table using DAX. Then, check all the relationships that have been automatically established and build the missing ones.

### b. Exploring and Manipulate Some Data Using DAX Query
Create Measures and columns Using DAX functions such as count, sum, calculate, if and Date-time function before analysing.

## 3. Data Visualization
Visual representation of data offers intuitive insights. The following visuals will be incorporated in the report:
### Cards
- Showcasing total revenue.
- Representing AOV.
- Representing the number of orders.
- Displaying overdue/ intime shipments.
### Slicer
Representing the date time.
### Charts
- Line chart for Total Revenue by Year & Month, Revenue YTD and YoY% by Year & Month, AVG Shipment Duration, % Overdue Shipments.
- Stacked column chart for the Revenue from New and Old Customers by Year and Month, the % Overdue Shipments by Year, Month & Company.
- Map for the Count of Orders by Region.
- Gauge for AVG Shipment Duration & % Overdue Shipments.
- Table for Sale team performance, Shippers statistics and Customers statistics.
### Tooltips
- Showing the distribution of Revenue from New and Old customers.
- Showing an Employee's data.
### Parameters
Add parameters for Max % of Overdue shipments and Max Shipment Duration Target with slicers.

Gratitude for your time!
