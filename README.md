# Yajing's Portfolio
<a href="https://www.linkedin.com/in/liyajing/"><img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="3%" height="3%" /></a>

# Projects

## [Project 1: Retail business analysis | Power BI](https://github.com/Yajinglee/My_Portfolio_Website/raw/main/AdventureWorks_Report.pbix)

#### Project description:

The project 

- Connected data and built a relational model from 6 dimensional tables and 2 fact tables.
- Transformed data, created columns and measures with Query Editor and DAX calculation.
- Built interactive reports to visualize sales performance with slicers, KPIs, drilldown, and various charts.

#### Data model
![](/images/Data_model.png)

#### Executive summary

![](/images/Executive_summary.png)

#### Product detail
![](/images/Product_detail.png)

#### Customer Detail
![](/images/Customer_detail.png)


## [Project 2: Web Scraping GoodReads.com & Built book selection dashboard | Python, Tableau](https://github.com/Yajinglee/Web-Scraping-Project)

#### Project description:

The project was aimed to scrape all the books that won the Choice Awarded on GoodRead.com and build a book selection dashboard for book lovers to choose the books and authors by awards, year, and ratings for their next reading.

#### Project details:

- Retrieved 4000+ awarded book information from the website and saved to two csv files containing awards and book details using Beautiful Soup, Selenium, and pandas.
- Replaced values, split/added/renamed/dropped columns, and dropped duplicated values using pandas.
- Explored awarded books and authors through data manipulation and visualization using pandas, matplotlib, and word cloud.
- Built interactive dashboard to filter popular books and authors by year and award using Tableau.

#### Awarded books dataframe
The awarded books dataframe 
![Awarded books](/images/Awarded_Books.png)

#### Book details 

![Book details](/images/Book_Details.png)

#### Word cloud (Python wordcloud)

![Word Cloud](/images/Best_fantacy_books.png)



#### [Tableau dashboard](https://public.tableau.com/app/profile/yajing.li/viz/GoodReadsAwardedBooks/Dashboard?publish=yes)

Top Books and Authors winning the 'Best fantasy books' award with rating above 4.5 in 2022

![Top Books and Authors winning the 'Best fantasy books' award with rating above 4.5 in 2022
](/images/Dashboard.png)

<hr>


<hr>

## [Project 3: Home credit default risk prediciton | Machine Learning, Python](https://github.com/Yajinglee/Home-credit-default-risk-predict/blob/main/home-credit-default-risk-predict.ipynb)

- Transformed categorical variables into dummy variables using label encoding and one-hot encoding. 
- Checked missing records, anomalies, and correlations, and explored data through hist chart, KDE plot, and heatmap. 
- Used polynomial features and domain knowledge to create new features. 
- Implemented and compared Logistic Regression(baseline) and Decision Tree classification models


<hr>


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
