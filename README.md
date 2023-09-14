# AC-Data-Modeling
Algonquin College Data Modelling project. Build a data model and dashboards using Power BI

# Requirements
Build a star schema and create calculated column/DAX Measures to create below visualization:

2A
- GrossProfitAmount: The SalesAmount less TotalProductCost.
- GrossProfit(%): The GrossProfitAmount divided by SalesAmount.
- NetProfitAmount: The GrossProfitAmount less Freight and Taxes.
- NetProfit(%): The NetProfitAmount divided by SalesAmount.
- TaxRate(%): The TaxAmount divided by SalesAmount.
- SalesCommissionAmount: a 1% commission from total sales amount to the sales employee up to a maximum of $50,000 in the native currency.


2B
- SalesToPreferredReseller: Total Sales sold to resellers with annual sales equal or above $1,000,000
- NegativeGrossMargins: Total Gross Margin Amounts that are less than zero
- USABicycleSales: Total Sales made for bicycles in the United States of America.


3A: Sales Dashboard

Business users at AdventureWorks would like you to create an interactive dashboard showing the breakdown of their sales by the following:
- Breakdown by SalesTerritory
- Breakdown by Product Categories and Subcategories
- Breakdown by Sales Persons with their sales commissions


3B - Reseller Profile Dashboard

Business users at AdventureWorks would like to better understand the types of resellers they are selling to create an ideal profile for their sales and marketing teams to prioritize leads. Based on your understanding of the DimReseller table, create a dashboard showing the profile of the resellers using at least 3 attributes.


3C

Management would like your help to understand the following – find the answer using any method of your choice but show your work (i.e. create a visual or leave the filters applied):
- How many (count) products have been sold at a loss (negative gross margin)?
- What are the top 3 most popular colours for bicycles?
- Is there a relationship between the resellers with the highest sales amounts and lowest gross margin (i.e. are we selling more in bulk but at a lower margin)?
