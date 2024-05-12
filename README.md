# Pizza Sales Data Analysis using SQL

This project dives into pizza order data to uncover key insights and trends. It explores customer preferences, popular pizza choices, revenue patterns, and more through a series of targeted queries. The ultimate goal of this project is to provide actionable information that can help a pizza business optimize its operations, menu, and marketing strategies. 

# DataSet Information: 
A year's worth of sales from a fictitious pizza place, including the date and time of each order and the pizzas served, with additional details on the type, size, quantity, price, and ingredients.

| Table| Field |Description:

| orders| order_id | Unique identifier for each order placed by a table | order_date | Date the order was placed | order_time |Time the order was placed.

| order_details| order_details_id | Unique identifier for each pizza placed within each order | order_id | Foreign key that ties the details in each order to the order itself | pizza_id | Foreign key that ties the pizza ordered to its details, like size and price | quantity | Quantity ordered for each pizza of the same type and size.

| pizzas| pizza_id |Unique identifier for each pizza | pizza_type_id | Foreign key that ties each pizza to its broader pizza type | size | Size of the pizza (Small, Medium, Large, X Large, or XX Large) |  price | Price of the pizza in USD.

| pizza_types| pizza_type_id | Unique identifier for each pizza type |name | Name of the pizza as shown in the menu | category | Category that the pizza fall under in the menu (Classic, Chicken, Supreme, or Veggie) | ingredients | Comma-delimited ingredients used in the pizza as shown in the menu.




























