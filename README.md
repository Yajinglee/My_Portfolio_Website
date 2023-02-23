# Yajing's Portfolio
<a href="https://www.linkedin.com/in/liyajing/"><img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="3%" height="3%" /></a>

## [Project 1: Retail business analysis | Power BI](https://github.com/Yajinglee/My_Portfolio_Website/raw/main/AdventureWorks_Report.pbix)

### Project description:

This project was aimed to delivered a business intelligence solution and gain actionable insights from 8 csv files containing products, customers, sales and returns of a retail business names AdventureWorks.

### Project details:

- Loaded the data and create data model using snowflack schema from 6 dimensional tables and 2 fact tables.
- Transformed data, created columns and measures with Query Editor and DAX calculation.
- Built interactive reports to visualize sales performance with slicers, KPIs, drilldown, and various charts including tree map, line and bar chart, donut chart and garge. 

### Data model:

- AW_Sales and AW_Returns are the 2 facts tables.
- Customer, Territory, Calendar, Product, Product Category, Product Subcategory are the 6 dimention tables.

![](/images/Data_model.png)

### Dashboards:

#### 1. Executive Summary:

The executive summary dashboard provided an overview of the sales performance across difference countries over 2015 to June 2017. 

#### Executive Summary of 2015

![](/images/2015_executive_summary.png)
#### Executive Summary of 2016

![](/images/2016_executive_summary.png)

#### Executive Summary of 2017

![](/images/2017_executive_summary.png)

#### Insights:

- Bike was the only product AdventureWorks sold in 2015. Starting from June 2016, it introducted new products incluidng accessories and clothes, which could be one of the major reasons of the profit increase by 53% comparing from 2015 to 2016.
- In 2016, bike is the most ordered product category in Australia and least ordered product category in Canada, and the possible reason behind this could be that the weather condition in Australia is more suitable for biking all year round, whereas in Canada, only few months in a year is good for outdoor biking.
- The United State and Australia are the top 2 countries that brought the most profit, and there was also a 100% increase in profit in countries in Europe from 2015 to 2016.
- Total product sold in 2017 already exceed the amount 2016 by 25% even thought there were only 6 months data in 2017. The profit in 2017 is almost equal to it in 2016. So, AdventureWorks had a hugh growth in 2017.
- Looking at the proudcts, Waterbottle is the product that AdventureWorks sold for the most amount, and all the mountain bikes are the top revenue generators for AdventureWorks.

#### 2. Product Details:

The product detail dashboard provided the detailed sales information about one specific product. The product name can be selected on the executive summary dashboard, and drilled through to the product detail dashborad for more inforamtion. 

I'll take mountain bike 200 black 42, which is one of the most profitable product, as an example. I would like to see how the sales performance looks like comparing with June 2016 and June 2017 in Australia.

#### Mountain bike sales detail in June 2016 in Australia

![](/images/2016_june_mountain_bike.png)

#### Mountain bike sales detail in June 2017 in Australia

![](/images/2017_june_mountain_bike.png)

Compared with the sales in 2016, the sales performance of mountain bike 200 black 42 in 2017 did not reached the goals as expected in general. 

#### 3. Customer Detail:

![](/images/Customer_detail.png)


## [Project 2: Web Scraping GoodReads.com & Built book selection dashboard | Python, Tableau](https://github.com/Yajinglee/Web-Scraping-Project)

#### Project description:

The project was aimed to scrape all the books that won the Choice Awarded on GoodRead.com and build a book selection dashboard for book lovers to choose the books and authors by awards, year, and ratings for their next reading.

#### Project details:

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

The screenshot below show the books that won the 'Best fiction' award in 2011 that has ratings above 3.5.

![Word Cloud](/images/best_fiction_book_wordcloud.png)

#### [Tableau dashboard](https://public.tableau.com/app/profile/yajing.li/viz/GoodReadsAwardedBooks/Dashboard?publish=yes)

The screenshot below shows the top books and authors winning the 'Best fantasy books' award with the rating above 4.5 in 2022

![Top Books and Authors winning the 'Best fantasy books' award with rating above 4.5 in 2022
](/images/Dashboard.png)


## [Project 3: Home credit default risk prediciton | Machine Learning, Python](https://github.com/Yajinglee/Home-credit-default-risk-predict/blob/main/home-credit-default-risk-predict.ipynb)

- Transformed categorical variables into dummy variables using label encoding and one-hot encoding. 
- Checked missing records, anomalies, and correlations, and explored data through hist chart, KDE plot, and heatmap. 
- Used polynomial features and domain knowledge to create new features. 
- Implemented and compared Logistic Regression(baseline) and Decision Tree classification models


## [Project 4: Invenroty/Sales/Customer behavior analysis | SQL ](https://github.com/Yajinglee/SQL-Projects)

This project aims to demonstrate the use of SQL to answer hypothetical sales and marketing questions about a DVD rental store with a MySQL database named Sakila.

### Problem Description

##### Inventory summary:

- What's the total value of all the inventory and total inventory value of each store?
- How many film are there in each category of each store, and the total inventory count?
- How many films are there in each rating?
- How's the film inventory level looks like?
- Which actor/actress is in the most films in store inventory?

##### Consumer behavior:

- How many days do customer usually rent?
- Do customer usually rent on weekdays or weekends?
- What are the top films that customers rented for the longest days accumulatively, and rented for the most times?
- Among the films that rented most frequently, are they usually rented on weekday or weekends?
- What is the average rental period?
- Which genres are most popular?
- Who are identified as loyalty customers?
- Were there customers who did not return the film?
- Which actors/actresses are most popular given our rental history?

##### Store performance:

- How many stores are there and how many staff in each store?
- What's the number of transaction each month for both store?
- Which store has more customer rented the film?
- Which store makes the most money?

##### Sales summary:

- What's the total revenue for the time period and for each month?
- What's the most profitable move genres/rating?
- Do we make the most money from long or short rentals?
