# E-commerce Business Transaction Analysis

This dataset contains one year of sale transactional data from a UK-based online retail company specializing in gifts and homeware products for adults and children. The business operates primarily through an e-commerce platform and serves both individual customers and small retailers worldwide.

The dataset includes approximately 500,000 records and 8 key variables, covering transaction details:
- TransactionNo: a six-digit unique number that defines each transaction
- Date: the date when each transaction was generated
- ProductNo: a five or six-digit unique character used to identify a specific product
- ProductName: product/item name
- Price: the price of each product per unit in pound sterling (£)
- Quantity: the quantity of each product per transaction
- CustomerNo: a five-digit unique number that defines each customer
- Country: name of the country where the customer resides

Let's inspect the initial rows to analyze the data in its original format.


|TransactionNo|Date|ProductNo|ProductName|Price|Quantity|CustomerNo|Country|
|-------------|----|---------|-----------|-----|--------|----------|-------|
|581482|12/9/2019|22485|Set Of 2 Wooden Market Crates|21.47|12|17490|United Kingdom|
|581475|12/9/2019|22596|Christmas Star Wish List Chalkboard|10.65|36|13069|United Kingdom|
|581475|12/9/2019|23235|Storage Tin Vintage Leaf|11.53|12|13069|United Kingdom|
|581475|12/9/2019|23272|Tree T-Light Holder Willie Winkie|10.65|12|13069|United Kingdom|
|581475|12/9/2019|23239|Set Of 4 Knick Knack Tins Poppies|11.94|6|13069|United Kingdom|
|581475|12/9/2019|21705|Bag 500g Swirly Marbles|10.65|24|13069|United Kingdom|
|581475|12/9/2019|22118|Joy Wooden Block Letters|11.53|18|13069|United Kingdom|
|581475|12/9/2019|22119|Peace Wooden Block Letters|12.25|12|13069|United Kingdom|
|581475|12/9/2019|22217|T-Light Holder Hanging Lace|10.65|12|13069|United Kingdom|
|581475|12/9/2019|22216|T-Light Holder White Lace|10.55|24|13069|United Kingdom|


The following section outlines the key steps undertaken in the data analysis process.

## 🔥 Step 1 - Data Preparation: Use Python to query, clean, and transform data (incorrect data types, missing values) - E_commerce_Business_Transaction.ipynb

## 🔥 Step 2 - Exploratory Data Analysis (EDA): Analyse and visualise data using Python - E_commerce_Business_Transaction.ipynb

## 🔥 Step 3 - Visualization & Dashboard: Build dashboards using BI tools - Sales Transaction Overview.pbix

<img width="889" height="501" alt="image" src="https://github.com/user-attachments/assets/25d4edb2-8850-4659-a2b3-d9d3f8e1e330" />


## 🔥 Step 4 – Key Insights & Recommendations

### 📊 1. Sales Trend Insight
	  
Sales showed a strong upward trend toward the end of the year, peaking around months 10–11

=> Seasonal demand, likely driven by holiday shopping periods
  
  👉 Recommendation:
	
•	Increase marketing campaigns and promotions during peak months
	
•	Prepare inventory in advance to avoid stock shortages

### 🛍️ 2. Product Performance Insight

The top-most ordered products account for strong customer preference and high demand for these specific products

  👉 Recommendation:

•	Focus on promoting top-selling products

•	Slower-moving products should be sold up to increase overall sales


### 👤 3. Customer Behaviour Insight 

Suggests the presence of high-value customer segments

👉 Recommendation:

•	Implement loyalty programs and personalized offers

•	Retarget high-value customers with exclusive promotions

•	Improve customer retention strategies such as birthday discounts, loyalty rewards, and special occasion gifts


### 🌍 4. Geographic Insight

Revenue is concentrated in specific countries (mainly Europe/UK region), while some regions show low contribution

👉 Recommendation:
	
  •	Expand marketing campaign in high-performing regions
	
  •	Explore root reasons and growth opportunities to modify in underperforming markets

### ❌ 5. Cancellation Insight

There is a noticeable number of cancelled transactions across months, leading to lost revenue and operational inefficiencies

👉 Recommendation:

•	Conduct a root cause analysis of cancelled transactions to uncover key drivers such as inventory shortages, fulfillment delays, or gaps in customer experience.

•	Improve inventory management to reduce stockouts

•	Provide real-time stock visibility to customers

### 💸 6. AOV (Average Order Value) Insight

AOV indicates moderate spending per transaction

👉 Recommendation:

•	Introduce upselling strategies

•	Offer discounts for bulk purchases (e.g., buy more save more)

•	Provide free shipping thresholds to increase basket size

The analysis provides actionable insights to enhance revenue growth by optimizing product strategy, improving customer targeting, and reducing operational inefficiencies.





