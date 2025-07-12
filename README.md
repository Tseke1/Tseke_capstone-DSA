[kms query 5 (shiiping mode).csv](https://github.com/user-attachments/files/21195507/kms.query.5.shiiping.mode.csv)[kms query 6.1 (Product to Buy).csv](https://github.com/user-attachments/files/21195400/kms.query.6.1.Product.to.Buy.csv)[kms query 6 (MOST VALUABLE).csv](https://github.com/user-attachments/files/21195397/kms.query.6.MOST.VALUABLE.csv)[kms query 8 (corporate customer).csv](https://github.com/user-attachments/files/21195367/kms.query.8.corporate.customer.csv)[kms query 7 (small business).csv](https://github.com/user-attachments/files/21195359/kms.query.7.small.business.csv)[kms query 9 (consumer customer).csv](https://github.com/user-attachments/files/21195318/kms.query.9.consumer.customer.csv)[kms query 11.2.csv](https://github.com/user-attachments/files/21195307/kms.query.11.2.csv)[kms query 11.1.csv](https://github.com/user-attachments/files/21195306/kms.query.11.1.csv)[kms query 11.0.csv](https://github.com/user-attachments/files/21195305/kms.query.11.0.csv)[kms query 7 (small business).csv](https://github.com/user-attachments/files/21195291/kms.query.7.small.business.csv)[kms query 6.1 (Product to Buy).csv](https://github.com/user-attachments/files/21195279/kms.query.6.1.Product.to.Buy.csv)[kms query 5 (shiiping mode).csv](https://github.com/user-attachments/files/21195272/kms.query.5.shiiping.mode.csv)[kms query 4 (Advice).csv](https://github.com/user-attachments/files/21195259/kms.query.4.Advice.csv)[kms query 3 (appliance sales).csv](https://github.com/user-attachments/files/21195258/kms.query.3.appliance.sales.csv)[kms query 2.1 (bottom 3) N.NT.Y.csv](https://github.com/user-attachments/files/21195249/kms.query.2.1.bottom.3.N.NT.Y.csv)[kms query 2.0 (top 3) W.O.P.csv](https://github.com/user-attachments/files/21195247/kms.query.2.0.top.3.W.O.P.csv)[kms query 1 (technology).csv](https://github.com/user-attachments/files/21195203/kms.query.1.technology.csv)# Tseke_capstone-DSA
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
-	MS Excel 
- For data cleaning
- For data collection
- SQL server
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
[UploadiTechnology,5984248.18199998
ng kms query 1 (technology).csv…]()
#### Insight: Technology had the highest total sales of –between 2009-2012
#### Interpretation: Technology contributes largely to the revenue and may indicate higher demand and pricing in that category
## TOP 3 and Bottom 3 Regions In Terms of Sales
[Uploading kms query 2.0 Region	Total Sales
West	3597549.276
Ontario	3063212.48
Prarie	2837304.601
(top 3) W.O.P.csv…]()
[UploadREGION	Total sales
Nunavut	116376.4835
Northwest Territories	800847.3295
Yukon	975867.371
ing kms query 2.1 (bottom 3) N.NT.Y.csv…]()
#### Insight: shows that west, Ontario and praprie were top 3 while Nunavut, northwest territory &Yukon appear bottom 3 with the least sales
#### Interpretation
Less urbanized regions may have limited customer base or are faced with logistical challenges.
#### Recommendation
Focus on improving marketing and delivery optimization in the bottom regions or consider collaborations with local vendors to increase accessibility.
## Total Sales of Appliances in Ontario
[Uploading kmNULL
s query 3 (appliance sales).csv…]()
#### Interpretation: 
There has been no significant demand for appliances in Ontario, possibly due to consumer behavior.
#### Recommendation: 
Run a promotion and discount deals in that region specifically to increase conversion rate.
 ## Increase Revenue from Bottom 10 Customers
[UploadinJeremy Farry,85.72
Natalie DeCherney,125.9
Nicole Fjeld,153.03
Katrina Edelman,180.76
Dorothy Dickinson,198.08
Christine Kargatis,293.22
Eric Murdock,343.328
Chris McAfee,350.18
Rick Huthwaite,415.82
Mark Hamilton,450.99
g kms query 4 (Advice).csv…]()
#### Interpretation: 
This may be due to low product relevance or poor service experience
#### Recommendation: 
Analyze past consumer behavior to recommend relevant products and improve customer support.
## Most Costly Shipping Method
[UploDelivery Truck,51971.9399999998
ading kms query 5 (shiiping mode).csv…]()
#### Insight
Delivery truck incurred the highest shipping cost.
#### Interpretation
Though they have faster average shipping dates, the shipping cost may cause a reduction in the profit margins, especially if used for low order-priority.
## Most Valuable Customers & Their Preferences
[Uploading kmEmily Phan,117124.438
Deborah Brumfield,97433.1355
Roy Skaria,92542.153
Sylvia Foulston,88875.7575
Grant Carroll,88417.0025
s query 6 (MOST VALUABLE).csv…]()
[Uploading kms Deborah Brumfield,4
Emily Phan,1
Grant Carroll,5
Roy Skaria,8
Deborah Brumfield,8
Emily Phan,5
Grant Carroll,15
Roy Skaria,12
Deborah Brumfield,8
Emily Phan,4
Grant Carroll,7
Roy Skaria,6
query 6.1 (Product to Buy).csv…]()
#### Interpretation:
 These customers likely operate in office –heavy businesses with recurring demands
#### Recommendation:
 Introduce loyalty package exclusive deals for high-value customers and focus on their preferred products.
## Top Small Business Customer by Sales
[UploadiDennis Kane,75967.5905
ng kms query 7 (small business).csv…]()
#### Insight:
 Sales are most likely generated in technology products purchased
#### Interpretation
  It indicates that small business can grow and perform well in building tech infrastructure. The development of tech bundles and inclusivity of educational content to attract similar small scale business clients.
## Corporate Customer With Most Orders (2009-2012)
[UplAdam Hart,27
oading kms query 8 (corporate customer).csv…]()
#### Insight:
 Adam hant placed the most orders in this period among all corporate customer
#### Interpretation: 
For frequent ordering, the need for consistent stock should be made available.
#### Recommendation
 Consider contact based sales for frequent buyers.
## Most Profitable Consumer Customer
[UplEmily Phan,34005.44
oading kms query 9 (consumer customer).csv…]()
#### Interpretation: 
Profitable consumers can venture into from home based businesses 
#### Recommendation
 Implore the use of demographic analysis to identify similar consumer segment and target them with curated offers
## Customers Who Returned Items & Their Segments
[Uploading kms query 10 (returned customers).csv…]()
#### Insight
 8 customers returned items; 3 are in consumer, 3 in small business, 1 in corporate and 1 in home office.
#### Interpretation
Consumers return of items more frequently may be due to unmet expectations or unclear product details.
#### Recommendation
 Improve on the product description, images and make adjustment on return policies
## Appropriateness of shipping cost 
[Uploading kmsDelivery Truck,51971.9399999998
Regular Air,48008.1899999998
Express Air,7850.90999999996
 query 11.0.csv…]()
[Uploading kmCritical,Express Air,200,8.7105
Critical,Delivery Truck,228,47.2974561403509
Critical,Regular Air,1180,7.27691525423726
High,Express Air,212,6.85627358490567
High,Delivery Truck,248,45.1890322580646
High,Regular Air,1308,7.64909021406723
Low,Express Air,190,8.16647368421053
Low,Delivery Truck,250,44.52644
Low,Regular Air,1280,8.01845312499995
Medium,Express Air,201,8.12731343283582
Medium,Delivery Truck,205,46.154243902439
Medium,Regular Air,1225,7.68875102040812
Not Specified,Express Air,180,8.167
Not Specified,Delivery Truck,215,43.6651627906977
Not Specified,Regular Air,1277,7.62261550509002
s query 11.1.csv…]()
[UploadinExpress Air,Low,4
Regular Air,Low,4
Delivery Truck,Low,3
Delivery Truck,Critical,1
Delivery Truck,High,1
Delivery Truck,Medium,1
Delivery Truck,Not Specified,1
Express Air,Critical,1
Express Air,High,1
Express Air,Medium,1
Express Air,Not Specified,1
Regular Air,Critical,1
Regular Air,High,1
Regular Air,Medium,1
Regular Air,Not Specified,1
g kms query 11.2.csv…]()
#### Insight
The order priority for delivery truck is considerably critical even though it is seen clealy in the analysis that regular air has the highest total orders. 
#### Interpretation
There are misalignment between urgency and shipping method. while regular air has the highest total orders, the days average shipping days are misaligned. Hence, the increases overheads without matching the business need.
#### Recommendation
Enforce order-priority on shipping rules to management system while encouraging low order-priority customers to opt for economical shipping mode with incentives like discounts. For high order-priority among small and large business customers, use appropriate shipping method to order priority more strictly

