# Starbucks-Customer-Analysis
## Table of contents
## Glossary
- EDA: Exploratory Data analysis
- Revenue:  the total amount of money brought in by a company's operations, measured over a set amount of time.
- Average: an average is a single number or value that best represents a data set.
- Sales: Unit price * quantity
- KPIs: Key Point Indicators are metrics used to measure the business's success.
- Metrics: a system or standard of measurement.
- profit: The income gotten after expenses.
- Expenses: These are the money spent or costs incurred in a company's revenue-generating efforts.
- Coffee blends: A synonym for the product ID
  
## Project Overview
This project aims to answer stakeholder questions and Key Point Indicators that affect the business's success. Furthermore, the report will account for the data sources & types used as well as its cleaning and transforming processes, and finally, the insights obtained from the Exploratory Data Analysis and the recommendations one can provide by the information.

## Dashboard
A visual representation of all the insights from the exploratory data analysis with time, roast type, size and loyalty card.<br /> <br /> ![Screenshot (463)](https://github.com/Tyroneekhator/Starbucks-Customer-Analysis/assets/72547969/a2958319-70ea-4b33-87ae-15c6e37c9bfe)

## Data sources used
- An unclean CSV file containing three worksheets: orders, customers and products.
## Columns in the dataset
- Order ID: The unique identifier of each purchase the customer makes.
- Order date: The time at which the purchase took place.
- Order Day: The day of the week the order was made.
- Order Month: The month of the year the order was made.
- Customer ID: the idiosyncratic code given to each customer.
- Product ID: A distinct code for a product purchased which is the combination of the initials of the coffee type; roast type; and size of the cup. Likewise, the product ID in the analysis is called the coffee blend.
- Quantity: The number of items purchased
- Customer Name: The full name of each customer
- Customer Email: The email of each customer.
- Country: The geographical location of where the item was purchased.
- City: the city where it was bought.
- Coffee type: type of coffee beans.
- Roast type: how the beans are roasted.
- Size: the size of the cup measured in KGs.
- Unit Price: the initial price of one item purchased by the customer.
- Sales: Unit price * Quantity
- Profit for the business: the money from each purchase after expenses.
- Loyalty card: Whether a customer has a loyalty card or not.
- Phone Number: the telephone number of each customer.
- Address Line: the address of each customer.
- Postcode: the postcode of each customer.
- Price per 100g: the cost when the item is 0.1kg.
## Tools Used
- Excel: A spreadsheet software that features calculation or computation capabilities, graphing tools, pivot tables, and a macro programming language called Visual Basic for Applications.
## Data cleaning and  transforming process
- Check for duplicates
- Check for null values
- Added new columns namely Order Day; Order month and Sales
- Used 'XLOOKUP' & 'INDEX MATCH' to extract data from the spreadsheet.
- Formula was used to get sales.
    - Sales = Unit price * Quantity
- Used the 'Text' function to get the day & month from the 'order date' column.
- Created pivot to start Exploratory Data Analysis
- Use filter panels for the dashboard
## Stakeholder questions and Key Point Indicators(KPI'S)
1. Total revenue for Starbucks
2. Average size of cup ordered
3. Average bill per order
4. Total cups sold
5. Daily trends of Starbucks revenue
6. Sales revenue by country
7. Percentage (%) of the most ordered coffee blends
8. the most expensive coffee blends
9. top selling coffee blends
10. customer that has generate the most revenue
