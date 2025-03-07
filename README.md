# Analyze data in a Model Car Database with MySQL Workbench -Inventory Analysis of  Mint Classics Company- relational database MauntClassics

## Overview
This project analyzes the relational database "MauntClassics" to optimize warehouse storage and reduce overstock. The goal is to make data-driven decisions for warehouse closure while maintaining supply chain efficiency.

## Key Insights
- High Sales Products: The majority of stock movement.
- Oversold Items: Inventory tracking improvements are needed.
- Negligible Normal & Overstocked Products: Warehouse space can be optimized.
## Key Takeaways:
  High Sales: The business moves inventory efficiently, but supply chain management needs optimization to prevent stockouts.
  Oversold Products: This is likely due to inaccurate stock tracking or delays in replenishment.
  Normal & Overstocked Products: Minimal impact on storage decisions.
## Data
- `mauntclassica.sql`: Raw inventory and sales data. -data provides by Coursera about  Mint's classic company
- `oversold, high sales, normal stock.csv`: Categorized inventory insights.  This data was Derived from the database" mauntclassica " by running SQL queries in My SQL
- 'low stock high sale product.csv':Categorized inventory insights.This data Derived from the database" mauntclassica " by running SQL queries in My SQL
- 'oversold.csv':Categorized inventory insights.This data Derived from the database" mauntclassica " by running SQL queries in My SQL
## SQL Queries
- `mauntclassica.sql`: Identifies oversold, high sales, and overstocked products.

## Technologies Used
- **MySQL**: Database analysis.
- **Python (Optional)**: Data processing.

## Recommendations:
-Prioritize Stock Accuracy
-Implement real-time inventory tracking to avoid overselling.
-Improve forecasting based on sales trends.
-Optimize Warehousing

-Since overstocked products are minimal, warehouse space could be restructured instead of fully closing a facility.
-Focus on optimizing storage for high-selling products.
-Supplier & Order Management
-Strengthen supplier relationships for faster restocking of high-sales items.
-Automate reorder levels for in-demand products
-1985 Toyota Supra is the product name quantity is 7733 but not sold product, this product must be sold at a discount or returned to the supplier so that the warehouse is optimized.
## Preliminary Insights:
-Oversold Products:

 These products have demand exceeding supply.
 Possible action: Increase restocking or prioritize sourcing.

-Overstocked Products:

 These items have no sales but a significant stock.
 Possible action: Reduce reorder frequency, offer discounts, or phase out.

-High Sales Products:

 These products are performing well in sales.
 Possible action: Keep a close eye on stock levels to avoid running out.

-Normal Stock:
 These products have a balance between sales and inventory.
 Possible action: No immediate action is required, but monitor trends.










## Contributors
Name (shwetachavan555)




