![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | SQL Joins

<details>
  <summary>
   <h2>Learning Goals</h2>
  </summary>

  This lab allows you to practice and apply the concepts and techniques taught in class. 

  Upon completion of this lab, you will be able to:
  
- Use SQL joins to combine data from multiple tables, such as inner, outer, left, right or self-joins.

  <br>
  <hr> 

</details>

<details>
  <summary>
   <h2>Prerequisites</h2>
  </summary>

Before this starting this lab, you should have learnt about:

- SELECT, FROM, ORDER BY, LIMIT, WHERE, GROUP BY, and HAVING clauses. DISTINCT, AS keywords.
- Built-in SQL functions such as COUNT, MAX, MIN, AVG, ROUND, DATEDIFF, or DATE_FORMAT.
- Using JOIN to combine data from multiple tables.
 
  <br>
  <hr> 

</details>


## Introduction

Welcome to the SQL Joins lab!

In this lab, you will be working with the [Sakila](https://dev.mysql.com/doc/sakila/en/) database on movie rentals. Specifically, you will be practicing how to perform joins on multiple tables in SQL. Joining multiple tables is a fundamental concept in SQL, allowing you to combine data from different tables to answer complex queries.  Furthermore, you will also practice how to use aggregate functions to calculate summary statistics on your joined data.


## Challenge - Joining on multiple tables

Write SQL queries to perform the following tasks using the Sakila database:


1. List the number of films per category.
2. Retrieve the store ID, city, and country for each store.
3.  Calculate the total revenue generated by each store in dollars.
4.  Determine the average running time of films for each category.
5.  Identify the film categories with the longest average running time.
6.  Display the top 10 most frequently rented movies in descending order.
7. Determine if "Academy Dinosaur" can be rented from Store 1.

Here are some tips to help you successfully complete the lab:

***Tip 1***: This lab involves joins with multiple tables, which can be challenging. Take your time and follow the steps we discussed in class:

- Make sure you understand the relationships between the tables in the database. This will help you determine which tables to join and which columns to use in your joins.
- Identify a common column for both tables to use in the `ON` section of the join. If there isn't a common column, you may need to add another table with a common column.
- Decide which table you want to use as the left table (immediately after `FROM`) and which will be the right table (immediately after `JOIN`).
- Determine which table you want to include all records from. This will help you decide which type of `JOIN` to use. If you want all records from the first table, use a `LEFT JOIN`. If you want all records from the second table, use a `RIGHT JOIN`. If you want records from both tables only where there is a match, use an `INNER JOIN`.
- Use table aliases to make your queries easier to read and understand. This is especially important when working with multiple tables.
- Write the query

***Tip 2***: Break down the problem into smaller, more manageable parts. For example, you might start by writing a query to retrieve data from just two tables before adding additional tables to the join. Test your queries as you go, and check the output carefully to make sure it matches what you expect. This process takes time, so be patient and go step by step to build your query incrementally.

## Requirements

- Fork this repo
- Clone it to your machine


## Getting Started

Complete the challenges in this readme in a `.sql`file.

## Submission

- Upon completion, run the following commands:

```bash
git add .
git commit -m "Solved lab"
git push origin master
```

- Paste the link of your lab in Student Portal.

