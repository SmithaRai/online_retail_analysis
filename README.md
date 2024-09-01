# online_retail_analysis

## **problem statement**
The project provides a  dataset focused on retail transactional data. As the main data analyst , you will analyze sales and customer experience  and create insightful dashboards to inform business stakeholders about potential problems and propose structural business improvements.

## **Outcomes**
The first objective analyzing which products are bestsellers and which ones have low sales.
To understand customer satisfaction and their engagement in purchases.
to understand the characteristics and behaviors of customer base.

## **Questions to ask**
Identify the top 20% of products responsible from which  80% of the revenue is generated using ABC analysis.
To identify top selling product category and product brand
To identify the active customers age group
To understand correlation between total revenue and rating by the customer
To understand sales behavior over time

## **Dataset Description**
#### 1.**Transaction_ID** : Unique identifier for each row.
#### 2.**Age** : Age of the customer
#### 3.**Gender** : Gender of the customer
#### 4.**Income** : Income level of the customer
#### 5.**Customer_Segment** : Segment of the customer (e.g., Premium, Regular, New)
#### 6.**Date** : Date component extracted from the last purchase date
#### 7.**Year** : Year component extracted from the last purchase date
#### 8.**month** : Date component extracted from the last purchase date
#### 9.**Time** : Time component extracted from the last purchase date
#### 10.**Amount** : Amount spent in a single transaction
#### 11.**Total_Purchase_Amount** : Total amount spent by the customer (calculated as Amount * Total_Purchases)
#### 12.**Product_Category** : Category of the purchased product
#### 13.**Product_Brand** : Brand of the purchased product
#### 14.**Feedback** : Feedback provided by the customer on the purchase
#### 15.**Shipping_Method** : Method used for shipping the product
#### 16.**Payment_Method** : Method used for payment
#### 17.**Order_Status** : Status of the order (e.g., Pending, Processing, Shipped, Delivered)
#### 18.**products** : list of different products
#### 19.**Ratings** : ratings given by customers on different products

### **Dataset Overview : Key Statistics and Shape**
  **Missing Values** :
#####        **Transaction_ID**     : 333
#####        **Age**                : 173
#####        **Gender**             : 317
#####        **Income**             : 290
#####        **Customer_Segment**   : 215
#####        **Date**               : 359
#####        **Year**               : 350
#####        **Time**               : 350
#####        **Total_Purchases**    : 361
#####        **Amount**             : 357
#####        **Total_Amount**       : 350
#####        **Product_Category**   : 283
#####        **Product_Brand**      : 281
#####        **Feedback**           : 184
#####        **Shipping_Method**    : 337
#####        **Payment_Method**     : 297
#####        **Order_Status**       : 235
#####        **Ratings**            : 184
#####        **products**           :   0
        
  **Complete Data** : 302010 rows,19 columns

## **Analysis insights**

### **Sales Analysis**

**Top selling product categories**: Electronics and grocery products are the top revenue contributors, accounting for 24% and 22% respectively, while other categories make up 18%. 
**Top selling product Brands**: Pepsi is the top seller, representing 24% of the total revenue, while BlueStar is the least, contributing just 2%
**Sales Over Time**: Sales were high in April and August 2023, followed by a decline from September 2023 to February 2024

### **Customer Analysis**

**Customer Type Breakdown**: Regular customers generate the highest revenue, accounting for approximately 49%, while new customers contribute 30% and premium customers account for 21% of the revenue.
**Customer Satisfaction levels**: The customer feedback data reveals that a significant portion of purchases are met with positive experiences, as evidenced by the 33.36% of customers rating their purchase as "Excellent" and 31.54% rating it as "Good."

### **Demographic Analysis**
                         
**Income breakdown**: Customers with a decent income, representing the middle class, contribute the most to revenue, accounting for 43%. This is followed by low-income customers at 32%, and high-income customers at 25%.
**Payment breakdown**: Credit cards lead as the preferred payment method, followed closely by debit cards and cash.

## **recommendations**

1.Due to data limitations, the root cause of underperforming product categories and declining sales remains unclear. However, analyzing inventory and logistics data could help identify the underlying issues.
2.Since credit cards are favored by most of the customer base, offering EMI options on high-priced products and providing cashback incentives could enhance customer satisfaction.
3.For regular customers, implementing loyalty programs could further increase engagement and retention.
4.Although electronic brands currently generate lower revenue, they receive positive customer feedback. Therefore, maintaining adequate stock levels, ensuring product quality, expanding the product range, and optimizing logistics could significantly boost revenue.

## **Conclusion**

The analysis of online retail sales data has provided valuable insights into customer behavior, product performance and customer satisfaction. 

