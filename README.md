# Global-Electronics-Retailer
Sales data for a fictitious global electronics retailer, including tables containing information about transactions, products, customers, stores and currency exchange rates.

 # OBJECTIVE 
 - You'vce just been hired as a Data Analyst for Maven Electronics, a global retailer that sells computers, cell phones, TVs, Cameras, Appliances and more, both online and in store.

# The ASSIGNMENT
- Revenue has been on a download trend since 2020,and management needs your help consolidating the data to conduct an exploratory analysis.
 Your goal is to use the csv files provided to build a data model and interactive report that the management team can use to explore performance.

# The ObJECTIVE 
1. Profile and prepare the data
2. Build a relational data model
3. Enrich and explore the data
4. Build an interactive report

<h2># Objective 1: Prfile & Prepare the data </h2>

- Connect  to the Sales csv file and profile the data. How many orders were recorded? Ovber what time period? Do you notice anything intersting about delivery dates?
  - Add a TransactionKey field to uniquely identify  each row
- Connect to the Product csv file and profile the data. What does the company sell? How many  distinct categories and subcategories do you see?
- Connect to the Sales csv file and profile the data. How many sotres does Maven Elctronics operate? Do you notice any that aren't like the others?
- Connect to the Exchange_rates csv file and profile the data. What information does this table contain, and how could it be used?

<h2># Objective 2: Build A Realational Model </h2>

- Create raeational from the Sales table to Customera, Stores, Product and Calender.
- What happens when you try to connect Sales to Excahnge Rates? Add a new column  to both tables named ExchangeKey and use that field to relate them via a 1.many relationship.
- Hide all foreign keys the Sales table
- Bonus split the Products table into category and subcategory-level dimension tables, and update the data modle to relate these new tables.

<h2># Objective 3: Enrich & Explore The Data </h2>

- Add a blank, dedicated measures table.
- Create a new measure to calculate Total Orders based on Order Number
- Calculate Total Revenue (USD), based on Quantity and Unit Price (USD)
- Calculate Average Order Value (Aov), based on Total Revenue (USD) and Total Orders.
- Calculate Average Delivery Time in Days

<h2># Objective 4: Build An Interactive Report </h2>
 
- Show orders, revenue, AOV and average delivery time as KPI cards
- Show revenue by month as a Line Chart, and by product Category a bar cahrt
- Add slicers for StoreKey and Year, connect to all cards and visuals
- Adjust fromatting and polish for calrity and readability
- What trends anjd pattrens do you see? Where would you suggest digging deeper?
