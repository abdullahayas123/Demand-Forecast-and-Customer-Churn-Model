# DEMAND FORECAST & CUSTOMER CHURN MODELLING

## DESCRIPTION

The CEO of retail business in Europe expects to do some demand forecasting to predict how the company will do in terms of sales in the next few months, and identify what products need to be stocked up. 

In Addition, The Sales Director is planning to implement a more personalized campaign for their customers to increase the company’s customer retention rate. They plan to invest in promotional activities for customers who are deemed valuable. Furthermore, they intend to double down on the amount spent on customers who have not been as active as before.

## OBJECTIVES
### DEMAND FORECAST
- demand prediction based on the transaction data for the next 6 months, need EDA.

### CUSTOMER CHURN MODELLING
- creating a model to identify which customers are predicted to have a high value and which customers are likely to churn, need EDA.

## DATASET
- Historical transaction in retail business from europe for 2010 until 2011 [DOWNLOAD_DATA_HERE](https://drive.google.com/file/d/1Ahi2W1fwLUwp4rorw-iLHaj4bY8jiZGH/view?usp=drive_link)

### DATASET EXPLANATION
- Order ID: Order Identifier, unique for each Transaction. ID starts with 'C' is a cancelled Order.
- Product ID: Product Identifier, unique for each product.
- Product Description: Product Description for given product ID
- Quantity: Quantities Sold for each Order, will be negataive if it's a cancelled order.
- Order Date: The datetime when a transaction occured.
- Unit Price: Price per Unit in GBP (UK Pounds Sterling),
- CustomerID: Customer Identifier, unique for each customer.
- Country: Country name where the transaction happened.
