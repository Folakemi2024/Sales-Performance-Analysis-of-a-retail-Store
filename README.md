# REPORT OF SALES PERFORMANCE OF A RETAIL STORE AND CUSTOMER SEGMENTATION FOR A SUBSCRIPTION SERVICE DATA ANALYSIS

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Table of Content

- An Overview of the Retail Store and Subscription Service

- Tools Used

- Steps in Data Cleaning

- Data Analysis Process

- Report Analysis

- Key Insights

- Recommendations
---------------------------------------------------------------------------------------------------------------------------------------------------------------------

## An Overview of Retail Store and Subscription Service

The Retail Store, a fashion retailer, offers a diverse selection of accessories such as shirts, gloves, hats, shoes, and jackets throughout Nigeria's western, southern, eastern, and northern regions. This report examines the sales performance of Fashion Retail Store in these areas over 2023 and 2024, uncovering insights on top-selling items, regional sales patterns, and monthly sales fluctuations. The analysis utilizes Microsoft Excel, SQL, and PowerBI to reveal trends and evaluate regional success.
For the subscription service, customers pay on a recurring basis monthly or annually for ongoing access to a particular product, service, or platform. This model provides ease of use, builds customer loyalty, and ensures steady revenue, making it advantageous for both consumers and providers. This analysis dives into customer data for a subscription service, aiming to identify customer segments and emerging trends. Using tools like Microsoft Excel, SQL, and PowerBI, it delivers insights into customer behavior, tracks various subscription plans, and highlights notable patterns in cancellations and renewals.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Tools Used

- Microsoft Excel

- SQL

- PowerBI
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Data Source

- The data is gotten from LITA Capstone dataset

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Data Structure

### Sales Performance of Retail Store Data Structure

- Order Id

- Customer Id

- Product

- Region

- Order Date

- Order Month

- Quantity

- Unit Price

- Total Sales

 ---------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Customer Segmentation for a Subscription Service Data Structure

- Customer ID

- Customer Name
  
- Region
 
- Subscription Type
 
- Subscription Start
  
- Subscription End
  
- Subscription Duration

- Cancelled

- Revenue

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Steps in Data Cleaning

- Check for null and duplicate values and remove duplicates

- Standardized data formats for numbers and text
  
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Process of Data Analysis 

### Microsoft Data Analysis

i. Highlight the Sales performance retail data and click Insert Pivot Table

ii. Click "From Table/Range"

iii. Click Existing worksheet, then click okay

iv. Same process applies to Customer Segmentation for a Subscription Service Data

### PowerBI

i. Click on Get data to upload the data from Microsoft Excel

ii. After uploading the data, tick Sales and Customer data and click tranform data 

iii. From the power query editor, click on the view then tick column quality to check the data quality

iv. Change the order date to date format

v. Create a new column and name it Order month

vi. To change the date 31/01/2023 to month, use DAX formula MonthName = FORMAT(SalesData[OrderDate], "MMMM") 

vii. The visualisation is done from the report view

### SQL

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Pivot Chart Analysis of Sales Performance Of Retail Store


<img width="375" alt="Total Sales by region" src="https://github.com/user-attachments/assets/ec3876f2-bcb6-4896-8225-b746aefde36b">

- The bar chart shows total sales across four regions, with the South leading at nearly 5 million, followed by the East, North, and West. The South’s strong performance indicates it may have higher demand or more effective sales strategies compared to other regions. 


<img width="345" alt="Total Revenue by Month" src="https://github.com/user-attachments/assets/7c3f78f1-3140-4297-ba0b-9c906172b7d1">

- The line chart shows monthly revenue trends, with a peak in February near 3 million, followed by a sharp drop in March and relatively lower fluctuations for the rest of the year. The data suggests strong revenue early in the year, with a more stable but lower revenue pattern across subsequent months.


<img width="371" alt="Total Sales for year 2023 and 2024" src="https://github.com/user-attachments/assets/503b1df0-2426-4dcf-9aec-3ed3d8a06f21">

- The bar chart displays total sales for 2023 and 2024, with 2023 reaching about 5.5 million and 2024 lowering to roughly 5 million. This indicates a noticeable drop in sales from 2023 to 2024.


<img width="371" alt="Average Sales by Products" src="https://github.com/user-attachments/assets/77d78f4a-2a55-4740-9dc9-a41cd1c6ebec">

- The chart shows the average sales of different clothing products. Shoes have the highest average sales with 326.7 units, followed by Shirts with 308.8 units.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Pivot Chart Analysis of Customer Segmentation for a Subscription Service

<img width="358" alt="Average Revenue by Subscription" src="https://github.com/user-attachments/assets/3ab62fa1-79b7-4752-afce-3cb374a0cd33">

