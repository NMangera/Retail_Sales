# Retail_Sales

This project uses Matplotlib & Pandas to analyze 12 months of store sales data. The dataset contains thousands of transactions at an electronics store broken down by month, product type, cost, purchase address, etc.


We start with data wrangling, where tasks include:

1. Dropping missing values 
2. Filtering the data based on a condition
3. Change the data type of columns 

Once the data is cleaned, the notebook moves onto data exploration. In this section 5 high level business questions are answered. They are:

1. What was the best month for sales? How much was earned that month?
2. What city sold the most product?
3. What time should we display advertisemens to maximize the likelihood of customer’s buying product?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?

To answer these questions different pandas & matplotlib methods are applied. These include:

a) Concatenating multiple csvs together to create a new DataFrame (pd.concat)

b) Adding columns

c) Parsing cells as strings to make new columns (.str)

d) Using the .apply() method

e) Using groupby to perform aggregate analysis

f) Plotting bar charts and lines graphs to visualize our results

g) Labeling our graphs
