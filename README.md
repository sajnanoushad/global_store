# global_store
Global Store Database Project

 Overview

This project creates a database for managing a store’s products and orders. It consists of two tables: Inventory (for product details) and Orders (for customer orders).

Tables

1. Inventory:

   - product_id: Unique identifier

   - name: Product name

   - price: Product price

   - quantity: Stock amount

   - category: Product category

2. Orders

   - order_id: Unique identifier

   - product_id: Reference to product

   - quantity_ordered: Amount ordered

   - order_date: Date of order

 Features

- Insert sample product and order data.

- Run queries to fetch:

  - Unique categories

  - Most expensive products

  - Products in stock

  - Total inventory price

  - Count by category

  - Out of stock items

  - Expensive product view

  - Combined product and order information

 Conclusion

This database helps organize and manage store inventory and orders effectively.

