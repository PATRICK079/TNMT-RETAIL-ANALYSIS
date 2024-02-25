# TNMT-RETAIL-ANALYSIS

![OK](https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/6fa4e185-2ce2-4235-bfd4-3516465fbe1f)

# INTRODUCTION

A company's sales report needs to be examined throughout time in order to determine its strengths and shortcomings if it is to continuously see increase in sales. The objective of this project was to use its major components to evaluate sales performance, trends, profitability, and total income generated by sales in 2020.

The business questions below also yielded insights.

• What is the top selling product and what product category drives the highest profit?

• How much profit was produced overall?

• Which channel is the best at selling?

• What was the total amount of money made?

• Which are the top stores in terms of profit margin?

• What was the amount of sales in the most successful month?

• Which month had the most sales and what was the quantity?

• Who generated the greatest revenue for the company in sales?

# Data Collection

The dataset used in this project was gotten from @learn.utiva.io as a capstone project.

This dataset, which includes over 19,000 transactions in the sales table, covers the period from January 1, 2022, to May 31, 2022, approximately five months. 

There were four XLSX-formatted tables in the dataset.

• The sales table included the following information: order number, sales date, channel, currency, team, store, product, order quantity, unit price, and unit cost.

• The Sales Team table included the following columns: region, sales team, and index. 

• The Products table had the names, categories, and unique product indexes for each product.

• The store location table included the following information: name, ID, county, state code, area code, latitude, longitude, household size, median income, land area, water area, and time zone.

# Tool Used

Analyses and visualizations on Ms Excel were conducted using Excel pivot.

# Data Preparation


The following actions were taken to prepare the data for analysis.

• Excel was used to import the four xlsx datasets.

• The imported dataset  were  converted into tables respectively  

• I started the data cleaning with the preliminary step of looking for duplicates in the 4 tables and no duplicate values was found in any of the tables

• Additionally, I ensured that the appropriate data type was used to represent each column. 




<img width="993" alt="Screen Shot 2024-02-25 at 19 49 59" src="https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/799f1cf9-f9a9-4efd-af66-fa2ac699700f">





• In order to assist me coin the profit column by deducting total cost from total price, I took the order quantity, unit cost, and unit price columns and minted the total cost and price columns from them. 




<img width="1165" alt="Screen Shot 2024-02-25 at 20 14 24" src="https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/279ab3f4-3d8e-4e79-b55a-92526aeacf26">


# Data  Model

<img width="743" alt="Screen Shot 2024-02-25 at 20 24 27" src="https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/d8173bf3-2c9a-4079-a180-391f6b460574">



# Insights and Findings

Based on the business questions posed earlier, conclusions and insights were acquired.

1. What is the top selling product and what  product category drives the highest profit?


<img width="798" alt="Screen Shot 2024-02-25 at 21 09 42" src="https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/6ed989c7-b1e6-4f60-bcf8-f13862df5400">



<img width="806" alt="Screen Shot 2024-02-25 at 21 13 57" src="https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/3a188a6f-dc4b-4c69-90c6-b5556ac9e413">

### insights/findings

 • With $1.10 million in sales, the accessory category's "clock" product stands out as the most lucrative item. This suggests that there is a significant market for clocks
 
 in the accessories sector, which may be influenced by functional requirements, design trends, or promotional tactics.
 
  • The decoratives category, with a $3.80 million overall profit, emerges as the primary profit generator. This implies that decoratives are not only a very profitable
  
  sector of products, but they are also popular. It might be the result of several things, including better margins, premium pricing, or effective cost control in this 
  
  particular category.

  • In the accessories category, the clock might lead in terms of sales, but decorative products drove higher total profitability due to a number of reasons, including          price strategies, market dynamics, production costs, profit margins, and seasonal trends.

  ### Recommendation

   • The clock is generating a lot of revenue, so there might be room to grow the product range or release new models to better satisfy customer demand. To accommodate a        wide range of preferences within the accessories market, this can entail providing a variety of designs, sizes, or functions.
     The decoratives sector makes a substantial profit contribution, which emphasizes how important it is to concentrate resources and efforts on this market. To sustain        and even improve profitability, the corporation might find it advantageous to devote more funds to product development, marketing, and distribution in the decoratives      area.


   2. How much profit was produced overall?

  The pivot table was used to calculate the overall profit.

 


<img width="293" alt="Screen Shot 2024-02-25 at 21 41 08" src="https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/0ec60a99-3ab8-43d2-88cf-ab180fef2d05">


### insights/findings

  The company's impressive $12.7 million profit above sales shows that it is successfully maximizing profitability across all of its product categories. This indicates effective cost, pricing, and general business operations management.


  3. Which channel is the best at selling?


<img width="330" alt="Screen Shot 2024-02-25 at 21 53 29" src="https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/2198dbe7-2287-47ab-b786-ea7758fca688">

### insights/findings

Online sales  channel seems to be the best in sales.

With sales ranging from $10.96 million to $11.25 million, the sales data across the four channels—online, distributor, wholesale, and in-store—shows a reasonably balanced 

performance. This shows that the business has successfully diversified its sales channels to target various market and customer categories.

  ### Recommendation

   Having the largest sales volume of $11.25 million, the online channel is prominent. 
   
   This shows how important internet retailing and e-commerce are becoming to the  company's sales strategy. The web channel's impressive performance can be an indication 
   
   of consumers' growing inclination toward online buying due to its accessibility, convenience, and ease. The business may improve its online image, get more users to the 
   
   website, and eventually increase revenues through the online channel. Track key performance indicators (KPIs) like average order value, conversion rates, and website         
   traffic on a regular basis to assess these initiatives' efficacy and make data-driven modifications as necessary.


4. What was the total amount of money made?

   
<img width="247" alt="Screen Shot 2024-02-25 at 22 09 52" src="https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/c3ec06f4-4505-433b-b8f7-2c6f280287b1">

   ### insights/findings

   The $44.4 million in total revenue offers a thorough overview of the business's financial performance during the given period of time.
   
One important performance metric for evaluating the success of the business's sales and marketing initiatives is total revenue.

Through the process of cross-referencing present sales figures with past records or industry standards, the business can assess its growth trajectory and pinpoint 

opportunities for enhancement.

5. • What was the amount of sales in the most successful month?

<img width="1033" alt="Screen Shot 2024-02-25 at 22 17 20" src="https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/3b7a3366-06dd-40c7-9cb2-061c5069755d">

### insights/findings

  With $9.2 million in sales, May stands out as the month with the highest sales throughout the five-month timeframe provided. Sales for the other months, such as April 
  
  ($8.6 million), March ($8.9 million), February ($8.6 million), and January ($9.1 million), are less than this.

6. Who generated the greatest revenue for the company in sales?

   
 <img width="626" alt="Screen Shot 2024-02-25 at 22 31 51" src="https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/edc27f36-f098-4dc4-9439-85c2b2161ed6">

    
### insights/findings

With $1,856.2 million in sales, Nicholas Cunningham achieved the highest amount.


# VISUALIZATION

<img width="1389" alt="Screen Shot 2024-02-25 at 18 23 01" src="https://github.com/PATRICK079/TNMT-RETAIL-ANALYSIS/assets/157173680/ba7ceafe-03e1-4512-9190-1deb2ac0d48e">


  Interract with my dashboard here https://1drv.ms/x/s!Ar7Ar6ZEDjjugTBDSD2P8Mu7WNTi?e=0Wpjqa
