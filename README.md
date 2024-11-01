# SALES PERFORMANCE ANALYSIS ON RETAILS STORE

#INTRODUCTION
In a retail environment, data analysis plays a crucial role in understanding customer behavior, optimizing inventory, and enhancing sales strategies. 
This project focuses on analyzing sales data for a retail store specializing in fashion such as shoes and clothing items.
By examining transaction records, customer demographics, product performance, and seasonal trends, this analysis aims to uncover valuable insights
that can inform business decisions and drive growth.

# PROJECT OBJECTIVES
The primary objectives of this data analysis project are to:

1. Understand Customer Preferences: Identify which fashion categories, styles, and price points resonate most with customers.


2. Optimize Inventory Management: Determine fast-moving and slow-moving items to ensure optimal stock levels, reducing overstock and stockouts.


3. Analyze Sales Trends:Track sales trends across region,  and promotional periods to align inventory and marketing efforts with high-demand times.


4. Customer Segmentation: Segment customers based on purchase patterns and demographics to personalize marketing and improve customer retention.
  
5. It will involve analyzing the most frequently used product categories, identifying the region with the highest sales,
and examining how sales evolve month by month. In essence, this project will aid in identifying the factors that influence customer behavior

# DATA DESCRIPTION

The dataset includes the following fields:

* ORDER ID: A unique identifier for each individual order. This ID helps in tracking orders across different transactions, 
ensuring each sale or order is distinct

* CUSTOMER ID: A unique identifier for each customer. It allows for tracking purchase behavior, frequency, and segmentation based on customer-related metrics
  
* REGION: The region on which each product is been sold by different outlet ( North, South, East and South)

* PRODUCT: The name or ID of the product sold. This allows for analysis of product popularity, revenue contribution, and inventory management.

* ORDER DATE: The date on which the order was placed. This helps in understanding sales patterns over time, such as seasonal trends, peak periods, and customer buying habits.

* QUANTITY SOLD: The number of units of the product sold in each order. It helps in understanding demand, inventory turnover, and contributes to revenue calculations.

* TOTAL REVENUE: The total sales revenue generated from each order. It can be calculated as Quantity Sold * Price per Unit. This is essential for revenue analysis, profit calculations, and sales performance metrics.
  
*AVEARAGE REVENUE PER PRODUCT: The average revenue generated per product in a given period. This can be calculated by dividing the total revenue by the quantity sold peR PRODUCT

# METHODOLOGY

 ## DATA COLLECTION
The dataset for this project was made available by Konga, Konga, is a leading e-commerce platform in Nigeria , that provide access to anonymized sale data for reseach and learning.
The data was provide inCSV format, making it easliy accessible for analysis

## DATA MANIPULATION
1. *DATA CLEANSING
    - All duplicated data were removed using Data validation method.Remove duplicates (Data > Data Validation > Remove Duplicates)
    - Handle missing values (Find & Select > Go To Special > Blanks)
    - Remove unnecessary characters (Text to Columns, Flash Fill)
2.  *DATA NORMALIZATION :
    - Convert text to uppercase/lowercase (FORMULATEXT, LOWER/UPPER)
    - Standardize date formats (Text to Date, DATE function)
    - Normalize numeric values (ROUND, TRUNC)
3. *Data Transformation:
    - Pivot data (PivotTables)
    - Transpose data (Paste Special > Transpose)
    - Group data (Group By)
    - Aggregate data (SUM, AVERAGE, COUNT)
4. *Data Merging:
    - Combine datasets (VLOOKUP, INDEX-MATCH)
    - Merge tables (Power Query, Merge & Append)
5. *Data Splitting:
    - Split columns (Text to Columns)
    - Split rows (Filter, Group By)

Microsoft Excel Functions:

1. Text functions: LEN, LEFT, RIGHT, FIND, REPLACE
2. Date functions: DATE, DATEDIF, EOMONTH
3. Numeric functions: ROUND, TRUNC, RAND
4. Logical functions: IF, IFERROR, IFBLANK
5. Lookup functions: VLOOKUP, INDEX-MATCH

Power Query:

1. Import data (From File, From Database)
2. Transform data (Group By, Pivot, Merge)
3. Load data (Load To, Load To Worksheet)

Data Analysis Tools:

1. PivotTables
2. Charts (Column, Line, Bar)
3. Conditional Formatting
4. Data Validation

