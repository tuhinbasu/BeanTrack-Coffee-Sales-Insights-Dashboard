<div align = "center"><h2><u>BeanTrack- Coffee Sales Insight Dashboard</u></h2></div>

![image](https://github.com/user-attachments/assets/795be1b2-7322-4db1-a9d9-5634b206ec7f)

<h2><u>Know your coffee beans</u></h2>
<p>
1. <b>Arabica:</b> Known for its smooth and mild flavor, Arabica is the most popular coffee bean, accounting for about 60% of global production. It grows at higher altitudes, offering a wide flavor profile with hints of sweetness, fruitiness, and acidity.</br>
2. <b>Robusta:</b> With a bold and bitter taste, Robusta beans are higher in caffeine and commonly used in espresso blends for their strong body and crema. They thrive in lower altitudes and are more resistant to pests.</br>
3. <b>Liberica:</b> A rare and unique bean, Liberica is prized for its smoky, floral, and fruity aroma. Its distinct flavor profile sets it apart, though it is less widely cultivated.</br>
4. <b>Excelsa:</b> A variety of Liberica, Excelsa has a tart, fruity, and complex flavor. It is often used to add depth and character to coffee blends, making it a favorite for adventurous coffee drinkers.</br>
</p>

<h2><u>Objectives:</u></h2>
<p>
1. <b>Trend Analysis:</b> Evaluate annual sales data to uncover growth patterns.</br>
2. <b>Coffee Bean Performance:</b> Assess the performance of individual coffee bean types (e.g., Arabica, Robusta, Liberica, Excelsa) to identify the top-performing varieties overall.</br>
3. <b>Top Countries by Sales:</b> rank countries based on their total sales volume and contribution to overall revenue.</br>
4. <b>Loyal Customers:</b> Recognize customers with consistent repeat purchases over time.</br>
5. <b>High-Value Customers:</b> Identify and rank customers based on total expenditure to highlight the most profitable clients.</br>
</p>

<h2><u>Data</u></h2>
<p>
1. <b>Orders:</b> It contains all the details related to orders with Order ID, Customer ID, Product ID, Order Date, and Quantity..</br>
2. <b>Customers:</b> It contains all the details related to the customers with Customer ID, Customer Name, Email, Phone Number, Address, City, Country, Postcode, and Loyalty Card..</br>
3. <b>Products:</b> It contains all the products (beans) related details with Product ID, Coffee Type, Roast Type, Size, Unit Price, Price per 100g, and Profit..</br>
</p>

<h2><u>Data Manipulation and Cleaning</u></h2>
<p>
  
  ![image](https://github.com/user-attachments/assets/18105188-08f0-4e7c-9810-e9a3155e0eb8)

1. Analysed three datasets to identify and select the relevant columns required for the analysis.</br>
2. Merged the necessary columns from the Customers and Products datasets into the Orders dataset for a unified view..</br>
3. Utilized XLOOKUP, IFS, and INDEX-MATCH functions to efficiently retrieve and map data across tables..</br>
3. Transformed the final dataset into a dynamic table, ensuring automatic updates in the dashboard with any new data additions..</br>
5. Removed duplicates, replaced NaN values with empty strings, and standardized sales values by converting them to dollars..</br>
</p>


