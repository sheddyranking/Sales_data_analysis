# Sales_data_analysis

This is a Sale Data Analysis Project involving (E-commerce Case Study) 

#### Problem Statements => Data Preparations

Write a list comprehension to return all the 12 Months data from the `dir`. And `concat` them into a new `df`.

#### Problem Statements => Best Month of Sales.

Create a `Month Column` covert the `dtypes` to `int` and `Qty Ordered` to `int` as well, `Price Each` to `float` and multple the Quantity Ordered on the Price Each and store in a `sales` column. do a sumed groupby of the `months` with there respect sales and visualized.

![Best_month](https://user-images.githubusercontent.com/42388234/160526918-76b18df4-eeb2-4e6d-bcd0-404304a58fde.png)

#### Problem Statements => Cities with the Highest Order.

Create a `city` column and `group` all the cities and visualise.

![highest_order_city](https://user-images.githubusercontent.com/42388234/160526967-16804968-7e08-4b25-a168-c6edb00daa44.png)


#### Problem Statements => At what time is the sales Products to the MAX.

Convert the `dates` to `dateTime`, creat an `hour` column, group the hours into `keys` and visualize.

![best_time](https://user-images.githubusercontent.com/42388234/160527001-7f2c775c-67f9-489c-93d5-aa669d0fa926.png)


#### Problem Statements => What Product Solds the Most and why.

Do a `groupby` on the `Products` and `Quantity` visualized the see which sales most and do a `groupby` on the `product` and `price` to see why. you can use a `subplot` to plot together as well.

##### Products Sold the most:
![Pr_sold_most](https://user-images.githubusercontent.com/42388234/160527082-65650e9b-f71b-4bdf-85dc-9a07528d9be6.png)

##### Why it sold the most:
![why_its most_sold](https://user-images.githubusercontent.com/42388234/160527138-f95ba20e-cc12-4549-81aa-a365dd50e248.png)

#### Problem Statements => What Products are More often Sold together.

Group the `Order ID's` and remove the Duplicates and Visualize.

![Product_Sold_Together](https://user-images.githubusercontent.com/42388234/160527176-1e058677-3160-4f32-a370-dbb436610b3e.png)