Best Practices:

1. Document transformations
2. Verify data integrity
3. Use meaningful column names
4. Test transformations
5. Version control

Example Transformations:
1. Group sales by region
=PivotTable (Region, SUM(Sales))

Common Data Transformation Challenges:

1. Handling missing values
2. Dealing with inconsistent data formats
3. Merging large datasets
4. Optimizing performance

## DATA CLEANSING AND PREPARATION
For this project, I will use Microsoft Excel, SQL, and Power Bi with detail data analysis. The data was collected from Fashion retailer stores from FOUR (4) regions from 2023 to 2024. This comprehensive dataset aims to offer insights into shopping habits and provide a valuable understanding of shopping patterns
##PROJECT OBJECTIVE The primary objective of this data analysis is to comprehend and identify trends in customer purchasing behavior. It will involve analyzing the most frequently used product categories, identifying the region with the highest sales, and examining how sales evolve month by month. In essence, this data analysis will aid in identifying the factors that influence customer behavior



## How much is the total  revenue by product?
To obtain the results, Microsoft Excel formulas was used

### Total Revenue by Product= Quantity Sold*Price per Unit
### Total Revenue by Product= F2*G2
Where F2 represent the quantity Sold and G2 represent Price per Unit

*PIVOT TABLE* : Pivot table will be used to work on  Data calculated suing excel formulas such data  summarization,
Data Filtering. Comparison, data reshaping and proper Analysis
ANALYSIS QUESTIONS
 Using Excel formulas to calculate metrics such as;
1.	What is the Total Average sales per product 
2.	What is the Total revenue by region 

Using pivot table to extract;

3.	What are the total sales by product
4.	What are the total Sales by region   
5.	What are the Average sales by product
6.	Analysis total product ordered by each region?
7.	Calculate Monthly Sales Trend? 
8.	Calculate the amount of product ordered by each of the region monthly?
9.	Identify the product with the Highest and Lowest sale by Region?
10.	What are the percentage of total sales by each region?
           
Using SQL, write Queries on how to extract key insights based on the following questions.  
o Retrieve the total sales for each product category. 
o Find the number of sales transactions in each region. 
o Find the highest-selling product by total sales value. 
o Calculate total revenue per product. 
o Calculate monthly sales totals for the current year. 
o Find the top 5 customers by total purchase amount. 
O Calculate the percentage of total sales contributed by each region. 
o Identify products with no sales in the last quarter. 





*The sales revenue spike from #248,000  in Januray to #546,300 February contributing to 45% increase in total sales and this can be related to some of the reasons listed below;

1. Valentine's Day: Many people buy clothing, accessories, and gifts for Valentine's Day, creating a surge in sales. Couples may purchase new outfits for dates, and retailers often offer Valentine's-themed promotions and discounts.
2. Spring Fashion Releases: February is a key time for brands to introduce spring collections, generating interest and demand as people begin shopping for the upcoming season.
3. New Year Promotions and Clearance Sales: Leftover stock from the holiday season often goes on clearance, which attracts bargain-hunters looking for discounted fashion items.
4. Events and Celebrations: Some regions have cultural events


![image](https://github.com/user-attachments/assets/7acfb28d-8473-4ff6-b7a9-5bf8b81061cc)


Tracing the product to the primary data collected I noticed that various product are been sold at different prices in various location.
For example Hat is sold in the East for #15 per unit, same Hat is been sold in the west for #50 per and also sold #10 in the North and this can be traced 
To some of the factors that affect demand and supply such product such product scarcity, cost of transportation. When cost of delivering product to particular
Location is high, cost of such product will be high. Also when demand for a particular product is very high, price per product will increases. 
For Example cost of shoes, socks will increased in the Month of September when the children in primary school and secondary school resume new school session and vise visa


TOTAL UNIT SOLD BY REGION AND TOTAL UNIT SOLD  BY PRODUCT
![image](https://github.com/user-attachments/assets/dce153a8-e347-4b4f-b109-2e28dd292d34)

From the above table it is seen that Southern region recorded the higest sales by quantity 
and items purchased are shoes (9930). Gloves (9903) and Sock (4464) while in Western  recorded the 
lowest sales and item purchased by those region are Hat (3486), Socks (3457). Gloves (2465)
Shoes (1992).This shows that in the Western region most customers cannot affort the high cost most of the product due to theie level of incom

