# pizzasales-modified
Modified pizza sales dataset served for the purpose of data exploration and visualization. The dataset has been intentionally made dirty for the sake of education.
The original mostly cleaned dataset comes from: https://www.kaggle.com/code/melikedilekci/eda-pizza-restaurant-sales

About this Dataset:
Contents
This pizza sales dataset make up 12 relevant features:

order_id: Unique identifier for each order placed by a table

order_details_id: Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)

pizza_id: Unique key identifier that ties the pizza ordered to its details, like size and price

quantity: Quantity ordered for each pizza of the same type and size

order_date: Date the order was placed (entered into the system prior to cooking & serving)

order_time: Time the order was placed (entered into the system prior to cooking & serving)

unit_price: Price of the pizza in USD

total_price: unit_price * quantity

pizza_size: Size of the pizza (Small, Medium, Large, X Large, or XX Large)

pizza_type: Unique key identifier that ties the pizza ordered to its details, like size and price

pizza_ingredients: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)

pizza_name: Name of the pizza as shown in the menu


Changes that have been made:
![resampling](https://github.com/user-attachments/assets/177e17f0-4f14-48d9-987f-248be6f5039c)
Resampled according to 10k randomized rows.

![DIRTY](https://github.com/user-attachments/assets/3746bc51-b88e-4228-947b-c09fdcbb9534)
- Set missing values on total_price to random observations.
- Changed random pizza_name observations to lowercase.
- Set the Order_Date on random rows to null.
- Changed the data_format on certain random rows to a different format.
