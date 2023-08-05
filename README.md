# Walmart-Sales-Analysis

**----Introduction----**

Walmart is an American multinational retail corporation that operates a chain of hypermarkets (also called supercenters), discount department stores, and grocery stores in the United States, headquartered in Bentonville, Arkansas. The company was founded by brothers Sam and James "Bud" Walton in nearby Rogers, Arkansas in 1962 and incorporated under Delaware General Corporation Law on October 31, 1969. It also owns and operates Sam's Club retail warehouses.

**----Project Description----**

Downloaded the hotel data from the Kaggle. The data cleaning and visualization is done in PowerBi using Power Query. Analysed the Sales of 
Walmart from 2011 to 2014. Created a Dashboard and provided insights and solutions for those insights.

**----Data Description----**

**a) Excel_data -** This folder contains the Walmart_Data.csv file which is the main raw data downloaded from Kaggle website.

**b) Python File -** This folder contains the ipynb file for Data Cleaning.

**c) Powerbi Excel Dashboard -** This folder contains the Dashboard which is done in Powerbi as well in Excel.

**d) Insights & Improvements -** This folder contains the Insights got from the Dashboard like why the sales become quite less and the Improvements thats can increase the sales in the next few years.

**e) SQL File -**  This folder contains the SQL Queries to clean the Database and make Database Schema.


**----Overview----**

**1) Downloaded the Walmart data from the Kaggle :-** The Sample data looks like this.
   
![Screenshot 2023-08-05 024802](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/70bab083-a58f-4687-9120-dee6e5a3bf77)

**2) Cleaning the Data :-**
Used Numpy as Pandas for cleaning the data.

**a) Import necessary modules and packages-** 

![cleaning_1](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/c07745ed-b8c7-4c80-803b-9ff43e0f813d)

**b) Dealing with the noise and null values-**

![cleaning_2](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/83d4a81e-d3d1-4bc7-ad63-1453020554e8)

**c) Ordering the Date column and changind the Datatypes-**

![cleaning_3](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/f6a62319-4a0c-48f6-b9e1-717e75808ba4)

**d) Creating the OrderId column for visualition purpose and storing the data into a csv file-**

![cleaning_4](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/082f7aae-beba-4952-9244-89ac2e7ddd6f)


**3) Making the Schema of the Database and Normalize the Data :**

**a) Customer Table :**
 
![customer](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/bcf5a88f-649a-4cad-bbda-df415014df5e)

 **b) Shippers Table:**
 
![shippers](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/c8306407-8d02-4cc5-bb7b-9b222bc5b586)

 **c) Orders Table:**
 
![Orders](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/c40fd807-a5fd-43ad-97e6-3a2624e751b1)

**d) OrderDetails Table:**
 
![orderdetails](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/ce48b41f-3d06-4e39-acda-fb415ac72899)

 **e) Products Table:**
 
![products](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/34245bf3-24e2-48ae-bef0-dc3a91e46c36)

 **f) Full Table:**
 
 ![fu;ll table](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/046887ff-8378-420b-aaef-d903712d11fc)


**2) Creation of Dashboard in Powerbi based on the Data.**

**a) Products_Dashboard -** It includes various charts, graphs, tables, and other visualizations that provide a comprehensive view of product-related data. This dashboard can be tailored to suit the specific needs of the business and can help us monitor and analyze product performance, sales, inventory, customer feedback, and other important metrics.

![Screenshot 2023-08-05 025318](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/669e6f44-8da4-41d3-befb-08899fa47954)

**b) Customers_Orders Dashboard -** It contains all the Customers and Orders relatied informations. It is for the analysis of Order Summary, Order Trend, Top Customers, Order Geography and Order during the previous years.

![Screenshot 2023-08-05 025337](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/eea86184-4fb5-472f-b31c-af87f1968f71)

**3) Insights and Improvements provided based on the Dashboard.**

![insights_7](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/55aa43b9-0fcf-478d-8b1c-4ac73f46b1f4)
![insights_8](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/31aaff01-af50-4640-aab7-e4501634634c)

**a) The total Revenue is 3.54 M and the profit is 152 k.**

**b) The highest number of products were sold in the State Claifornia.**

**c) The Sales and Profit goes on increasing year by year. So we can say that the company is in a good state.**

![insights_6](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/a753a54b-708d-40e9-b00a-f8147d6f5b44)

**d) Overall Consumer Segment has more number of Products Sold.**

![insights_5](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/555ce06e-3f72-4c6e-b04f-5436415adf2b)

**e) Very less people are buying Office Supplies Subcategory Products.**

![insights_4](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/2f279c5a-aba7-4ed3-ba2a-63d71651b3a7)

**f) In the month of May and June in 2014 the Aquisition of Customers were very less compared to other years.**

![insights_3](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/2e8fde07-b352-4146-b595-ee62c3d406f7)

**g) Very less orders were ordered in the Same Day.**

**h) So the average delivery time for the Orders are 57 days approx. So we should look into the delivery agents.**

**i) Montona State has ordered least number of products.**

**j) Currently the company is in a good state but the Sales can do down in any Month because the graph of Sales for Years is not stable.**

**k) Total Products Ordered - 1504**

**l) In the Month of Jan in 2014 the Sales and Profit was good but recently it came down.**

![insights_1](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/d8a974c1-359f-4e35-8c97-8bf58c682ef3)

![insights_2](https://github.com/tuneerdutta/Walmart-Sales-Analysis/assets/131517578/0e5a3810-1d7b-40fe-8cc1-c2f12c06813d)


**----Improvements----**

1) As the delivery time taken is much more for the products to be delivered. So we should consult with the delivery agents and ask about this mishap.

2) There are some customers who are hardly buying products. So we need to go to them or give some offeres to only those customers.

3) We should look to the quality or return rate of the products in Nevada State because it the least ordering State.

4) We should study the customer feedback and the reviews in our online platform.

5) Prices of the least selling products should be given some discount.



**----Challenges Faced----**

**1) Data Cleaning -** I phased the major problem in the data cleaning part with Power Query. Because the data was too uncleaned when it was donloaded.

**2) Insights and Improvements -** To study the insights deeply and visualize the charts and suggest good Improvements.

**3) Sentiment Analysis -** Analyzing Customer reviews and feedback to gauge sentiment and identify areas for improvement became challenging, especially with the varying nature of products and orders and places.

