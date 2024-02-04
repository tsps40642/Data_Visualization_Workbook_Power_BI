# Data_Visualization_Workbook_Power_BI

This is a notebook for data visualization on Microsoft Power BI.  
Below are demonstrations for some steps using sample dataset from: https://youtu.be/NNSHu0rkew8?si=8oZ76U0zjnjWRCJR  

## Transform data 
1. Table view mode -> click "Home" -> click "Transform data", "Transform data", this open Power Query Editor  
2. This doesn't affect original data source  
3. Right click column name -> "Replace value" to replace original values with designated values  
4. On the right side can see "APPLIED STEPS" to check working steps  
5. Click "Remove Columns" to delete a selected column  
6. Home tab -> click "Close & Apply" -> back to Power BI Desktop  

## Build table relationships
Power BI will automatically detect table relationship.  
If it doesn't, drag the column that the relationship will rely on to another table to create a relationship manually.  

## Create a line chart for Cookies Shipped against Order Date  
1. Click and create a blank line chart  
2. Drag Cookies Shipped and Order Date to Y-axis and X-axis respectively
3. Click the chart -> click "Drill up" to adjust time units magnitude in x-axis
4. Adjust orther details in "Format visual"

## Create a number card fot ΣRevenue   
1. Click "ΣRevenue" and Power BI will detect the best possible visualization, and you can also change it by clicking anoter chart format
2. To create a number card, click "Card"

## Create a table for Customer Name  
1. Click "Customer Name" and Power BI automatically creates a table
2. Since the two tables have relationship, we can connect all the chart together. If click one of the customer names, we can filter all the chart and see results corresponding to that selected customer name
3. Click Shift or Control tab to multi-select the customer names

## Publish the report  
1. Click "Home" -> Click "Publish" -> select "My Workspace" to publish
2. When success, click "Open ... in Power BI" to view your report on Power BI website service
3. Click the top-left "File" -> select the option you want
4. Or can click "Export" and select the option you want  
