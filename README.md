# Yajing's Portfolio
<a href="https://www.linkedin.com/in/liyajing/"><img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="3%" height="3%" /></a>

## [Project 1: Retail business analysis | Power BI](https://github.com/Yajinglee/My_Portfolio_Website/raw/main/AdventureWorks_Report.pbix)

### Project Description:

This project was aimed to deliver a business intelligence solution and gain actionable insights from 8 csv files containing products, customers, sales and returns data of a retail business named Adventure Works.

### Project Details:

- Loaded the data and created data model using snowflake schema from 6 dimensional tables and 2 fact tables.
- Transformed data, created columns and measures with Query Editor and DAX calculation.
- Built interactive reports to visualize sales performance with slicers, KPIs, drilldown, and various charts including tree map, line and bar chart, donut chart and gauge chart. 


### Data Model:

- AW_Sales and AW_Returns are the 2 facts tables.
- Customer, Territory, Calendar, Product, Product Category, Product Subcategory are the 6 dimension tables.

![](/images/Data_model.png)

### Dashboards:

#### 1. Executive Summary:

The executive summary dashboard provided an overview of the sales performance across difference countries from 2015 to June 2017. 

#### Executive Summary of 2015

![](/images/2015_executive_summary.png)
#### Executive Summary of 2016

![](/images/2016_executive_summary.png)

#### Executive Summary of 2017

![](/images/2017_executive_summary.png)

#### Insights:

- Bike was the only product Adventure Works sold in 2015. Starting from June 2016, it introduced new products including accessories and clothes, which could be one of the major reasons of the profit increase by 53% comparing from 2015 to 2016.

- In 2016, bike is the most ordered product category in Australia and least ordered product category in Canada, and the possible reason behind this could be that the weather condition in Australia is more suitable for biking all year round, whereas in Canada, only few months in a year is good for outdoor biking.

- The United States and Australia are the top 2 countries that brought the most profit, and there was also a 100% increase in profit in countries in Europe from 2015 to 2016.

- Total product sold in 2017 already exceed the amount 2016 by 25% even thought there were only 6 months data in 2017. The profit in 2017 is almost equal to it in 2016. So, Adventure Works had a huge growth in 2017.

- Looking at the products, Water bottle is the product that Adventure Works sold for the most amount, and all the mountain bikes are the top revenue generators for Adventure Works.

#### 2. Product Details:

The product detail dashboard provided the detailed sales information about one specific product. The product name can be selected on the executive summary dashboard, and drilled through to the product detail dashboard for more information. 

I'll take mountain bike 200 black 42, which is one of the most profitable products, as an example. I would like to see how the sales performance looks like comparing with June 2016 and June 2017 in Australia.

#### Mountain bike sales detail in June 2016 in Australia

![](/images/2016_june_mountain_bike.png)

#### Mountain bike sales detail in June 2017 in Australia

![](/images/2017_june_mountain_bike.png)

#### Insights:

- Both revenue and number of orders of mountain bike 200 black 42 in 2017 exceeded 2016 as well as the target, with an increase of 62.5% with both measures.

- There wasn't a noticeable increase in the number of returns despite the increase in the number of orders. 

- Number of bikes sold in June of 2016 and 2017 both showed the sample pattern which is that the second week of the month having the greatest number of bikes sold.

#### 3. Customer Details:

The customer details dashboard visualized the customers data including age group, occupation, income level, total order placed and total revenue generated.

The below screenshot showed the customer who placed order in 2016.

![](/images/customer_details.png)


The below screenshot showed the customer who placed order in 2016 with average income.

![](/images/customer_avg_income.png)


The below screenshot showed the customer who placed order in 2016 with low income.

![](/images/customer_low_income.png)


#### Insights:

- The majority customers are of average income and low income. And customers of average income bring more profit than those are of low income. The average amount they spend in one order is higher.

- Accessories is the product category that has the most orders, followed by bikes and clothes.

## [Project 2: Web Scraping GoodReads.com & Built book selection dashboard | Python, Tableau](https://github.com/Yajinglee/Web-Scraping-Project)

