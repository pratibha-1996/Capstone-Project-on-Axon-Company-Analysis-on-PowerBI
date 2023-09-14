# Capstone-Project-on-Credit-card-database
The project contains a dataset which contains data regarding Axon company and details through a dashboard. This Project is part of Odin School Bootcamp.
**Analysis of Axon company’s dataset using Power BI**
**Objective:** To contribute to the success of a business by utilising data analysis techniques, explicitly focusing on time series analysis, to provide valuable insights.
•	**Calculation of Average days: **
Avg days = IF(ISBLANK('classicmodels orders'[orderDate]) || ISBLANK('classicmodels orders'[shippedDate]),BLANK(),DATEDIFF('classicmodels orders'[orderDate],'classicmodels orders'[shippedDate], DAY))	
•	Out of 326 orders, 303 were shipped. 
•	Classic cars were most sold and have the latest quantity in stock
•	Office 4 has maximum sales
•	Vendor Lin Diecast has maximum sales among all the vendors.
•	USA has maximum sales among 21 countries.
