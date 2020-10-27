---
layout: post
title: SQL Practice Question 2
---
## Problem Statement
Query the NAME field for all American cities in the CITY table with populations larger than 120000. The CountryCode for America is USA.     

The CITY table is described as follows:            

![image db1]({{site.baseurl}}/assets/images/sql1.jpg)

## My Solution
{% highlight sql %}
SELECT name from CITY where population>120000 and countrycode='USA';
{% endhighlight %}

## Link to practice on hacker rank
[Easy Hacker Rank - Revising the Select Query II](https://www.hackerrank.com/contests/cs5200-sql-fe-1/challenges/revising-the-select-query-2)

## Reference to study material
[SQL Select Reference](https://www.w3schools.com/sql/sql_select.asp)