#### Project Description:

The project was aimed to scrape all the books that won the Choice Awarded on GoodRead.com and build a book selection dashboard for book lovers to choose the books and authors by awards, year, and ratings for their next reading.

#### Project Details:

- Retrieved 4000+ awarded book information from the website and saved to two csv files containing awards and book details using Beautiful Soup, Selenium, and pandas.
- Replaced values, split/added/renamed/dropped columns, and dropped duplicated values using pandas.
- Explored awarded books and authors through data manipulation and visualization using pandas, matplotlib, and word cloud.
- Built interactive dashboard to filter popular books and authors by year and award using Tableau.

#### Dataframe

- Awarded books dataframe

![Awarded books](/images/Awarded_Books.png)

- Book details dataframe

![Book details](/images/Book_Details.png)

#### Word cloud

Python wordcloud library was used to create the word clouds. 

The screenshot below shows the books that won the 'Best fiction' award in 2011 that has ratings above 3.5.

![Word Cloud](/images/best_fiction_book_wordcloud.png)

#### [Tableau dashboard](https://public.tableau.com/app/profile/yajing.li/viz/GoodReadsAwardedBooks/Dashboard?publish=yes)

The screenshot below shows the top books and authors winning the 'Best fantasy books' award with the rating above 4.5 in 2022

![](/images/Dashboard.png)


## [Project 3: Home credit default risk prediction | Machine Learning, Python](https://github.com/Yajinglee/Home-credit-default-risk-predict/blob/main/home-credit-default-risk-predict.ipynb)

#### Project Description:

The goal of this project was to predict clients' repayment abilities for an international finance provider named Home Credit. The dataset containing 122 columns and more than 300k records.   

#### Dataset:

![](/images/Home_credit_dataset.png)

#### Project Details:

- Transformed categorical variables into dummy variables using label encoding and one-hot encoding. 
- Checked missing records, anomalies, and correlations, and explored data through hist chart, KDE plot, and heatmap. 
- Used polynomial features and domain knowledge to create new features. 
- Implemented and compared Logistic Regression(baseline) and Decision Tree classification models, measured by ROC-AUC score.


## [Project 4: Sakila DVD rental data analysis | SQL, Python(pandas, seaborn, matplotlib)](https://github.com/Yajinglee/SQL-Projects)

#### Project Description:

This project aimed to use SQL queries to explore the DVD rental dataset to gain an understanding of inventory level, consumer behavior, store sales and performance.

Dataset was connected in MySQL Workbench, and then Jupyter Notebook was set up to access data from MySQL databases by loading the SQL magic jupyter notebook extension.

#### Sakila Database Entity Relationship Diagram(ERD)

<img src="https://www.jooq.org/img/sakila.png">

#### Analysis:

#### Inventory summary:

- What's the total value of all the inventory and total inventory value of each store?
- How many film are there in each category of each store, and the total inventory count?
- How many films are there in each rating?

![](/images/Film_rating.png)

- How's the film inventory level looks like?

![](/images/Inventory_level.png)

- Which actor/actress is in the most films in store inventory?

#### Consumer behavior:

- How many days do customer usually rent?
- Do customer usually rent on weekdays or weekends?

![](/images/rental_day.png)

- What are the top films that customers rented for the longest days accumulatively, and rented for the most times?
- Among the films that rented most frequently, are they usually rented on weekday or weekends?
- What is the average rental period?
- Which genres are most popular?
- Who are identified as loyalty customers?
- Were there customers who did not return the film?
- Which actors/actresses are most popular given our rental history?

#### Store performance:

- How many stores are there and how many staff in each store?
- What's the number of transactions each month for both store?

![](/images/stores_transactions.png)

- Which store has more customer rented the film?
- Which store makes the most money?

#### Sales summary:

- What's the total revenue for the time period and for each month?

![](/images/store_sales.png)

- What's the most profitable move genres/rating?
- Do we make the most money from long or short rentals?
