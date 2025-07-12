# Tseke_capstone-DSA
My first project on SQL while taking my data analysis course with The Incubator Hub

## Project Topic- KMS Business Intelligence Analysis (2009-2012)
### Project Overview
The primary objective for this project is to assess customer behavior, product performance, shipping efficiency and profitability across regions, segments and categories using SQL-driven analytics. In this analysis, I am expected to
-  Identify top-performing products, customers, and regions.
-  Track down cost inefficiencies
-  Highlight underperforming segments
-  Recommend data approved strategies for revenue growth
### Data Source
Order Data (CSV File) which contains transactional records from 2009-2012, including:
- Order date, quantity, Sales, profit, shipping cost, shipping mode
- Customer details: name, segment, region, province
- Product details: category, sub-category, container.
Order Status Data (CSV File)	
This file contains data which includes returned order IDs and status information.
### Tools Used
-	MS Excel  [Download Here]
- For data cleaning
- 	For data collection
- 		SQL server
  ``` SQL
  SELECT A,B,C
  WHERE A>15
  ```
-	For querying
-	For conducting analysis
### Data Preparation
The file gotten from excel which contained the data from 2009-2012 required little to no cleaning. I started by creating a database on SQL for the project then continued with the following prompt
- Importation of data from ms excel into SQL
-	Create Table in SQL
-	Validate date
-	Execute as needed
  # Data Analysis
## Product With the Highest Category


#### Insight: Technology had the highest total sales of –between 2009-2012
#### Interpretation: Technology contributes largely to the revenue and may indicate higher demand and pricing in that category
## TOP 3 and Bottom 3 Regions In Terms of Sales


#### Insight: shows that west, Ontario and praprie were top 3 while Nunavut, northwest territory &Yukon appear bottom 3 with the least sales
#### Interpretation
Less urbanized regions may have limited customer base or are faced with logistical challenges.
#### Recommendation
Focus on improving marketing and delivery optimization in the bottom regions or consider collaborations with local vendors to increase accessibility.
## Total Sales of Appliances in Ontario


#### Interpretation: 
There has been no significant demand for appliances in Ontario, possibly due to consumer behavior.
#### Recommendation: 
Run a promotion and discount deals in that region specifically to increase conversion rate.
 ## Increase Revenue from Bottom 10 Customers


#### Interpretation: 
This may be due to low product relevance or poor service experience
#### Recommendation: 
Analyze past consumer behavior to recommend relevant products and improve customer support.

## Most Costly Shipping Method


#### Interpretation:
 These customers likely operate in office –heavy businesses with recurring demands
#### Recommendation:
 Introduce loyalty package exclusive deals for high-value customers and focus on their preferred products.

## Top Small Business Customer by Sales


#### Insight:
 Sales are most likely generated in technology products purchased
#### Interpretation
  It indicates that small business can grow and perform well in building tech infrastructure. The development of tech bundles and inclusivity of educational content to attract similar small scale business clients.

## Corporate Customer With Most Orders (2009-2012)


#### Insight:
 Adam hant placed the most orders in this period among all corporate customer
#### Interpretation: 
For frequent ordering, the need for consistent stock should be made available.
#### Recommendation
 Consider contact based sales for frequent buyers.

## Most Profitable Consumer Customer


#### Interpretation: 
Profitable consumers can venture into from home based businesses 
#### Recommendation
 Implore the use of demographic analysis to identify similar consumer segment and target them with curated offers

## Customers Who Returned Items & Their Segments


#### Insight
 8 customers returned items; 3 are in consumer, 3 in small business, 1 in corporate and 1 in home office.
#### Interpretation
Consumers return of items more frequently may be due to unmet expectations or unclear product details.
#### Recommendation
 Improve on the product description, images and make adjustment on return policies
## Appropriateness of shipping cost 



