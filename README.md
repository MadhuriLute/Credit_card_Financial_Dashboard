# Credit_card_Financial_Dashboard
 Credit card financial dashboard using Power BI:
 • Developed an interactive dashboard using transaction and customer data from a SQL database, 
to provide real-time insights. 
• Streamlined data processing & analysis to monitor key performance metrics and trends.
 • Shared actionable insights with stakeholders based on dashboard findings to support decision-making processes


Project Objective:
To develop a comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations 
effectively.


Data sets:
This project includes customer.csv (customer details) and credit_card.csv (credit card transactions), which were imported into SQL as relational tables. The customer table stores customer information, while the credit_card table records transactions linked by customer_id. CSV files were loaded into SQL using the LOAD DATA INFILE command.




Steps:
Imported CSV Files – Loaded customer.csv and credit_card.csv into SQL.
Created SQL Tables – Defined customer and credit_card tables with primary and foreign keys.
Performed Data Cleaning – Removed duplicates, handled missing values, and formatted dates.
Loaded Data into Power BI – Connected SQL tables to Power BI for visualization.
Created DAX Columns –
Week_Num2 – Extracted the week number from the transaction date.
Week_Start_Date – Calculated the start date of each week.
Created DAX Measures –
Current_Week_Revenue, Previous_Week_Revenue, WOW_Revenue, WOW_Growth_Percentage
Total Transactions, Total Customers, Average Transaction Value
Built Dashboards in Power BI –
Transaction Report Dashboard – Analyzes total revenue, WoW growth, transaction trends, and payment methods.
Customer Report Dashboard – Tracks customer segmentation, spending behavior, and new vs. returning customers.




Project Insights : Week 53 (31st Dec)
 WoW change: 
• Revenue increased by 28.8%, 
• Total Transaction Amt & Count increased by xx% & xx%
 • Customer count increased by xx%
 Overview YTD:
 • Overall revenue is 57M
 • Total interest is 8M
 • Total transaction amount is 46M
 • Male customers are contributing more in revenue 31M, female 26M
 • Blue & Silver credit card are contributing to 93% of overall 
transactions
 • TX, NY & CA is contributing to 68%
 • Overall Activation rate is 57.5%
 • Overall Delinquent rate is 6.06%

