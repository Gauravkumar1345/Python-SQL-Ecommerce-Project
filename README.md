 🛍️ Python-SQL E-commerce Project

> Ecommerce project using Python and SQL for data processing, analysis, and insights.

 🚀 Project Overview

This repository contains a Python and SQL-based e-commerce project that demonstrates how to connect Python with a SQL database to perform data queries, data manipulation, and basic analytics.

The project is implemented as a Jupyter Notebook (`python+sql_ecommerce.ipynb`) where various SQL operations and Python code are used together to explore and process e-commerce data.

 🧠 Features

✔ Connects Python with SQL to fetch and analyze data.  
✔ Executes SQL queries to retrieve meaningful business insights.  
✔ Uses Python for data processing, visualization, and result presentation.  
✔ Demonstrates common operations like filtering, sorting, aggregations, and joins.

 🛠️ Tech Stack

- **Python** — For processing, analyzing, and plotting results.
- **SQL** — For storing and querying e-commerce records.
- **Jupyter Notebook** — Interactive environment for running the code.

 📂 Project Structure
Python-SQL-Ecommerce-Project/
├── python+sql_ecommerce.ipynb # Core notebook with Python & SQL code
└── README.md # Project documentation


> The main work is in the `python+sql_ecommerce.ipynb`, which combines both Python and SQL examples into a single workflow.


🗂️ Dataset Schema & Tables

The dataset consists of the following tables:

1️⃣ olist_customers_dataset.csv

Contains customer information.

Column Name	Description
customer_id	Unique customer identifier
customer_unique_id	Unique customer across orders
customer_zip_code_prefix	Customer ZIP code
customer_city	Customer city
customer_state	Customer state

2️⃣ olist_orders_dataset.csv

Contains order-level details.

Column Name	Description
order_id	Unique order ID
customer_id	Customer ID
order_status	Order status (delivered, shipped, etc.)
order_purchase_timestamp	Order purchase time
order_approved_at	Order approval time
order_delivered_carrier_date	Carrier delivery date
order_delivered_customer_date	Customer delivery date
order_estimated_delivery_date	Estimated delivery date

3️⃣ olist_order_items_dataset.csv

Contains item-level details for each order.

Column Name	Description
order_id	Order ID
order_item_id	Item number within order
product_id	Product ID
seller_id	Seller ID
shipping_limit_date	Shipping deadline
price	Item price
freight_value	Shipping cost

4️⃣ olist_products_dataset.csv

Contains product information.

Column Name	Description
product_id	Product ID
product_category_name	Category name (Portuguese)
product_name_lenght	Product name length
product_description_lenght	Description length
product_photos_qty	Number of photos
product_weight_g	Weight (grams)
product_length_cm	Length
product_height_cm	Height
product_width_cm	Width

5️⃣ olist_order_payments_dataset.csv

Contains payment information for orders.

Column Name	Description
order_id	Order ID
payment_sequential	Payment sequence
payment_type	Payment method
payment_installments	Installments
payment_value	Payment amount

6️⃣ olist_order_reviews_dataset.csv

Contains customer review data.

Column Name	Description
review_id	Review ID
order_id	Order ID
review_score	Rating (1–5)
review_comment_title	Review title
review_comment_message	Review message
review_creation_date	Review date
review_answer_timestamp	Seller response time

7️⃣ olist_sellers_dataset.csv

Contains seller information.

Column Name	Description
seller_id	Seller ID
seller_zip_code_prefix	ZIP code
seller_city	Seller city
seller_state	Seller state

8️⃣ olist_geolocation_dataset.csv

Contains geographical coordinates for ZIP codes.

Column Name	Description
geolocation_zip_code_prefix	ZIP code
geolocation_lat	Latitude
geolocation_lng	Longitude
geolocation_city	City
geolocation_state	State

9️⃣ product_category_name_translation.csv

Maps Portuguese category names to English.

Column Name	Description
product_category_name	Portuguese category
product_category_name_english	English translation



 💡 Getting Started

 1. Clone the Repository

```bash
git clone https://github.com/Gauravkumar1345/Python-SQL-Ecommerce-Project.git
cd Python-SQL-Ecommerce-Project

pip install pandas sqlalchemy notebook
Open & Run Notebook
jupyter notebook

