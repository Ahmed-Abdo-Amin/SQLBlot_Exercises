# [<img src="https://sqlbolt.com/cs/images/favicon.png"/> SQLBolt](https://sqlbolt.com/)

## SQL Lesson 7: OUTER JOINs
In this exercise, you are going to be working with a new table which stores fictional data about Employees in the film studio and their assigned office Buildings. Some of the buildings are new, so they don't have any employees in them yet, but we need to find some information about them regardless.

Since our browser SQL database is somewhat limited, only the LEFT JOIN is supported in the exercise below.

## Table: Buildings
Building_name|Capacity
|-:|-:|
1e|24
1w|32
2e|16
2w|20

## Table: Employees
Role|Name|Building|Years_employed
-:|-:|-:|-:|
Engineer|Becky A.|1e|4
Engineer|Dan B.|1e|2
Engineer|Sharon F.|1e|6
Engineer|Dan M.|1e|4
Engineer|Malcom S.|1e|1
Artist|Tylar S.|2w|2
Artist|Sherman D.|2w|8
Artist|Jakob J.|2w|6
Artist|Lillia A.|2w|7
Artist|Brandon J.|2w|7
Manager|Scott K.|1e|9
Manager|Shirlee M.|1e|3
Manager|Daria O.|2w|6


## Exercise 7 — Tasks
1. Find the list of all buildings that have employees
2. Find the list of all buildings and their capacity
3. List all buildings and the distinct employee roles in each building (including empty buildings)

[Click here to see the details](https://sqlbolt.com/lesson/select_queries_with_outer_joins)

## Solution:
![EX7](./Ex7.gif)