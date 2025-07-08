# Starbucks-Customer-Analysis
## Table of contents
- [Glossary](#glossary)
- [Project Overview](#project-overview)
- [Dashboard](#dashboard)
- [Data sources used](#data-sources-used)
- [columns in the dataset](#columns-in-the-dataset)
- [Tools used](#tools-used)
- [Data cleaning and  transforming process](#data-cleaning-and-transforming-process)
- [Stakeholder questions and Key Point Indicators](#Stakeholder-questions-and-Key-Point-Indicators)
- [Insights gotten from the analysis](#insights-gotten-from-the-analysis)
- [Recommendations based on the analysis](#recommendations-based-on-the-analysis)
## Glossary
- EDA: Exploratory Data Analysis
- Revenue:  the total amount of money brought in by a company's operations, measured over a set amount of time.
- Average: An average is a single number or value that best represents a data set.
- Sales: Unit price * quantity
- KPIs: Key Point Indicators are metrics used to measure the business's success.
- Metrics: a system or standard of measurement.
- profit: The income gotten after expenses.
- Expenses: These are the money spent or costs incurred in a company's revenue-generating efforts.
- Coffee blends: A synonym for the product ID
  
## Project Overview
This project aims to answer stakeholder questions and Key Point Indicators that affect the business's success. Furthermore, the report will account for the data sources and types used, as well as their  data cleaning and transformation processes. Finally, it will provide insights obtained from the Exploratory Data Analysis and recommendations that can be made based on the information.

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
## Stakeholder questions and Key Point Indicators
1. Total revenue for Starbucks
2. Average size of cup ordered
3. Average bill per order
4. Total cups sold
5. Daily trends of Starbucks' revenue
6. Sales revenue by country
7. Percentage (%) of the most ordered coffee blends
8. the most expensive coffee blends
9. top selling coffee blends
10. customer that has generated the most revenue
## Insights gotten from the analysis
1. Based on the diagram below one can see the total revenue, average size of cups ordered, average bill per order and total cups sold by the barista company <br />![Screenshot (464)](https://github.com/Tyroneekhator/Starbucks-Customer-Analysis/assets/72547969/bb3228d6-fefe-44a1-85d1-33bc27901266)
2. The next image is the filter panel. This allows one to filter the data based on time, roast type, size of the cup and whether a customer has a loyalty card or not. <br /> ![Screenshot (465)](https://github.com/Tyroneekhator/Starbucks-Customer-Analysis/assets/72547969/67da8de2-d7f5-47f4-9aa5-a2ea7e29c8b3)
3. Moreover, the dashboard covers the revenue generated by days of the week. Likewise, from the chart, the most profitable days are Friday and then Sunday respectively. <br />  ![daily trend  of starbucks revenue](https://github.com/Tyroneekhator/Starbucks-Customer-Analysis/assets/72547969/6d8280c6-8b05-4133-aee6-8d8e47f3890b)
4. The sales revenue by country indicates that America generates the most revenue with it having the most Starbucks stores in the world. <br /> ![sales revenue by country](https://github.com/Tyroneekhator/Starbucks-Customer-Analysis/assets/72547969/2131b156-0a37-425d-9a6a-3804859afc63)
5. Percentage of the most ordered coffee blends: From the visualization, it can be observed that R-L-0.2 is the most ordered coffee blend across all stores. <br /> ![pie_chart](https://github.com/Tyroneekhator/Starbucks-Customer-Analysis/assets/72547969/2c185320-aa56-478d-a77b-7ae16915233f)
6. The most expensive coffee blends: the chart shows the expensive products the shops have.<br />![expensive coffee blends](https://github.com/Tyroneekhator/Starbucks-Customer-Analysis/assets/72547969/cc1eebe9-456f-44cd-a2de-ba17f4f8dc27)
7. Top-selling coffee blends. The top 5 products that generate the most revenue. <br /> ![top selling coffee blends](https://github.com/Tyroneekhator/Starbucks-Customer-Analysis/assets/72547969/15597392-3a27-484f-8832-326da3e1bb9e)
8. Customers that generate the most revenue. It can be acknowledged that 'Allis Willmore' followed by 'Brenn Dundredge' brings in the most money for the business. <br /> ![customer most revenue](https://github.com/Tyroneekhator/Starbucks-Customer-Analysis/assets/72547969/df24cd02-9fa9-439c-b574-e52c98966b8f)
## Recommendations based on the analysis
No serious recommendations can be given only just making sure that the most profitable days are equipped with enough stock and a reward being given to the customer that has generated the most revenue.

