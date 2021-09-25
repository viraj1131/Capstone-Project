# Capstone-Project

## Project Title: Optimizing The Business Processes of Retail and E-Commerce Platforms with Data Analytics and Machine Learning

### Business Problem: 

The retail industry has drastically changed from brick-and-mortar stores to e-commerce and has overall increased in the previous decade as the advancement of technology never stopped. We can see the online presence of a small convenience store near our homes or big size stores, on platforms like Google or social media with their dedicated sites for e-commerce. So, in the new tech world now the business owners have changed their techniques of conducting business with the help of digitalized tools and with the help of software like CRM where they can record data for billing, shipping, taxes, sales, inventory and many more. As the current world thrives on the data and almost every possible problem can be solved with data so with the help of data science business owners can make decisions and can predict their business for the near future with help of data science. It is not limited to decision making or predicting the outcomes in near future, but the data can also help us in recommending the products placement to increase sales and forecast their sales, inventory requirements, make informed marketing strategies and many more. The data can help both the retail store and e-commerce to advance their business in numerous ways. Our multiple data-oriented insights and predictions will help the business owners in decision making and planning for their business.

### Link To Project Presentation: https://www.youtube.com/watch?v=h6QEnYe__J8

### Dataset:

**Link:** https://www.strategytitan.com/blog/titanized-real-world-dataset-to-develop-your-analytics-muscle![image](https://user-images.githubusercontent.com/59807869/134786339-2ca1ccfc-6f53-45ea-8ca4-ee2bfd10e7e5.png)

**Brief Understanding Of Data:** 

There are approximately 1.60k rows and 24 columns in the dataset where each row represents the order placed by a customer which includes Profit Ratio, Discount, Customer demographics, product name, manufacturer name, etc. Apart from this, the other main features are freight bill, freight gain/loss, freight recovery, and channel from which customer has purchased the product.

### Things We Implemented in our Project:

* Market Basket Analysis to make a recommendation system for an e-commerce website and to help retail store with its product placement to increase sales.
* Customer Segmentation i.e., categorizing the customer based on RFM score to find loyal customers and to find the potential customers churn with the help of RFM Analysis.
* Sales Forecasting to understand the business direction.
* Analytical Reporting to analyze business data with the help of business intelligence dashboards and visualizations to display the businesses key performance indicators (KPIs), to assess performance measures and generate actionable insights.

### **Tools Used:** Excel, Jupyter Notebook, Python, Tableau Desktop

### Files:

1. Data file
2. Python Notebook
3. Tableau file
4. Report
5. Powerpoint Presentation

###	Steps for Running Python Notebook:

* you will need **titanized_sales___profit_data.xlsx** file. Keep this file in the same folder where you keep the python file otherwise you need to change to path location in the code where we are reading this file.
* Our Excel file has four different sheets and has been explained  in below points.
* **Titanized Sales Data** sheet is our raw data.
* **Customer ID** sheet is created by us to assign the Customer ID to different Customers by using VLOOKUP function which was required for our analysis.
* **Product ID** sheet is created by us to assign the Product ID to different Products by using VLOOKUP function which was required for our analysis.
* **Source & Credits** sheet is the authority to use this data by Strategy Titan.
* While Running RFM analysis part we have written one code for saving generated results to .CSV file which will be saved into your current python file running environment as **rfm_365.csv** but still for safe side we are attaching this file as well.
* We have commented code for reading the file when running it in Google Colab if you wish to run python file in Google Colab you just need to uncomment them  and comment jupyter notebook reading file code before running it.


### Steps for Running Tableau file:

* For running Tableau file, you will need **titanized_sales___profit_data_tableau.xlsx**  and **rfm_365.csv** files. Keep this file in the same folder where you keep the Tableau file.
* **Rfm_365.csv** is extracted from the python notebook after performing customer segmentation using RFM analysis.
* Basically, we have used 3 data sources two as mentioned in first point and third one is the joined file based upon these two files.
* If it asks for rfm_365 then locate file source **rfm_365.csv**.
* If it asks for titanized_sales___profit_data_tableau then locate file source **titanized_sales___profit_data_tableau.xlsx**. 
* we have also created a join between these 2 files if it asks you to locate them again then please locate them once more.

### **Note:** To more better understnd all the things which we did you can go through Python Notebook and Tableau file.
