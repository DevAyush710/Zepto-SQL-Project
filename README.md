ZEPTO-SQL-PROJECT

📌 Project Overview
This project replicates the typical workflow of a data analyst in the e-commerce or retail sector by using SQL to manage and analyze real-world product data. The focus is on building a robust inventory database, performing detailed exploratory analysis, cleaning inconsistent data, and extracting meaningful business insights.

🔧 Key Tasks:

Designed a structured SQL database from unrefined inventory data
Conducted EDA to examine product availability, pricing issues, and category distribution
Cleaned data by fixing nulls, removing faulty records, and converting prices from paise to rupees
Wrote insight-driven SQL queries to evaluate stock trends, revenue drivers, and pricing effectiveness
📁 Dataset Summary
The dataset, originally sourced from Kaggle and based on Zepto’s product listings, mirrors what analysts often face in real e-commerce systems. Each record represents a unique SKU (Stock Keeping Unit), with duplicate product names reflecting variations in size, weight, discounts, or packaging — a common scenario in online catalogs.

🔍 Key Columns:

sku_id – Synthetic primary key identifying each entry
name – Product title as displayed on the app
category – Classification such as Fruits, Snacks, or Beverages
mrp – Maximum Retail Price (converted from paise to ₹)
discountPercent – Discount percentage applied on MRP
discountedSellingPrice – Final selling price after applying discount
availableQuantity – Inventory count for the product
weightInGms – Weight of the product in grams
outOfStock – Boolean indicating stock status
quantity – Units per package (varies for loose and packed items)
🔍 Data Exploration
Assessed overall dataset structure and record count
Identified null values and reviewed unique product categories
Compared in-stock vs. out-of-stock items
Analyzed SKU duplications due to different package formats
🧹 Data Cleaning
Removed entries with zero MRP or selling price
Standardized pricing by converting all monetary values from paise to ₹
📊 Business Insights
Ranked top 10 best-value products based on highest discounts
Highlighted out-of-stock items with high MRP
Estimated revenue potential by product category
Filtered high-cost products with low discounts
Ranked categories offering highest average discounts
Calculated price-per-gram to evaluate product value
Categorized inventory into Low, Medium, and Bulk weight groups
Computed total inventory weight per product category
