# SOPHIEMATRIS SUPERMARKET SALES PERFORMANCE ANALYSIS 

# INTRODUCTION
**In a retail environment, data analysis plays a crucial role in understanding customer behavior, optimizing inventory, and enhancing sales strategies**. 
**This project focuses on analyzing sales data for a retail store specializing in fashion such as shoes and clothing items.**
** By examining transaction records, customer demographics, product performance, and seasonal trends, this analysis aims to uncover valuable insights
that can inform business decisions and drive growth**.

# PROJECT OBJECTIVES
**The primary objectives of this data analysis project are to**:

1. **Understand Customer Preferences: Identify which fashion categories, styles, and price points resonate most with customers**.


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

### BASIS STASTICS ABOUT THE DATASET

* Total revenue by product: #2,101,090
* Total Average sales per product: #2,094,317
* Total Quantity sold by product: 68,461
* Region with highest sale total revenue:#927,820
* Top selling Product total revenue:
* Product category : 6
 


### METHODOLOGY

 ## DATA COLLECTION
**The dataset for this project was made available by Konga, Konga, is a leading e-commerce platform in Nigeria ,
that provide access to anonymized sale data for reseach and learning.**

**The data was provide inCSV format, making it easliy accessible for analysis*8

## DATA MANIPULATION
1. *DATA CLEANSING
    - **All duplicated data were removed using Data validation method.Remove duplicates (Data > Data Validation > Remove Duplicates)
    - **Handle missing values (Find & Select > Go To Special > Blanks)**
    - **Remove unnecessary characters (Text to Columns, Flash Fill)**
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
3. **Use meaningful column names**
4. T**est transformations**
5. **Version control**

**Example Transformations:**
1. **Group sales by region**
**=PivotTable (Region, SUM(Sales))**

**Common Data Transformation Challenges:**

1. Handling missing values
2. Dealing with inconsistent data formats
3. Merging large datasets
4. Optimizing performance

## DATA CLEANSING AND PREPARATION
**For this project, I will use Microsoft Excel, SQL, and Power Bi with detail data analysis. The data was collected from Fashion retailer stores from FOUR (4) regions from 2023 to 2024. This **comprehensive dataset aims to offer insights into shopping habits and provide a valuable understanding of shopping patterns**

##PROJECT OBJECTIVE

**The primary objective of this data analysis is to comprehend and identify trends in customer purchasing behavior. It will involve analyzing the most frequently used product categories, identifying the region with the highest sales, and examining how sales evolve month by month. In essence, this data analysis will aid in identifying the factors that influence customer behavior**



## How much is the total  revenue by product?
To obtain the results, Microsoft Excel formulas was used

### Total Revenue by Product= Quantity Sold*Price per Unit
### Total Revenue by Product= F2*G2
Where F2 represent the quantity Sold and G2 represent Price per Unit

*PIVOT TABLE* : **Pivot table will be used to work on  Data calculated suing excel formulas such data  summarization,
Data Filtering. Comparison, data reshaping and proper Analysis**

### TOOLS USED
* Microsoft Excel
* SQL
* Pewer BI
  
### ANALYSIS QUESTIONS
 Excel formulas are used to calculate metrics;
1.	What is the Total Average sales per product 
2.	What is the Total revenue by region

 pivot table to used to extract;

3.	What are the total sales by product
4.	What are the total Sales by region   
5.	What are the Average sales by product
6.	Analysis total product ordered by each region?
7.	Calculate Monthly Sales Trend? 
8.	Calculate the amount of product ordered by each of the region monthly?
9.	Identify the product with the Highest and Lowest sale by Region?
10.	What are the percentage of total sales by each region?


