# ecommerce_db_schema

This repository contains the `ecommerce_schema.sql` file which implements a complete relational schema for a simple e-commerce store using MySQL.

## What is included
- `ecommerce_schema.sql` — Creates database `ecommerce_db` and tables:
  - customers, addresses, suppliers, categories, products
  - orders, order_items, payments, product_reviews
  - indexes and a sample view `v_order_summary`

## How to run (MySQL)
1. Open MySQL Workbench / CLI and connect to your MySQL server.
2. Run the SQL file:
   ```sh
   SOURCE path/to/ecommerce_schema.sql;
