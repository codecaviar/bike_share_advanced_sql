<img src="https://raw.githubusercontent.com/codecaviar/digital_asset_management/master/assets/bingyune-and-company-logo-6400x3600.png" align="left" width="200" height="auto">

<br/><br/><br/><br/>

----------

# Bike Share for All: Ultimate Guide to Advanced SQL

**Code Caviar Story**: https://www.bingyune.com/blog/bike-share-advanced-sql

## Project Overview

Databases and languages that are used to communicate with databases, like SQL, can handle significantly more data than spreadsheets and manage the back-end of most modern-day web applications. While SQL is not necessarily all that cool and new compared to other programming languages, it is an important language to learn if you want to do any work involving data. For those who have dabbled with SQL, you probably already know that it is pretty easy to write basic queries: SELECT column, FROM table, and WHERE condition - that's what makes it so great! Yet you may still feel you are not taking full advantage of SQL's expressive power. The key steps to using advanced SQL: learn the ins and outs of data types, know best practices to optimize performance, and understand how to structure a database from scratch. You'll also need a variety of new statements and clauses to explore and analyze data at scale. Even if you aren't planning to move over to the data team any time soon, it's worth taking the time to learn a bit of advanced SQL. At a minimum, you'll gain a better understanding of building and interacting with databases, which will make you more well rounded. And that's useful in its own way.

**The goal of this project is** to provide an Ultimate Guide to the advanced hacking skills needed to explore and analyze data at scale with SQL. The project makes use of the [Bay Area Bike Share](https://mtc.ca.gov/our-work/operate-coordinate/traveler-services/bay-area-bike-share) data sourced from [Kaggle](https://www.kaggle.com/benhamner/sf-bay-area-bike-share). The original dataset contains data for 70 stations (where users can pickup or return bikes), about 71M status updates (number of bikes and docks available for given station), about 670k trips (individual bike trips), and about 3k weather forecasts (for a specific day for a certain zip code).

## Summary:

A data type is an attribute that specifies the type of data for an object in SQL. For example, the `INTEGER` data type only stores whole numbers - no decimals. On the other hand, the `REAL` or `DOUBLE PRECISION` data types can store many significant decimal digits. Each column, variable, and expression has a related data type in SQL.

Subqueries (also known as inner queries or nested queries) are a tool for performing operations in multiple steps. How this works: When you run one query and get a result (with an inner query), you can feed it to another query (to the outer query). Subqueries are a common requirement when dealing with layered aggregations, filtering, and creating temporary tables with calculated or categorized columns.

A common table expression (CTE) is defined outside of the above clauses using the `WITH` operator, making it a convenient way to manage more complicated queries. CTE is used for creating a temporary result set that can be referenced within the following clauses: `SELECT`, `INSERT`, `UPDATE`, or `DELETE`.

A window function is an SQL function where the input values are taken from a "window" of one or more rows in the results set of a `SELECT` statement. Window functions are distinguished from other SQL functions by the presence of an `OVER` clause.

Similar to the [Complete Guide to Intermediate SQL](https://www.bingyune.com/blog/bike-share-intermediate-sql), many of the practice problems in this guide can be solved in one or two ways with the skills you've learned so far. Keep in mind that the answers to practice problems should be used as a reference, but are by no means the only ways of answering the questions.

## Getting Started

First, cloning the git repository and installing the provided packages will help you get a copy of the project up and running on your local machine. The project was created using Jupyter Notebook (.ipynb) and the packages were managed using the Anaconda platform.

```
git clone https://github.com/codecaviar/bike_share_intermediate_sql.git
conda env create -f environment.yml
```

File Description:
* environment.yml - packages used to perform this analysis
* notebook_bike_share_advanced_sql.ipynb - Jupyter Notebook for this project including code examples and explanations
* solutions_bike_share_advanced_sql.ipynb - Jupyter Notebook for this project including solutions to practice problems

## Authors

- **BingYune Chen** - [LinkedIn](https://www.linkedin.com/in/bingyune-chen/)
- **BingYune & Co** - [GitHub](https://github.com/codecaviar)

## License

The project is licensed under the GNU General Public License v3.0 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

The project referenced the following resources:
* https://mode.com/sql-tutorial/
* https://www.w3schools.com/sql/
* https://www.sqlitetutorial.net/

----------
The Code Caviar is a digital magazine about data science and analytics that dives deep into key topics, so you can experience the thrill of solving at scale.
