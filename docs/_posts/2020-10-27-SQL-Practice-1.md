---
layout: post
title: SQL Practice Question 1
---
## Problem Statement
Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.      
The CITY table is described as follows:    

![image db1]({{site.baseurl}}/assets/images/sql1.jpg)

## My Solution
{% highlight sql %}
SELECT * from CITY where POPULATION>100000 and COUNTRYCODE='USA';
{% endhighlight %}

## Link to practice on hacker rank
[Easy Hacker Rank - Revising the Select Query I](https://www.hackerrank.com/contests/cs5200-sql-fe-1/challenges/revising-the-select-query)

## Reference to study material
[SQL Select Reference](https://www.w3schools.com/sql/sql_select.asp)
