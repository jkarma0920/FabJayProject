# A Multiple Variable Regression Model to predict public high schools graduation rates in NYC (2014) based on NYC Open Data
Contributors: Jay KIM and Fabrice MESIDOR
August 2019

## Objective:
Identify factors that can help predict NYC public high school graduation rates.

## Questions:
 * Do demographics of a school impact student graduation rates?  If so, which attributes (gender, ethnicity, new English Learner, etc.) ?
 * Similarly, can factors pertaining to school quality or individual student achievements help predict graduation rates?

## Hypothesis:
The high rate of graduation in a school is not dependent on a discernible set of predictive factors related to the school or the students, at least on the surface.

## Sources
 * Data extracted from NYC Open Data (https://opendata.cityofnewyork.us/) in csv format, cleaned and treated using python (pandas)
 * Disclaimer: NYC Open Data format has inconsistencies (i.e., results are only as good as its source data)

## Datasets:
 For the 2014-2015 School Year:
 1) Graduation Rates (by individual schools), with tables for:
 * All students
 * by ELL (English Language Learner) classification
 * by SWD (Student with Disabilities) classification
 * by Ethnicity
 * by Gender
 * by Poverty classification
 2) High School Quality Report, with tables for:
 * Summary of Results
 * Student Achievement Breakdown

## Data
 * 420 observations - each observation represents a school.

## Target Variable
 * High school graduation rate (% - continuous)

## Independent variables (40 after filtering)
 * Examples of categories: ethnicity - language proficiency - gender - SAT - achievement scores

## Empirical Approach
![After Removing_Outliers](Images/Before_After.jpg "Removed Outliers")
 * Transformation of target variables to consider success 
(graduation rate ≥ 50%)
 * Distribution approximates a normal distribution after change
 * It also helped to remove data that would create biases in our models

## Empirical Approach (Out of a Suite of 39 Variables)
 * Relationship between target variable and potential explanatory variables
 * 2 main variables have noticeably high correlation rates: Student Achievement Scores and Student Attendance Rate



