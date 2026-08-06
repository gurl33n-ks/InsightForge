# Database Schema

## Tables

### Customers
Primary Key:
- customer_id

Purpose:
Stores customer information.

---

### Orders
Primary Key:
- order_id

Foreign Key:
- customer_id

Purpose:
Stores every order placed.

---

### Order Items
Primary Key:
- order_item_id (logical identifier within an order)

Foreign Keys:
- order_id
- product_id
- seller_id

Purpose:
Stores products included in each order.