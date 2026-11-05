# Zepto-Inventory-and-Pricing-Analysis
SQL analysis of Zepto’s grocery inventory and pricing to find discount patterns, stock-outs and business recommendations.

##  Project Overview

This project focuses on analyzing Zepto's retail inventory and product data using PostgreSQL. The objective is to explore product-level information, clean and transform raw data, and solve business-related problems using SQL queries.

The analysis aims to uncover insights related to product pricing, discounts, inventory availability, and category-wise performance to support data-driven business decisions.

##  Dataset

- **Source:** Kaggle
- **Dataset:** Zepto Inventory Dataset
- **Format:** CSV
- **Database:** PostgreSQL

The dataset contains product-level information, including product names, categories, prices, discounts, available quantities, and other inventory-related attributes.

##  Tools & Technologies

- **PostgreSQL:** Database management and SQL-based data analysis.
- **pgAdmin 4:** Database administration and query execution.
- **SQL:** Data loading, exploration, cleaning, transformation, and business analysis.

##  Project Workflow

### Step 1: Data Loading
- Created a database and table in PostgreSQL.
- Imported the Kaggle dataset (CSV format).
- Verified the successful loading of records.

### Step 2: Data Exploration
- Examined the dataset structure and column details.
- Identified the total number of records and columns.
- Explored product categories, pricing, discounts, and inventory levels.

### Step 3: Data Cleaning
- Identified and handled missing or NULL values.
- Checked for duplicate records.
- Standardized data formats and corrected inconsistencies.
- Validated product prices and inventory-related information.

### Step 4: Business Problem Solving
- Developed SQL queries to answer business-related questions.
- Analyzed product pricing and discount patterns.
- Examined category-wise product distribution.
- Evaluated inventory availability and stock levels.
- Identified products and categories with relevant business insights.

### Step 5: Reporting
- Consolidated the results of SQL analysis.
- Prepared a report highlighting key findings.
- Presented actionable recommendations based on the analysis.

##  Results & Key Insights

Key findings

- About 12% of products (453 of 3,731) are out of stock, which is a direct revenue risk.
- Out-of-stock premium products cause the biggest loss per missed order.
- Discounts are uneven: some categories are discounted much more than others.
- Some high-priced products carry very little discount.
- Heavy and bulk categories increase storage and delivery costs.

Business recommendations

- Restock high-value products first and set higher safety stock for them.
- Review the deepest discounts and keep only those that lift sales or clear stock.
- Use targeted discounts instead of blanket discounts.
- Plan storage and delivery around the heaviest categories.
- Promote the best price-per-gram products and clean up duplicate listings.



##  Conclusion

This project provided practical experience in performing end-to-end data analysis using PostgreSQL. It demonstrates the application of SQL for data exploration, data cleaning, and solving real-world business problems using retail inventory data.

The analysis helped develop insights into product pricing, discounts, and inventory management, supporting informed business decision-making.
