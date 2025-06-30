# amazon_product_review_analysis
A Google Sheets data analysis project exploring Amazon product reviews, pricing, discounts and ratings across 1466 products. Includes a dashboard with Insights 
# 📦 Amazon Product Review Analysis
This project was developed as a part of Digital Skill Up (DSA) Data analysis Capstone, focused on helping Amazon sellers understand the trends in products pricing, discounts, ratings, price buckets and potential revenue. Using a dataset of 1,466 Amazon product listings, the goal was to generate business insights using Google sheets.
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
  - Calculated Columns (Discounted Price, Revenue, Price Buckets)  
  - Dashboard and summary cards
