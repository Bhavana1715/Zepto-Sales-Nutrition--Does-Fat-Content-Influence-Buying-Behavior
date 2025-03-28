# Zepto Sales Analysis: Does Fat Content Influence Buying Behaviour?

## 💠**Project Overview**

+ Zepto, a fast-growing 10-minute grocery delivery service, has revolutionized the quick-commerce industry with its hyper-efficient supply chain and micro-fulfillment centers.

+ Over the past few years, Zepto has rapidly expanded its presence in major Indian cities, capturing a significant share of the instant grocery delivery market.

+ As part of its growth strategy, Zepto aims to optimize product offerings by analyzing consumer preferences based on various product attributes, including fat content in food products.


+ The goal is to provide actionable recommendations that enhance product selection, pricing strategies, and marketing efforts for different fat-content categories, ultimately boosting overall sales and customer retention.

## 💠Data Source/DataSet
➽ The dataset is sourced from Kaggle.

➽ It contains the following columns:

* Item Identifier – Unique ID for each product.

* Item Fat Content – The fat content category of the product (e.g., Low Fat, Regular).

* Item Type – The category/type of the product (e.g., Dairy, Snacks, Beverages).

* Item Visibility – The percentage of total display area allocated to the product in stores.

* Item Weight – The weight of the product.

* Outlet Identifier – Unique ID for each store.

* Outlet Establishment Year – The year when the store was established.

* Outlet Location Type – The type of city where the store is located (e.g., Tier 1, Tier 2, Tier 3).

* Outlet Size – The size of the store (e.g., Small, Medium, High).

* Outlet Type – The category of the store (e.g., Supermarket Type1, Grocery Store).

* Sales – The total sales of the product.

* Rating  – Customer rating for the product .
## 💠Tools

**Pandas**,**Numpy** - Data Cleaning & Transformation

𝐏𝐨𝐰𝐞𝐫 𝐁𝐈 - Power Query, Data, DAX and measures, Data Visualization, Dashboard creation

Github- For Documnetation







https://github.com/user-attachments/assets/e4fdcb2f-a7d2-4b3c-a0b3-117b421f1e1a



## ✨ Key Insights and Findings
###   Key Performance Indicators 

  + **Total Sales**: Remains steady at $1M, signifying overall revenue performance.

  + **Average Sales**: Currently at $141, indicating the typical transaction value.

  + **Number of Items Sold**: Reaches 8,523, reflecting total product sales.

  + **Average Rating**: Maintains a value of 4, highlighting customer satisfaction.
   
### ➼ Revenue Distribution: Low-Fat vs. High-Fat Products
  + Low-fat products contribute significantly to total sales, generating $776K, while high-fat products account for $425K.
    
  + Consumers show a higher preference for low-fat products.Hence,the demand for low-fat products is nearly 1.8 times that of high-fat products.

  * Health-conscious choices may be driving the greater sales of low-fat products.





    
![Screenshot (1081)](https://github.com/user-attachments/assets/dabb1ea4-7a00-424d-9de0-e5f27d86c054)
###  ➼  **Fat Content vs. Sales by Location Tier**

+ Across all location types—Tier 1, Tier 2, and Tier 3—low-fat products consistently achieve higher sales.

+ Among the three tiers, Tier 3 records the highest sales for low-fat products. 

+ Consumer preference for low-fat products remains strong, regardless of geographical market segmentation.

  


   ![Screenshot (1082)](https://github.com/user-attachments/assets/41273f95-11c8-4b59-a547-9804e89a014a)

### ➼ **Top 3 Selling Products**

The top three selling product categories on Zepto are:

+ Fruits & Vegetables

+ Snack Foods

+ Household Items

### ➼ **Average Sales**

 + The average sales for all products, regardless of fat content, is $141, with low-fat products at $141 and regular fat products at 
  $142.

+ Despite low-fat products contributing 77.6% of total sales, their average sales remain almost the same as regular fat products.

+ This is due to <u> **no significant price difference** </u> between low-fat and regular fat products, balancing out the per-unit sales value.
  

![Screenshot (1080)](https://github.com/user-attachments/assets/2a348f5d-04aa-4fff-82a5-cdef9f45cdc0)

### ➼ Item Type vs. Sales: Low-Fat vs. Regular Fat

+ Low-fat products consistently dominate sales across various item types.

+ Consumer preference for low-fat options is particularly strong in snack foods (75%) and soft drinks (98.8%).

+ In the starch foods category, 60.3% of sales come from low-fat products, indicating a moderate preference
  
  





![photo-collage png](https://github.com/user-attachments/assets/bda8a7ae-d380-4d66-ab33-bde9cdfc1958)
###  ➼ Outlet Size & Location vs. Sales by Fat Category
+ A consistent pattern of higher sales for low-fat products is observed across outlets based on size and location.

+ In large-sized outlets, total sales remain nearly the same, irrespective of fat content.

+ To our surprise, Tier 2 high-sized outlets, **regular fat products** have higher sales compared to low-fat products.

  
![Screenshot (1093)](https://github.com/user-attachments/assets/96b4e2e2-80bc-4f86-bf6f-70d2432307e7)

+ Most of sales are through tier 3 and tier 2 location type

+ Tier 2 Outlets: Small-sized outlets generate the highest sales, suggesting a strong customer preference for convenience or accessibility in these areas.

+ Tier 3 Outlets: Medium-sized outlets lead in sales, likely due to a balance of product variety and affordability.

+ Size vs. Location Impact: Outlet performance varies by tier and size, indicating that consumer behavior is influenced by regional shopping patterns.







![Screenshot (1100)](https://github.com/user-attachments/assets/d058d2f4-2595-4a19-817c-7035a5109503)


![Screenshot (1099)](https://github.com/user-attachments/assets/6d474c7c-d9a3-4096-8373-3497cc0f47f0)

 
### ➼ **Visibility vs. Sales Insights**
+ **Low Visibility ≠ Low Sales**: Most items have low visibility but still drive high sales (e.g., Fruits & Vegetables: ₹178,124.08). Essential goods sell well despite low visibility.

+ **High Visibility ≠ High Sales**: Breakfast has high visibility  but has low sales (₹15,596.70), proving visibility doesn't always boost sales.

+ **Demand-Driven Sales**: Household (₹135,975.58) and Dairy (₹93,376.93) perform well despite low visibility, indicating necessity matters more than exposure.


![Screenshot (1103)](https://github.com/user-attachments/assets/5fb44d60-3760-4526-9acb-525ef37deb77)
