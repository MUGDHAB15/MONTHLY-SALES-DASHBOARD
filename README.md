# MONTHLY-SALES-DASHBOARD
MONTHLY SALES DASHBOARD ON EXCEL (AMAZON)

Files attached
1. sales_analysis_workfile - excel file
2. Sales_analysis - csv file
3. dashboard_pdf

BACKGROUND
There is a sales data of AMAZON downloaded from Kaggle. And there is an Input sheet with few other important details corresponding with the ProductID.
We have to create a Dashboard showing the following details:
1. Total Sales
2. Total Profit
3. Profit percentage
4. Monthly Sales
5 Daily sales trend
6 Sales by Type of channel
7. Sales by mode of payment
8. Top soled product

In the EXCEL Sheet the first tab is named as AMAZON, which contains the sheet downloaded from the kaggle, then the input data sheet is the sheet with other details having the PRODUCT_ID in common.

Firtly we created another tab called the cleaned data, where in we copied the AMAZON sheet data and perform the data cleaning, checked the data types and dropped few columns which was not required for the analysis. Then We joined the cleaned data sheet and input data sheet with the help of VLOOKUP, and created more columns and total sales value, total buying value, day, month, and year from the date column - this all is done in the Data_for_analysis tab. 

Now since we are ready with our cleaned and formatted data, we start and prepare the analysis tab where in we created all the pivot table and other charts as required.

Finally, we created our dashboard with all the charts we prepared in the analysis_tab and did all the formatting.

We found the following:
1. Total sales - $26,197,800
2. Total Profit - -$46,115,721
3. Profit percentage - -64%
4. Top sold product - USB SMART TELEVISION

This shows that sales has NOT increaed it has been normal but the profit is decreased.

Further the data can be used to analyse the rating wise, peoples comment, however not used in this analysis.

