# Sephora Customer Reviews Analysis


![sephora logo](https://github.com/user-attachments/assets/a6de981a-1c01-41ca-a3ba-510681808201)

# About

This project analyzes a large set of Sephora product reviews to uncover insights into customer sentiment, product popularity, and brand performance. 
Using Python and Power BI, the data was cleaned, structured, and visualized to support data-driven recommendations.

# Data Cleaning Process
Data cleaning was performed using:
- Python (Pandas) – for handling large volumes data,missing values, nulls, whitespace , etc
- Power BI Power Query – for further transformation and model linking

# Dataset Overview
1. **Product.csv**

- product_id:                                               Unique ID of product
- product_name, brand_id, brand_name:                       Product and brand details
- loves_count, rating, reviews:                             Popularity & rating metrics
- size, variation_type, variation_value, variation_desc:    Product variants
- ingredients :    Ingredient info
- price_usd, value_price_usd, sale_price_usd:         Price info
- limited_edition, new, online_only, out_of_stock, sephora_exclusive:     Flags
- highlights, primary_category, secondary_category, tertiary_category:    Categorization
- child_count, child_max_price, child_min_price :                        Variant stats

2.**Customer_Reviews.csv**
- author_id:   Unique reviewer ID
- rating, is_recommended : Review rating & sentiment
- review_text, review_title, submission_time : Review content
- total_feedback_count, total_pos_feedback_count, total_neg_feedback_count: Helpfulness votes
- skin_tone, skin_type, eye_color, hair_color: Reviewer Profile
- product_id, product_name, brand_name, price_usd : Product info
- clean_skin_type : Duplicated and changed data type from skin_type

3.**Date**
- Date:    Full Date
- Year, Month, Month_name:  Time components for analysis

# Business Questions
1.**Number of Reviews and Ratings by Year**

*How has customer engagement changed over time?*

- Insight: Customer engagement peaked in 20202 with the highest number of reviews and ratings
- Power BI: Combo Chart showing trend of reviews and ratings by years



2.**Top 5 Most Reviewed Products**

*Which products received the highest number of reviews?*

- Insight: The most reviewed products are dominated by skincare brands.
- Power BI: Clustered column chart showing product names sorted by total number of reviews.

  

3.**Average Rating by Skin Type**

*Do different skin types rate products differently?*

- Insight: Combination or dry skin types gave slightly higher average ratings compared to oily or normal skin types.

- Power BI: Pie chart are using to visualize the different in percentage between each skin type

4.**Number of Reviews vs Total Positive Feedback by Years**

*Does a higher number of reviews mean better sentiment overtime?*

- Insight: Products with higher review counts also tend to receive more positive feedback overtime, showing a possible correlation.
  
- Power BI: Line chart capture the trend of total_reviews vs total_pos_feedback_count overtime.


# Tools Used
- Python (Pandas) – data cleaning and preparation
- Power BI – data modeling, DAX, and dashboard creation
- Power Query – ETL in Power BI

# Skills Demonstrated

- Data Wrangling with Python & Pandas
- Power BI Data Modeling
- DAX Measures and KPIs
- Customer Segmentation & Review Analysis
- Visual Storytelling for E-commerce

# Dashboard Previews
- [Sephora Customer Reviews.jpg]


# License

[![License: CC0 1.0 Universal](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This project is dedicated to the public domain under the [Creative Commons CC0 1.0 Universal License](https://creativecommons.org/publicdomain/zero/1.0/).  
You can copy, modify, and distribute this work without any restrictions.


# Contact

For questions or collaboration, feel free to connect:  
**[Feliz-7]
**GitHub: [@Feliz-7](https://github.com/Feliz-7)




