# Sales Data Analysis Project

Python Pandas and Matplotlib were used to analyze and answer business questions based on 12 months of sales data. The dataset contains hundreds of thousands of electronics store purchases, including information on month, product type, cost, purchase address, and more.

## Data Cleaning

The analysis began with **data cleaning**, which involved several key steps:

- Dropping missing values from the DataFrame
- Removing rows based on specific conditions
- Converting column types using methods such as `to_numeric`, `to_datetime`, and `astype`

## Data Exploration

After the dataset was cleaned, the **data exploration** phase addressed five high-level business questions:

1. Determining the best month for sales and the total revenue earned in that month
2. Identifying the city with the highest product sales
3. Finding the optimal time to display advertisements to maximize the likelihood of customer purchases
4. Discovering which products are most often sold together
5. Identifying the top-selling product and analyzing reasons for its popularity

## Methods and Techniques

To answer these questions, various Pandas and Matplotlib methods were employed, including:

- Concatenating multiple CSV files into a single DataFrame using `pd.concat`
- Adding and transforming columns
- Parsing strings within cells to create new columns using `.str` methods
- Applying custom functions with `.apply()`
- Performing aggregation using `groupby`
- Visualizing results with bar charts and line graphs
- Properly labeling graphs for clarity
