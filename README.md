# Shopify-Data-Challenge-Summer-2022

The task was to identify and calculate a metric to report for [this](https://docs.google.com/spreadsheets/d/16i38oonuX1y1g7C_UAmiK9GkY7cS-64DfiDMNiR41LM/edit#gid=0) dataset.

Two metrics were calculated: 
- total order_amount per shop_id (and total items )
- order_amount per payment_method (and total items)

### Total Order amount per shop_id
A preliminary graph shows that 2 shops have significantly higher order_amount's than the rest. 
![Graph of order_amounts per shop](https://github.com/RonnieDsouza/Shopify-Data-Challenge-Summer-2022/blob/main/images/orders_per_shop.PNG "Order amounts per shop")

After calculating, we can see that **shop_id 42 has the highest total order amount followed by shop_id 78**.
![Order_amounts per shop values](https://github.com/RonnieDsouza/Shopify-Data-Challenge-Summer-2022/blob/main/images/orders_per_shop_top5.PNG "Order amounts per shop")

### Order amount per payment_method
Once again, the graph shows us that credit cards have higher order amounts (and total_items) compared to cash and debit. 
![Graph of order_amounts per shop](https://github.com/RonnieDsouza/Shopify-Data-Challenge-Summer-2022/blob/main/images/orders_per_payment_method.PNG "Order Amount per Payment Methods")  

This tells us that the **majority of transactions occour using credit cards**.  
![Order Amount per Payment Methods Values](https://github.com/RonnieDsouza/Shopify-Data-Challenge-Summer-2022/blob/main/images/orders_per_payment_method_calc.PNG "Order Amount per Payment Methods")

