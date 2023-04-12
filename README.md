# Data-Analyst-Portfolio
SUPERMARKET DATA
ABOUT THE DATASET
The growth of supermarkets in most populated cities are increasing and market competitions are also high. The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data. In this analysis, the tasks are to find the main revenue stream i.e., where most revenue comes from? (b) the best performing product line, branch and payment method, and (c) where are most taxes paid?

DATA SOURCE
https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales?resource=download 

SKILLS
Data cleaning, Data aggregation, Desktop design, DAX, Data visualization, and Data insights

PROCESS
✅ I reviewed the data to find any bad data points, missing data, and duplicated data to perform accurate analysis, visualize the data, and draw actionable insights.  
✅Then, I cleaned and transformed the data.
✅Data cleaning manipulation and transformation
•	The data used in this analysis is titled ‘supermarket-sales’ and include the following fields
1.	Invoice id: Computer generated sales slip invoice identification number
2.	Branch: Branch of supercenter (3 branches are available identified by A, B and C).
3.	City: Location of supercenters
4.	Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.
5.	Gender: Gender type of customer
6.	Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel
7.	Unit price: Price of each product in $
8.	Quantity: Number of products purchased by customer
9.	Tax: 5% tax fee for customer buying
10.	Total: Total price including tax
11.	Date: Date of purchase (Record available from January 2019 to March 2019)
12.	Time: Purchase time (10am to 9pm)
13.	Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)
14.	COGS: Cost of goods sold
15.	Gross margin percentage: Gross margin percentage
16.	Gross income: Gross income
17.	Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10) 
•	The schema of the file type (CSV), data structure (single table), # of records (1001) and # of fields (17).
•	During the process of data cleaning, I identified errors in the data types for the fields related to Unit Price, Quantity, Tax, Total, Date, Time, Payment, COGS, Gross margin percentage, Gross Income and Rating'. These fields were transformed to numeric data except for Date that was formatted to DD/MM/YYYY and COGS in Currency $. 
•	There are no missing values in the table.
•	And DAX formula was used to calculate the total sales, tax, quantity sold, and gross margin. 
✅Performed simple DAX 
✅ Final step was to divide into the cleaned data and obtain important insights such as the trend of revenue in the last months, the top performing product line, branch, the most used means of payment, total revenues to the state in terms of tax paid, and the product that got the best rating. 

TOOLS
Excel, Power Query, MPBI.

INSIGHTS
Over the course of three months, the total sales amounted to $322,970, with a total of 5510 items sold across all branches. The cost of goods sold (COGS) initially decreased by 5.44% between January 1 and March 30, 2019, but started increasing on March 12, 2019, with a 22.01% rise ($770.96) in 18 days. The steepest incline occurred between January 1, 2019 and January 19, 2019, during which the COGS jumped from $4,519.22 to $4,680.69.

Female customers had a higher COGS sum of $159,888.5 compared to male customers' $147,698.88, accounting for 51.98% of the total COGS. In terms of branch revenue, Branch C had the highest revenue of $105,303.53, followed by Branch A and B at $101,143.21 and $101,140.64, respectively. Branch C also accounted for 34.24% of the total COGS.

The most sold product category was electronic accessories, with 971 pieces sold, generating a total revenue of $51,750.03. However, the total number of product pieces sold decreased by 17.28% between January 1 and March 30, 2019, with a steep decline of 44.83% (39) in 9 days from March 19, 2019. Fashion accessories received the highest customer satisfaction rating, accounting for 36.36% of the top 1 rating.

When it comes to payment methods, most customers preferred to pay in cash, which had the highest COGS at $106,863.4, followed by e-wallet at $104,755.34, and credit card at $95,968.64. Cash payment accounted for 34.74% of the total COGS.

The total tax paid to the states is $15,380 at a gross margin percentage of $4,760 on total sales. The total tax trended down by 5.44% between January 1 and March 30, 2019, but started trending up on March 12, 2019, with a 22.02% increase of $38.56 in 18 days. The steepest incline occurred between January 1, 2019, and January 19, 2019, during which the total tax jumped from $225.97 to $234.04.

Moreover, the total gross margin percentage trended down by 8.33% between January 1 and March 30, 2019, and started trending down on March 13, 2019, with a 20.00% decrease of 9.52 in 16 days. The steepest incline occurred between January 21, 2019, and January 27, 2019, during which the total gross margin percentage jumped from 38.08 to 66.64.

Data source: https://absentdata.com/data-analysis/where-to-find-data/ 

