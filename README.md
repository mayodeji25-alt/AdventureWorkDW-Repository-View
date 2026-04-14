# AdventureWorksDW Repository Views

This script creates several views in the AdventureWorksDW2025 database for analytical purposes. 
Ensure you have the necessary permissions and understanding of the database schema before running these scripts.

## Views Created

1. **Top 10 Products by Reorder Point**: `vw_Top10Products1`
2. **Top 100 Customers by Geography Key**: `vw_Top100CustomersByGeography`
3. **Top 100 Single Marital Status Customers**: `vw_Top100SingleCustomers`
4. **Top 10 Finance Records by Amount**: `vw_Top10FinanceByAmount`
5. **Sales Territories**: `vw_SalesTerritories`
6. **Product Categories**: `vw_ProductCategories`
7. **Sales Quotas**: `vw_SalesQuotas1`


## Description of Views

- **`vw_Top10Products1`**: Displays the top 10 products with the highest reorder points to manage inventory effectively.
- **`vw_Top100CustomersByGeography`**: Lists the top 100 customers segmented by geography for targeted marketing and sales strategies.
- **`vw_Top100SingleCustomers`**: Focuses on single customers, which might be a unique demographic for specific campaigns.
- **`vw_Top10FinanceByAmount`**: Shows the largest finance records, useful for financial analysts and accountants.
- **`vw_SalesTerritories`**: Organizes sales territories data for sales team allocation and performance analysis.
- **`vw_ProductCategories`**: Provides a complete view of product categories for inventory and sales analysis.
- **`vw_SalesQuotas1`**: Orders sales quotas by quarter and amount to track sales performance over time.
