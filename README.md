# WALMART SALES ANALYSIS

### Objective
The aim of this project is to explore Walmart sales data to analyze customer behavior, performing branch and sales trends of products over time in order to know how sales can be influenced and increased.

### The Dataset
This dataset was obtained from Kaggle Walmart Sales Forecasting Competition and it contains sales information from three Walmart branches located in Mandalay, Yangon and Naypyitaw. The dataset contains 1000 rows and 17 columns which are;
- Invoice_id
- Branch
- City
- Customer_type
- Gender
- Product_line
- Unit_price
- Quantity
- VAT
- Total
- Date
- Time
- Payment_method
- Cogs
- Gross_margin_percentage
- Gross_income
- Rating
- 

## Procedure Used
### Build Database
   A database was first created in MySQL Workbench. The  table was afterwards created and the data imported in order to get a good understanding of the dataset.

### Data Cleaning and Transformation
This step involves the cleaning and transformation of the data to prepare it for analysis. It involves the following steps;
- Data formatting
- Handling missing values
- Handling duplicate values
- Data extraction

### Feature Engineering
This involves creating new columns from existing ones

### Exploratory Data Analysis
This is done to carry out the aim of the project and also to answer questions derived from the data.

## Questions
### General Questions
1. How many unique cities does the data have?
2. In which city is each branch?
### Product Questions
1. How many unique product lines does the data have?
2. What is the most common payment method?
3. What is the most selling product line?
4. What is the total revenue by month?
5. What month had the largest COGS?
6. What product line had the largest revenue?
7. What is the city with the largest revenue?
8. What product line had the largest VAT?
9. Fetch each product line and add a column to those product lines showing "Good", "Bad". Good if it's greater than average sales
10. Which branch sold more products than average?
11. What is the most common product line by gender?
12.What is the average rating of each product line?
###  Sales Questions
1. Number of sales made in each time of the day per weekday
2. Which of the customer types brings the most revenue?
3. Which city has the largest tax percent/ VAT (Value Added Tax)?
4. Which customer type pays the most in VAT?
### Customer Questions
1. How many unique customer types does the data have?
2. How many unique payment methods does the data have?
3. What is the most common customer type?
4. Which customer type buys the most?
5. What is the gender of most of the customers?
6. What is the gender distribution per branch?
7. Which time of the day do customers give the most ratings?
8. Which time of the day do customers give the most ratings per branch?
9. Which day of the week has the best avg ratings?
10. Which day of the week has the best average ratings per branch?

### Calculations & Formulas
1. Cost of Goods Sold(COGS): 
COGS = Unit Price * Quantity 
2. Value Added Tax:
VAT = 5% * COGS
3. Gross Profit:
Gross Profit(Gross Income) = Total(gross_sales) - COGS




