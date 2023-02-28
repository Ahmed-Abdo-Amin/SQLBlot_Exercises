# [<img src="https://sqlbolt.com/cs/images/favicon.png"/> SQLBolt](https://sqlbolt.com/)

## SQL Lesson 8: A short note on NULLs
This exercise will be a sort of review of the last few lessons. We're using the same Employees and Buildings table from the last lesson, but we've hired a few more people, who haven't yet been assigned a building.

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
Engineer|Yancy I.||0
Artist|Oliver P.||0

## Exercise 7 — Tasks
1. Find the name and role of all employees who have not been assigned to a building
2. Find the names of the buildings that hold no employees

[Click here to see the details](https://sqlbolt.com/lesson/select_queries_with_nulls)

## Solution:
![EX8](./Ex8.gif)