- The chart shows the average revenue generated by different subscription. The Premium suscription generates the highest revenue, followed by the Standard suscription, and lastly, the Basic suscription.
  

<img width="373" alt="Region Revenue by Subscription" src="https://github.com/user-attachments/assets/b590d1da-4c15-434c-8460-f3a7c8da81b9">

- The chart shows the revenue generated by different subscription tiers across four regions: East, North, South, and West. The East region generates the highest revenue for all three tiers, followed by the West, South, and North regions. The Basic tier consistently generates the most revenue across all regions.
  

<img width="379" alt="Revenue by Subscription" src="https://github.com/user-attachments/assets/57ed72e2-608d-449f-b1f7-3c70b061ad2d">

- The chart shows the revenue generated from different subscription suscribers. The Basic subscription generates the highest revenue, followed by the Standard and Premium subscription.


<img width="364" alt="Average month subscription" src="https://github.com/user-attachments/assets/cd300968-a9ee-4196-88ca-6e31633b206a">

- The pie chart shows the average subscription month duration for different subscription types. All three subscription types, Basic, Premium, and Standard, have an average subscription month duration of 12 months.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Visualization on PowerBI

<img width="479" alt="POWER BI Visualization" src="https://github.com/user-attachments/assets/dc3bebf0-f736-45c2-a72e-7ed553267c45">


### Total Sales by Region: 

This bar chart displays the total sales for each region. It appears that the South region has the highest sales, followed by the East, North, and West regions.


## Sum of Quantity by Product: 

This pie chart shows the distribution of quantities sold for different products. Shoes seem to be the most popular product, followed by shirts, hats, and so on.


## Total Sales by Product:

This bar chart displays the total sales for each product. Shoes again appear to be the top-selling product, followed by shirts, hats, and other items.


## Total Sales by Month: 

This line chart shows how total sales have fluctuated over the months. There seems to be a peak in April and then a decline towards the end of the year.


## Number of Transactions by Region: 

This bar chart displays the number of transactions for each region. The East region has the highest number of transactions, followed by the North, South, and West regions.


## Total Revenue by Subscription Type:

This bar chart shows the total revenue generated by different subscription types. The Basic subscription type appears to generate the highest revenue, followed by Standard and Premium.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Key Insights

The data highlights notable variations in sales and revenue across different regions and seasons. The South region emerges as the top performer with the highest sales, likely driven by favorable market conditions or effective sales strategies, while the West records the lowest sales, underscoring significant disparities in regional performance. In addition, monthly revenue trends reveal a peak in February, which could be attributed to seasonal factors or targeted promotions, followed by a sharp decline and relatively steady but lower revenue levels for the remainder of the year. This trend indicates that demand is concentrated early in the year, with limited growth observed in the subsequent months.

Furthermore, year-over-year analysis shows a decline in total sales from approximately 5.5 million in 2023 to 5 million in 2024, which may be influenced by economic shifts, evolving consumer preferences, or other market dynamics. This persistent downturn in both monthly and annual sales underscores the need for targeted strategies to stabilize revenue, such as prioritizing underperforming regions like the West and identifying opportunities for growth during slower months. Overall, these insights highlight the necessity for strategic adjustments to sustain and improve sales performance across various regions and throughout the year.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Recommendations

Drawing from the data insights, the following recommendations are proposed to improve sales outcomes and achieve stable revenue:

- Increase Sales in Regions with Lower Performance: Direct attention to the West and North regions by deploying focused marketing efforts, establishing local partnerships, and offering products tailored to these markets. Understanding the unique needs of customers in these areas can help boost engagement and drive growth.

- Leverage Seasonal Revenue Peaks: Make the most of high-demand periods, such as February, by launching timely promotional events, exclusive offers, or new product releases. Analyzing what drives February's peak can help in creating similar successes during other times of the year.

- Address Annual Sales Decline: Explore the factors behind the sales reduction from 2023 to 2024, including possible shifts in customer preferences or economic influences. Adjusting pricing strategies, broadening the product range, or enhancing customer relations may help counteract this downward trend.

- Expand Marketing Throughout the Year: To maintain consistent revenue, consider organizing regular promotions, loyalty initiatives, or discounts during slower periods later in the year. Continuous customer engagement can foster loyalty and smooth out revenue fluctuations.

- Apply Data Analytics for Targeted Strategies: Use data analytics to gain deeper insights into customer behavior, seasonal trends, and regional sales dynamics. Data-driven decision-making will improve forecasting, allow for more targeted marketing, and enhance resource allocation, leading to stronger performance overall.

By implementing these strategies, the company can strengthen its presence in key regions, optimize peak seasons, and maintain a balanced revenue stream year-round.
