# inventory-control-sample-db

## Current Status: In Progress
- Tables (5) with relationships - Completed
- Queries (4) - Completed
- Forms - In progress
- Reports - In progress

## Features
Relational inventory management database built in Microsoft Access.
Tracks products, suppliers, stock levels and transactions.

## Database Structure
- **tblProducts** - product catalog with SKU, pricing, and reorder levels
- **tblCategories** - product category groupings
- **tblSuppliers** - supplier contact information
- **tblInventory** - current stock levels and warehouse locations
- **tblTransactions** - full audit log of stock movements (IN/OUT/ADJUST)

## Queries
- **qryCurrentStock** - live stock levels joined across products and inventory
- **qryLowStock** - filters items at or below reorder level
- **qryTransactionHistory** - full audit trail with product names
- **qryStockByCategory** - summarized stock totals grouped by category

## Screenshots
 
### Relationships Diagram
![Relationships](screenshots/relationships.png)
 
### Current Stock Query
![Current Stock](screenshots/qry_current_stock.png)
 
### Low Stock Alert Query
![Low Stock](screenshots/qry_low_stock.png)
 
### Stock by Category Query
![Stock by Category](screenshots/qry_stock_by_category.png)
 
### Transaction History Query
![Transaction History](screenshots/qry_transaction_history.png)

## Requirements
Microsoft Access 2016 or later
