# EmployeeDB-Schema-Task-1
Basic SQL database schema with ER diagram for e-commerce project
# E-Commerce SQL Schema

This project contains the SQL DDL script for setting up a basic e-commerce database.

Tables

1. Users – Stores user data (email, password, etc.)
2. Products – Items available for purchase
3. Orders – User orders with timestamps and statuses
4. OrderItems – Products within each order (many-to-many logic)
5. Payments – Payment info linked to orders

 Keys and Relationships

- Each `Order` belongs to one `User`
- Each `Order` contains many `OrderItems`
- Each `OrderItem` refers to one `Product`
- Each `Order` has one associated `Payment`

 ✅ Normalization

- 3NF maintained: no data redundancy, foreign keys used.
