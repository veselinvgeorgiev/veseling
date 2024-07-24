Customer Satisfaction in the Olist Online Store

Python libraries used: Pandas, Scikit-learn, Mathplotlib, Seaborn, Statsmodels, NumPy.   

This project is based on a Brazilian ecommerce public dataset made at [Olist Store](https://olist.com/).
Olist is essentially an aggregating platform - it offers suppliers or sellers the possibility to sell their products at their website and connects them to potential buyers.
You can find more information about the dataset [here](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil.
Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, 
product attributes and finally reviews written by customers.
The dataset also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

1) Main task is to analyze and report what drives the satisfaction of end-customers in this online store. 
The table `olist_order_reviews_dataset` contains a column `review_score` with values Mfrom 1 to 5 (lowest to highest) reporting the satisfaction from each purchased order. 
This score is essentially the so-called CSAT (customer satisfaction score), popular customer experience metric.

2) Additional task is to perform customer segmentation. It is done quantitatively via a so-called `k-means` clustering method which is the most widely used.

