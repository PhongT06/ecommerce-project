This is a simple e-commerce web application built with:
Python using Flask for the backend, 
SQLAlchemy for database management, 
and Marshmallow for serialization/deserialization.

Uses Python with Postman and MYSQL Workbench

Endpoints:

/customers
GET: Get all customers.
POST: Add a new customer.

/customers/<customer_id>
GET: Get a customer by ID.
PUT: Update a customer by ID.
DELETE: Delete a customer by ID.

/products
GET: Get all products.
POST: Add a new product.

/products/<product_id>
PUT: Update a product by ID.
DELETE: Delete a product by ID.

/products/by-name/<product_name>
GET: Get products by name.

/orders
GET: Get all orders.
POST: Add a new order.

/orders/<customer_id>
GET: Get orders by customer ID.
