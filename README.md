# Power-BI_Purchase-order-analysis-

# Raw data & data preprocessing
We have four tables, sales data, product data, store data, and employee data. We need to remove personal identifying information from data first (deidentification). We use python to achieve so. 

![image](https://user-images.githubusercontent.com/58899897/196028907-2ebc7335-3308-40d6-bacb-79c144d70630.png)

We randomly choose 7 universities to replace the information of stores and use geopy to get the address.
![image](https://user-images.githubusercontent.com/58899897/196031356-6eafacbc-1b20-43d0-be79-89c1d1443e3f.png)



Data after preprocessing

![image](https://user-images.githubusercontent.com/58899897/196029658-5e6038c2-5aae-4f76-adeb-0bffc90ea0a9.png)

![image](https://user-images.githubusercontent.com/58899897/196029663-1588e408-7d7d-4099-bd8a-781e14f6caae.png)

![image](https://user-images.githubusercontent.com/58899897/196029688-de3a9e7e-55c1-4966-9bb4-ed87ad70847e.png)

![image](https://user-images.githubusercontent.com/58899897/196031371-47584f0f-9ed8-4e03-b9f7-4a126228402e.png)

The relationships among tables

![image](https://user-images.githubusercontent.com/58899897/196030061-e20723db-2b69-437e-9d22-db1f2b170315.png)


# Power BI Dashboard

![image](https://user-images.githubusercontent.com/58899897/196031723-fcdb2132-284d-4728-9d51-46dc2842643e.png)

Some details of the dashboard

![image](https://user-images.githubusercontent.com/58899897/196031759-77c2d049-b4cd-419c-89f7-cec8be184e28.png)

We use bar chart to show the total sale by store

![image](https://user-images.githubusercontent.com/58899897/196031793-1297dc8c-b7d1-4132-9d75-b1657ff24f15.png)

We use line chart to show the trend of total sales

![image](https://user-images.githubusercontent.com/58899897/196031812-76348e1c-2893-483b-8840-d4d19768ea45.png)

We use map to visualize the salee by store. The bubble size depends on the total sales.

![image](https://user-images.githubusercontent.com/58899897/196031852-f6a8bea5-4522-4c40-ab16-b38d73cd901f.png)

We use bar chart to visualize the achievement rate of salesperson.

![image](https://user-images.githubusercontent.com/58899897/196031899-f2bd0ab9-b8e4-42f7-bd2c-586ee9aa02ee.png)

We use stacked bar chart to visualize the contribution of each product