![image](https://github.com/user-attachments/assets/1b13e78e-cdff-48c1-842c-6c703d5fc668)


 ![image](https://github.com/user-attachments/assets/c8c026f9-8dc5-4476-bfe5-417857942852)
 
![image](https://github.com/user-attachments/assets/9a1fbbe4-d2fa-4a4b-b13c-b68ea57ca7ac)




## EXPLORATORY DATA ANALYSIS ON SALES PERFORMANCE USING SQL

Using SQL, write Queries on how to extract key insights based on the following;

* Retrieve the total sales for each product category. 
*  Find the number of sales transactions in each region. 
*  Find the highest-selling product by total sales value. 
* Calculate total revenue per product. 
* Calculate monthly sales totals for the current year. 
* Find the top 5 customers by total purchase amount. 
*  Calculate the percentage of total sales contributed by each region. 
* Identify products with no sales in the last quarter.
 
**In this portfolio project, I conducted an analysis of Sophiematrissales data using SQL queries with dataset Schema
[dbo].[SALESDATA] with following field details;**

*OrderID
* Customer_id
* Product
* Region
* orderDate
* Quantity_Units_Sold
* Unit_price
* Total_revenue_Per_Product
* Average_Unit_Product
* Month
* Quarter

![image](https://github.com/user-attachments/assets/b108526a-6c14-47f1-bed1-65b11d1c568f)

![image](https://github.com/user-attachments/assets/d087af0c-a6f7-42a2-a756-dedcb51f8371)

![image](https://github.com/user-attachments/assets/c234846b-a981-42b9-8f46-b363aa888a48)

![image](https://github.com/user-attachments/assets/df7ef79e-20de-47a9-b37e-e367b2eed107)

![image](https://github.com/user-attachments/assets/0e3bf53d-f33b-40ef-b38b-b3ce0145eee5)

![image](https://github.com/user-attachments/assets/959af8b6-9128-4e81-9155-3b9dab532628)

![image](https://github.com/user-attachments/assets/594011c9-6d07-41d2-8afe-4f7704080038)

![image](https://github.com/user-attachments/assets/adb2cb6b-e3c4-402e-bc05-996c88519209)



 ### Details anlyzed data from SQL. I used SQL to query the data from the database and imported into PowerBI where the actual analysis was carried out. 
 
![image](https://github.com/user-attachments/assets/3283dde4-d6d0-44a0-99f3-cb3954e2d5b1)

![image](https://github.com/user-attachments/assets/8fbaa5c7-ea5a-45ee-8453-aca8ac946dda)

 ![image](https://github.com/user-attachments/assets/4fa58d32-475a-4a08-b638-b55804925e6f)
 
![image](https://github.com/user-attachments/assets/6d299e92-090a-425a-8e74-5628b6ce9904)

![image](https://github.com/user-attachments/assets/2ac372bb-a395-42b7-99c0-a25e684121cb)

## SALES PERFORMANCE GENERAL DASHBOARD

![image](https://github.com/user-attachments/assets/24ca816c-8527-45d5-ad13-c4ae8743c844)


## PRODUCT WITH THE HIGHEST SALES REVENUE (SHOES)

 ![image](https://github.com/user-attachments/assets/de6b8211-8dd6-4ad1-b66a-4c8409cf8301)



## REGION WITH THE HIGEST SALES REVENUE

![image](https://github.com/user-attachments/assets/368d309b-3874-48f1-9f04-0d0c7fcf69ea)

* **This analysis is based on the Southern region sales with total revenue of #927,820;
Regional Performance (Southern Region of Nigeria)**

*   **Product-wise Contribution to Total Sales Revenue**
  
* **Gloves: 14.13% of total sales with total sales of #247,600**
  
* **Socks: 8.60% of total sales with total sales of #133,920**
* **Shoes: 29% of total sales with total sales of #546,300 which happened to be the highest selling product within the reporting period.**

* **Total Quantity Sold in the southern region: 24,298 units**
  
* **Customer Insights**
  
* **Total Number of Distinct Customers: 500**

* **Average Purchase Volume per Customer:  units per customer**

## Key Insights:

**Shoes are the highest revenue contributor at 29%, which might indicate they are either priced higher or have a higher volume sold than other products.
Average Revenue per Customer in the southern region suggests a moderate customer spending pattern.**
**Gloves and socks, despite being essential items, contribute significantly less, so they may require focused sales strategies for growth**.

**Monthly transaction details shows that in February sum of five hundred and forty six thousand was achieved (#546,300) and happened the month with 
highest sales in the year and product sold was shoes, also in June total sales amounted to two hundred and forty seven thousand six hundred naira 
(#247,600) while in October sum of one hundred and thirty three thousand was recovered (#133,920).**

#### These insights we guide on where to channel the organization marketing efforts or possibly adjust product strategies to boost sales in other regions

## THE WESTERN REGION HAPPENED TO BE THE REGION THAT RETRIVE THE LOWEST TOTAL INCOME

![image](https://github.com/user-attachments/assets/fe2b6630-4637-4b6f-9437-ad49c2b63013)



**From Table 1 ,2,3 & 4 above  total revenue and total average sale per product  indicated that
Shoes  are  highly demanded by customers yielded totals sales revenue of #613,380 and which signify 29.1%  of
Total revenue.**

  **Shirt is the second items highly patronized by customers, shirt had total sales 
 Of #485,600 while socks is the least purchased product with total revenue of #180,785 which amounted to 8.6% of total revenue.**

**Customers may purchase more shirts and shoes compared to hats, jackets, and gloves for several reasons related to fashion trends, 
utility, and consumer behavior**:

* **Versatility: Shirts and shoes are often more versatile and can be worn in a variety of settings. A good shirt can be dressed up or**
  **down, making it suitable for casual outings, work, or formal events. Similarly, shoes, especially styles like sneakers or loafers,
  can complement a wide range of outfits and occasions.**

*  **Frequency of Use: Shirts and shoes are everyday essentials. People tend to wear shirts regularly, often needing multiple options for
   different occasions, while shoes can also vary based on style, activity (like running vs. casual), and season.**
* **Fashion Trends: Trends can significantly influence purchases. Shirts, being a staple item in most wardrobes, are frequently
  updated with new styles, colors, and patterns. Footwear trends also evolve, leading to increased consumer interest and purchasing
   frequency for shoes.**

* C**omfort and Fit: Consumers often prioritize comfort in clothing choices. Well-fitting shirts and comfortable shoes are crucial for
 daily wear, whereas items like jackets and gloves might not be needed as frequently, depending on the climate.**

* **Price Points: Shirts and shoes can be found in a wide range of price points, making them accessible to a broader audience.
  This accessibility can encourage more purchases, as customers feel they can find options within their budget**.

* **Emotional Purchase Factors: Clothing is often tied to personal expression and identity. Customers may feel a stronger
   emotional connection to shirts and shoes as they allow for individual expression, leading to higher purchase rates.**

* **Seasonal Demand: While jackets and gloves are typically seasonal items, shirts and shoes can be purchased year-round.
  This continual demand keeps sales consistent, unlike more seasonal items that may see spikes in specific months.**
  **research shows that clothing items like shirts often drive sales due to their fundamental role in the wardrobe and the desire for variety. 
**Footwear is similarly a critical component of personal style and function, influencing purchasing behavior significantly**

**From the above summarized table and chart we can boldly say that the southern region generated the highest total revenue for Sophiematis 
supermarket. The south region alone generated total revenue of #927,820 and total unit sold is 24298 and product sold are glooves, shoes, 
and socks. Follows by eastern region with a total revenue of #485,925 and total unit sold are 20,361. Items sold in the are hat, jacket, 
shirt and shoes. The western region recorded the lowest sales revenue with total of revenue of #300,345 with 11,400 unit sold.
item sold in the west are glooves, hat, shoes and socks** 
Southern region alone recorded 44.16% of the total revenue compared to the western region with 14.29% of total revenue

**In Nigeria, higher sales performance in the South,North,East,  and East for products like shirts, shoes, hats, jackets, gloves, and 
socks can be attributed to several factors:**

*. **Population Density and Urbanization:**
**The South and East of Nigeria include highly populated and urbanized regions such as Lagos, Port Harcourt, and Onitsha. 
These areas have larger consumer bases with increased purchasing power, resulting in higher sales for everyday items like shirts and shoes**.

**Lagos, for example, is a commercial hub with a high demand for fashion items due to the high number of residents and frequent events 
where people want to dress stylishly. The larger population in these areas leads to more consistent demand across various product categories.**

* **Economic Activities and Disposable Income**:
**The Southern and Eastern regions have strong economic activities, including oil, trade, and manufacturing industries,
particularly around Port Harcourt and Lagos. These industries contribute to higher average disposable incomes, allowing consumers**
**to spend more on apparel and fashion products**.
**As people in these regions often have more disposable income, they are more likely to purchase items beyond basic needs, including
trendy or high-quality clothing and accessories.**

* **Climate and Seasonal Demand**:

Nigeria has a generally warm climate, but the South and East experience relatively more rainfall. This drives demand for certain items like 
shoes and hats that can be used year-round, while demand for items like jackets might be more seasonal.
In contrast, the North tends to be hotter and drier, with less demand for items like jackets or gloves, which are less essential in that climate.
•	 Fashion Trends and Social Influence:
The Southern and Eastern regions, especially urban centers like Lagos, are known for their vibrant fashion scenes. Influencers, celebrities, and 
local trends drive higher demand for stylish clothing items.

**Lagos is known as a fashion and entertainment hub, leading to a higher demand for clothing that reflects current trends and fashion standards, 
including shirts and shoes which are worn daily**.

•	**Infrastructure and Retail Presence:**
**The South and East regions have more developed retail infrastructure, including shopping malls, boutiques, and e-commerce delivery services, making 
it easier for customers to access and purchase clothing items.**

**Better access to products and reliable supply chains encourages more frequent purchases compared to the West and North, where such infrastructure may 
be less developed.**

•	 **Cultural Factors:**

**Cultural celebrations in the South and East, such as traditional weddings and festivals, drive demand for new clothing items. 
These events often require participants to buy specific attire or follow certain fashion trends, creating consistent demand for products like shirts, shoes, and hats.
For example, events like Igbo weddings in the East often lead to higher sales of formal attire and accessories**.

**In summary, population density, economic strength, fashion trends, retail infrastructure, and cultural practices all contribute to the higher sales 
performance of clothing items in Nigeria's South and East compared to the West and North**. 


* **From the Monthly sales trend table and chart above it is seen that sales spike up in February from total revenue of #248,000 in January to total 
evenue of #546,300 amounting to 120% increase in sales.**
  
M**onth of February sales alone captured 26% of the total annual revenue while April sales revenue dropped to #46,865 signifying on 2.2% of total sales revenue.**

**For apparel items like shoes, shirts, gloves, hats, socks, and jackets, seasonal demand and spending patterns often drive fluctuations in sales. 
Here's why you might see high revenues in February and July and low revenues in November and December:**

#### February (High Sales):
*** Post-Holiday Sales: Many retailers run clearance and discount events to move leftover inventory from the holiday season, attracting bargain hunters**.
 
* **Seasonal Shift: Winter clothing, like jackets and gloves, might be in high demand due to cold weather. Additionally, new spring collections may be
  launching, sparking fresh interest**.
**Valentine’s Day: Apparel is often a popular gift choice for Valentine's Day, boosting sales of items like shirts, hats, and socks**.

  ##### July (High Sales):
  
* **Mid-Year Sales: Many stores hold "mid-year" or "summer clearance" sales to clear out summer inventory and make room for fall collections.**
* **Back-to-School Shopping: Some regions begin back-to-school shopping as early as July, which includes buying apparel.**

 * **Seasonal Apparel: Lighter clothing, like shirts and hats, often see a boost as people prepare for vacations, while early discounts on fall
   clothing can start to emerge.**

#### November and December (Low Sales):

* **Competition with Other Holiday Spending: During the holiday season, people often allocate more of their budget toward gifts, home decorations, and other
  holiday-specific expenses rather than apparel**.

* **Gifting Patterns: Apparel items like gloves, hats, and socks are sometimes less frequently given as gifts compared to electronics or toys.
Waiting for Post-Holiday Discounts: Some consumers might delay clothing purchases to take advantage of January clearance events, particularly
 for winter items like jackets.**

