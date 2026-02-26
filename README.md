# Amazon-Sales-Dashboard

## 📋 Overview
This Power BI dashboard provides comprehensive analytics for 42,000+ Amazon electronics products, offering deep insights into sales performance, pricing strategies, customer behavior, and market trends. The dashboard is designed for business stakeholders, category managers, and data analysts to make data-driven decisions.

## 🗂️ Dataset Description
Dataset Link : https://www.kaggle.com/datasets/ikramshah512/amazon-products-sales-dataset-42k-items-2025

features:
- product_title – Complete name/title of the product
- product_rating – Average customer rating (numeric) out of 5
- total_reviews – Total number of customer reviews
- purchased_last_month – Units purchased in the last month
- discounted_price – Current price after discount
- original_price – Original listed price before discount
- discount_percentage – Percentage discount applied to the product
- is_best_seller – Indicates if the product is tagged as a Best Seller
- is_sponsored – Whether the product is a Sponsored item or Organic
- has_coupon – Special discounted coupons availability (True/False)
- buy_box_availability – BuyBox button availability on amazon search page like add to cart(nan values represent False)
- delivery_date – Estimated delivery date (converted to datetime format)
- sustainability_tags – Eco-friendly and sustainability-related tags
- product_image_url – Direct image link of the product
- product_page_url – Official Amazon product page URL
- data_collected_at – Date when the data was collected
- product_category – Assigned product category based on the title


## 📊 Dashboard Pages
### 1. Executive Summary
### 2. Producty Performance Analysis
  - Product distribution by category
  - Rating analysis with category comparison
  - Best Seller concentration
  - Delivery coverage by category
  - Category-wise KPI cards

### 3. Price & Discount Analysis
  - Price bucket distribution (Under $25/$25-$50/$50-$100/$100+)
  - Discount band analysis (0-10%, 11-20%, 21-30%, 31-40%, 41-50%, 50%+)
  - Badge impact analysis (Best Seller, Limited Time, Coupons)
  - Sponsored vs Organic performance comparison

### 4. Sustainability Insights
  - Sustainability adoption by category
  - Performance premium (rating, price, purchases)


## 🧰 Tools & Technologies
- Power BI Desktop: Main dashboard development
- DAX (Data Analysis Expressions): Calculated measures
- Power Query : Data transformation
- Excel: Initial data exploration
- Git/GitHub: Version control and sharing
