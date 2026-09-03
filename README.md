# Amazon Products Sales Data Cleaning & Analysis (Excel)

## Project Overview

This project focuses on cleaning, transforming, and analyzing a real-world Amazon Products Sales dataset obtained from Kaggle using MS Excel.

The dataset contained inconsistent formatting, missing values, text-based delivery information, pricing irregularities, and categorical inconsistencies. The project demonstrates practical data cleaning techniques, exploratory analysis, KPI reporting, and dashboard creation using Pivot Tables, Excel formulas, and charts.

## Dataset Information

This project uses the **Amazon Products Sales Dataset 42K+ Items - 2025**, created by **Ikram Ul Hassan** and published on Kaggle.

The dataset contains **42,000+ Amazon product listings** collected from Amazon and is designed for data cleaning, feature engineering, exploratory analysis, and business analytics practice. The dataset covers a broad range of product and listing information, including product ratings, review counts, purchase volume, pricing, discounts, seller status, sponsorship, coupons, Buy Box availability, delivery information, and product categories.

Key fields in the dataset include:

* **Product information:** Product title and product category
* **Customer feedback:** Product rating and total number of reviews
* **Sales activity:** Number of products purchased in the previous month
* **Pricing:** Original price, discounted price, and discount percentage
* **Listing performance:** Best Seller status, Sponsored status, and Buy Box availability
* **Promotions:** Coupon availability and coupon status
* **Delivery:** Delivery dates and related delivery information
* **Additional attributes:** Sustainability information and product/listing metadata

The original dataset contains inconsistencies and formatting issues that make it suitable for practical data-cleaning work. The project uses a sample of the dataset for cleaning, transformation, analysis, KPI development, and dashboard creation in Excel.

**Dataset Creator:** Ikram Ul Hassan
**Source:** [Amazon Products Sales Dataset 42K+ Items - 2025 on Kaggle](https://www.kaggle.com/datasets/ikramshah512/amazon-products-sales-dataset-42k-items-2025)
**License:** **CC BY-NC 4.0 (Creative Commons Attribution–NonCommercial 4.0)**

## Tools Used

- Excel Online
- Pivot Tables
- Pivot Charts
- Excel Formulas
- Data Cleaning Techniques
- Dashboard Design

## Data Cleaning Process

The following cleaning steps were performed:

- Removed duplicates and standardized formatting
- Converted delivery text into structured delivery dates
- Extracted delivery charges from text-based fields
- Created calculated columns such as:
  - discount_rate
  - delivery_type
  - delivery_days
  - discount_bucket
  - price_bucket
  - rating_range
- Standardized date formats
- Handled missing values and inconsistent entries
- Converted text-based prices into numeric values

## Analysis Performed

The project includes analysis on:

- Delivery Type Impact
- Discount Impact on Purchases
- Price vs Demand
- Best Seller Performance
- Coupon Impact
- Delivery Speed Analysis

## Key Insights

- Products with moderate discounts (10–30%) generated the highest average purchase volumes.
- Lower-priced products ($0–50) dominated customer demand and represented the largest product segment.
- Fastest delivery options significantly reduced average delivery times compared to standard shipping.
- Best-selling products consistently outperformed non-best sellers in ratings, purchase volumes, and discount levels.
- Coupon analysis showed dataset imbalance, making conclusions less reliable for coupon effectiveness.

## Dataset Limitations

- Significant imbalance exists between best-seller and non-best-seller products.
- Coupon-enabled products represented a much smaller portion of the dataset.
- Some delivery information required manual extraction and transformation due to inconsistent formatting.

## Conclusion

This project demonstrates practical Excel-based data cleaning, transformation, exploratory analysis, and dashboard creation skills using a messy real-world e-commerce dataset.

