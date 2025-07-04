# amazon_product_review_analysis
A Google Sheets data analysis project exploring Amazon product reviews, pricing, discounts and ratings across 1465 products. Includes a dashboard with Insights 
# 📦 Amazon Product Review Analysis
This project was developed as a part of Digital Skill Up (DSA) Data analysis Capstone, focused on helping Amazon sellers understand the trends in products pricing, discounts, ratings, price buckets and potential revenue. Using a dataset of 1,465 Amazon product listings, the goal was to generate business insights using Google sheets.
## 📚 Project Background
Amazon's marketplace contains thousands of products, and sellers rely on pricing strategies, reviews and discount campaigns to drive customer engagement and products improvements. Without analysis , it is difficult to identify which product categories are performing well, which discounted producted attract more customers and how discounts affect customer's satisfaction.
As a Junior Data analyst at **RetailTech Insights**, my task was to analyse product listings and present key metrics through a dashboard to inform startegic business decisions 
## 🎯 Business Objectives
- What is the average discount percentage by product category? 
- How many products are listed under each category? 
- What is the total number of reviews per category?  
- Which products have the highest average ratings? 
- What is the average actual price vs the discounted price by category? 
- Which products have the highest number of reviews? 
- How many products have a discount of 50% or more? 
- What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)? 
- What is the total potential revenue (actual_price × rating_count) by category? 
- What is the number of unique products per price range bucket (e.g., <₹200, 
₹200–₹500, >₹500)? 
- How does the rating relate to the level of discount? 
- How many products have fewer than 1,000 reviews? 
- Which categories have products with the highest discounts? 
- Identify the top 5 products in terms of rating and number of reviews combined. 
## 📂 Dataset Overview
The dataset includes **1,466 Amazon products** with 16 columns
| Column Name         | Description                                     |
|---------------------|-------------------------------------------------|
| product_ID          | A unique code to each product category          |
| category            | Product category (e.g., Home, Electronics)      |
| product_name        | Name of product                                 |
| discounted_price    | Dicounted price of Product                      |
| actual_price	      | Original price of products                      |
| discount_percentage | Percentage discount offered                     |
| rating	            | Customer rating                                 | 
| rating_count 	      | Count of customers who rated the product        |
| about_product	      | Details about the product                       |
| user_id	            | Customers id                                    |
| user_name	          | Name of customer                                |
| review_id	          | A unique code attached to each review           |
| review_title	      | Written feedback from customers                 |
| review_content	    | Written feedback from customers                 |
| img_link            | Link to the image of the product                |
| product_link	      | Link to the product itself                      |
## 🧰 Tools Used
- ✅ **Google Sheets**
  - Data Cleaning & Formatting  
  - Pivot Tables & Charts  
  - Calculated Columns (Discounted Price, Potential Revenue, Price Buckets)  
  - Dashboard and summary cards
- ✅ **GitHub**
  - For documentation
## 📊 Dashboard Features
The Google Sheets dashboard includes;
### 🔹 KPI Cards / Summary Cards
- 🟢 Total Number of Products  
- 🌟 Average Product Rating  
- 💬 Total Ratings
- 💰 Sum of Potential Revenue
### 🔹 Charts
- 📈 **Distribution of Ratings** — Column chart showing how ratings are spread  
- 💰 **Product count by Price Bucket** — Bar chart showing the count of product by price bucket  
- 📉 **Average Discount % by Category** — Column chart showing the average discount % by category
- 🧾 **Actual vs Discounted Price Comparison** — Column chart 
- 🏠 **Potential Revenue by Category** — Column chart to help identify profit-driving Products category 
- 🔝 **Top 5 Products Category** — Column chart  
- ⚖️ **Relationship between Ratings and Discount Percentage** — Scatter plot to check correlation
## 💡 Key Business Insights
- ✅ Most product categories have an average rating above **4.0**, depicting good customer satisfaction
- ✅ Over **800 products are priced above  ₹500**, showing Amazon’s dominance in high-end customer market. Mid-range and budget friendly items exists but are smaller in comparison. This pricing structure could influence marketing strategies and sales patterns
- ✅ Homeimprovements, Health&personalcare, Electronics and Computers&accesories
- ✅ Electronics has the highest **Potential Revenue**, making it a key strategic product category
-  🌟 A few top products dominate the marketplace with **millions of reviews**, and could be used as benchmarks or promoted items
- ❌ There is **no strong correlation** between discount % and ratings 
- ## 🔬 Analysis Techniques Used
  
- Pivot tables 
- Calculated Columns
  - Potential Revenue  
  - Price buckets
  - Rating Score 
- Sorting & filtering for product-level insights  
- Comparative analysis using charts (bar, column,scatter)
- 
## 🎓 What I Learned

- How to perform exploratory data analysis (EDA) on real-world ecommerce data  
- How to create structured dashboards in Google Sheets  
- How to derive actionable insights from product metadata  
- Importance of clean formatting, interactive visuals, and storytelling in analytics

## 📁 Project Files 
- `Dashboard PDF` – Image of the completed dashboard  
- `Amazon_Product_Review_Analysis_Readme.md` – This documentation

  ## 🔗 Live Dashboard

👉 [Click here to view the Google Sheets Dashboard](https://docs.google.com/spreadsheets/d/1UCx_I3XOOxmLdpwe0kngytNN0AmqPgya/edit?gid=1627746479#gid=1627746479)

## 📬 Contact

**Oluwatobiloba Akinnubi**  
📧 hephzibaholuwatobiloba@gmail.com
🔗 [LinkedIn Profile](https://www.linkedin.com/in/oluwatobiloba-akinnubi)  


