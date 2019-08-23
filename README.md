# A Multiple Variable Regression Model to predict public high schools graduation rates in NYC (2014) based on NYC Open Data
Contributors: Jay KIM and Fabrice MESIDOR
August 2019

## Objective:
Identify factors that can predict NYC public high school graduation rates.

## Questions:
 * Do demographics of a school impact student graduation rates?  If so, which attributes (gender, ethnicity, new English Learner, etc.) ?
 * Similarly, can factors pertaining to school quality or individual student achievements help predict graduation rates?

## Hypothesis:
The high rate of graduation in a school is not dependent of any factors related to the school or the students.

## Datasets and Variables:
## Sources
 * Data extracted from NYC Open Data (https://opendata.cityofnewyork.us/) in csv format, cleaned and treated using python (pandas)
 * Disclaimer: NYC Open Data format has inconsistencies (i.e., results are only as good as its source data)

## Data
 * 420 observations - each observation represents a school. (3 primary tables)

## Target Variable
 * High school graduation rate (% - continuous)

## Independent variables (40 after filtering)
 * Classified between ethnicity - language proficiency - gender - SAT - achievement scores

## Empirical Approach
 * Transformation of target variables to consider success 
(graduation rate ≥ 50%)
 * Distribution approximates a normal distribution after change
 * It also helped to remove data that would create biases in our models

## Empirical Approach (Suite of Variables and Tools)
 * Relationship between target variable and potential explanatory variables
 * 2 main variables have noticeably high correlation rates: Student Achievement Scores and Student Attendance Rate

## MySQL Database schema with movies collected
![mainsqltable](Images/MainDB_Table_Head.png "Main SQL Table")
C
