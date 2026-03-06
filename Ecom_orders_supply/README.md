# Датасет Kaggle

[Ecommerce Order & Supply Chain Dataset](https://www.kaggle.com/datasets/bytadit/ecommerce-order-dataset)

### Описание таблиц

**Orders Table**
|column name | description |
|---         |---          |
|order_id| Unique identifier for an order, acting as the primary key|
|customer_id| Unique identifier for a customer. This table may not be unique at this level|
|order_status| Indicates the status of an order (e.g., delivered, cancelled, processing, etc.)|
|purchased_date| Timestamp when the order was made by the customer|
|approved_at_date| Timestamp when the order was approved from the seller's side|
|delivered_date| Timestamp when the order was delivered at the customer's location|
|estimated_delivery_date| Estimated date of delivery shared with the customer while placing the order|
---
**Order Items Table**
|column name | description |
|---         |---          |
|order_id| Unique identifier for an order|
|product_id| Unique identifier for a product|
|seller_id| Unique identifier for a seller|
|price| Selling price of the product|
|shipping_charges| Charges associated with the shipping of the product|
---
**Customers Table**
|column name | description |
|---         |---          |
|customer_id| Unique identifier for a customer, acting as the primary key|
|customer_zip_code_prefix| Customer's Zip code|
|customer_city| Customer's city|
|customer_state| Customer's state|
---
**Payments Table**
|column name | description |
|---         |---          |
|order_id| Unique identifier for an order|
|payment_sequential| Provides information about the sequence of payments for the given order|
|payment_type| Type of payment (e.g., credit_card, debit_card, etc.)|
|payment_installments| Payment installment number in case of credit cards|
|payment_value| Transaction value|
---
**Products Table**
|column name | description |
|---         |---          |
|product_id| Unique identifier for each product, acting as the primary key|
|product_category_name| Name of the category the product belongs to|
|product_weight_g| Product weight in grams|
|product_length_cm| Product length in centimeters|
|product_height_cm| Product height in centimeters|
|product_width_cm| Product width in centimeters|