### **Data Analysis Mini Project: PC Parts Sales**

#### **Project Overview**:
In this project, I will work with a **mock PC parts sales dataset** to test and improve my Pandas and Seaborn skills. The project focuses on tasks like **data cleaning**, **transformation**, and **analysis**. By handling real-world data challenges—such as missing values and formatting. I will gain deeper insights into pc parts sales performance.

---

### **Dataset Fields**:
The dataset I'll be working with will have the following key columns:
- **Order ID**: The ID of the product sale.
- **Product**: The name of the product sold.
- **Quantity Ordered**: Number of units sold for each product.
- **Price Each**: The price per unit of the product.
- **Order Date**: The date and time the order was placed.
- **City**: The city where the customer is located or where the order was shipped.
- **Country**: The country of the customer.

---

### **Data Cleaning Tasks**:
1. **Handle Missing Values**: I will look for missing values in critical columns like `Quantity Ordered` and `Price Each`, and decide whether to fill or remove them.
2. **Correct Data Types**: I'll ensure columns such as `Quantity Ordered` and `Price Each` are numerical, and the `Order Date` is in the correct date-time format.
3. **Date Parsing**: I’ll extract useful information such as month and hour from the `Order Date` to help with analysis.
4. **Remove Duplicates**: I will check for and remove any duplicate rows to clean up the data.

---

### **Data Analysis Goals**:
1. **Calculate Total Sales by Month**: I will calculate total sales revenue for each month using the formula `Quantity Ordered * Price Each`.
2. **Identify the Best-Selling Product**: I’ll determine which product sold the most in terms of quantity.
3. **Find the Most Profitable Product**: I’ll figure out which product generated the most revenue.
4. **Analyze Sales by City**: I will explore which cities contributed the most to total sales.
5. **Analyze Sales by Country**: I will explore which countries contributed the most to total sales.
6. **Determine the Best Time to Advertise**: By analyzing monthly sales trends from `Order Date`, I will identify the best time to run advertisements.

---

### **Tools I’ll Use**:
- **Pandas**: For data cleaning, aggregation, and analysis.
- **Optional (Seaborn)**: To create visualizations of the sales trends (e.g., by month or by product).

This project will help me practice data manipulation techniques, draw insights from raw data, and refine my data analysis skills.