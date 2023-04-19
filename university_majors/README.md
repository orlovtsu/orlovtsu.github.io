# Project: "STUDENTS AND CHOOSING MAJORS" 

Authors:
1. [Sergey Orlov](https://www.linkedin.com/in/orlovtsu/)
2. [Shrivarshini Balaji](https://www.linkedin.com/in/shrivarshini-balaji-999551188/)

## Introduction

Major is a specific area of study in which a student chooses to specialize. Popular disciplines for college majors include business, health, engineering and biology. The importance of your major depends on the industry you want to work in. When students start college, it can be difficult for students to find their focus, not everybody is certain about what they want to major in. 

However, most students know they want a good-paying and secure job. This is why they are willing to make the investment of time and money to go to college.
A degree can open up unexpected And exciting opportunities and pathways that are more attractive, having perks such as a better work environment, retirement health insurance, paid time off, bonuses, stock options, wellness and benefits, continuing education as well as other memberships. There’s no doubt choosing a major is a big decision and one that many students agonize over.

You might be wondering, why is choosing major important anyway?. Don't plenty of students go in undecided or switch their initial majors and still figure it out?. It’s a sad fact that even though more students are going to college than ever, many of them are not making  it across the finish line and earn their bachelor's degree.

Here are the 3 most common reasons why students dropout, fail out or transferred out of college.
   1. They get discouraged after flipping repeatedly from major to major.

   2. They take classes that don't fit their unique aptitudes, skill sets and strengths.
   3. They feel overwhelmed by the combination of taking coursers, adjusting to the college life, choosing college major depending on the employment rate, the unemployment rate, the popularity of the major etc.

Our mission is to help school students find their passion and choose majors, make the task of getting information about college degrees easy. Choosing right major’s according to a person’s skill and knowledge will help make the society a better place to live.

## Guiding questions

Our guiding questions are based on the questions a student will get when they are choosing a major for their college degree. Even high school students are feeling overwhelmed while thinking about what major they are going to choose. 

Many are also very uncertain about whether what they have chosen has a scope to shine in near future? To bring solutions to all these questions that rises in a student’s mind we have formed a set of guiding questions which we will find answer with the help of python graph plotting’s.

  1. How does Employee’s Salary is distributed depending on their university major?

  2. What major should be chosen to find a job and maximise a salary in the future?

  3. Distribution of men and women salaries and opportunities to find jobs depending on their majors?

  4. Difference in job opportunities between graduate and non graduate employees?

  5. What are the tendencies for the major's popularity in recent graduates compared to total data?

## Packages

Our team has made use of Python packages approved by the professor for the purpose of this project. These packages help assist in importing modules that will aid in the analysis of the chosen data set.  Below is a detailed explanation of how we have utilised each package that is imported in the code-block below this cell.

### Math
Python has a built-in module that can be used for mathematical tasks.

### Random
Python random module is an in-built module which is used to generate random numbers.

### Numpy
It is a library that helps us handle large and multidimensional arrays and matrices. It provides a large collection of powerful methods to do multiple operations.

### Pandas
It is an open source library that is made mainly for working with relational or labelled data easily. It provides various data structures and operations for manipulating numerical data and time series.

### Matplotlib
It’s a comprehensive library for creating static, animated and interactive visualisations in python.
statistics

### plotly.express as px
Plotly Express is a high-level interface to Plotly that operates on various types of data and produces easy-to-style. It has a function called px.line that creates a line plot using data points as vertices of a polyline mark in 2D space

### plotly.graph_objects as go
The plotly.graph_objects module (typically imported as go) contains an automatically-generated hierarchy of Python classes which represent non-leaf nodes in this figure. The term "graph objects" refers to instances of these classes.

### kaleido
Kaleido is a cross-platform library for generating static images (e.g. png, svg, pdf, etc.) for web-based visualization libraries, with a particular focus on eliminating external dependencies.

## Information on DataSet:
For our project we use data from the dataset “College Majors and their Graduates” collected from Kaggle “College Majors and their Graduates”.
This dataset contains a comprehensive selection of lavish data and processing scripts behind the articles, graphics, and interactive experiences generated by FiveThirtyEight. 

### License:
All this data is under the Creative Commons Attribution 4.0 International License and MIT License. The last update of the dataset was in November of 2022. 

## Step 1. Data cleaning

For the research with guiding questions two data tables have been chosen:
### Grad-students.csv columns
* Major_code: The code associated with the major. (Integer)  
* Major_code: The code associated with the major. (Integer)  
* Major_category: The category of the major. (String)  
* Grad_total: The total number of graduates from the major. (Integer)  
* Grad_sample_size: The sample size of graduates from the major. (Integer)  
* Grad_employed: The number of graduates employed. (Integer)  
* Grad_full_time_year_round: The number of graduates employed full-time
* year-round. (Integer)  
* Grad_unemployed: The number of graduates unemployed. (Integer)  
* Grad_unemployment_rate: The unemployment rate of graduates. (Float)  
* Grad_median: The median salary of graduates. (Integer)  
* Grad_P25: The 25th percentile salary of graduates. (Integer)  
* Grad_P75: The 75th percentile salary of graduates. (Integer)  
* Nongrad_total: The total number of non-graduates from the major. (Integer)  
* Nongrad_employed: The number of non-graduates employed. (Integer)  
* Nongrad_full_time_year_round: The number of non-graduates employed full-time * year-round. (Integer)  
* Nongrad_unemployed: The number of non-graduates unemployed. (Integer)  
* Nongrad_unemployment_rate: The unemployment rate of non-graduates. (Float)  
* Nongrad_median: The median salary of non-graduates. (Integer)  
* Nongrad_P25: The 25th percentile salary of non-graduates. (Integer)  
* Nongrad_P75: The 75th percentile salary of non-graduates. (Integer)  
* Grad_share: The share of graduates in the major. (Float)  
* Grad_premium: The difference between the median salary of graduates and non-graduates. (Integer) 

### Rrecent-grads.csv columns
* Major_code: The code associated with the major. (Integer)  
* Major_code: The code associated with the major. (Integer)  
* Major_category: The category of the major. (String)  
* Total: The total number of students in the major. (Integer)  
* Employed: The number of employed graduates from the major. (Integer)  
* Unemployed: The number of unemployed graduates from the major. (Integer)  
* Unemployment_rate: The unemployment rate of graduates from the major. (Float) 
* Median: The median salary of graduates from the major. (Integer)  
* P25th: The 25th percentile salary of graduates from the major. (Integer)  
* P75th: The 75th percentile salary of graduates from the major. (Integer)  
* Rank: The rank of the major in terms of popularity. (Integer)  
* Sample_size: The sample size of graduates from the major. (Integer)  
* Men: The number of male students in the major. (Integer)  
* women: The number of female students in the major. (Integer)  
* ShareWomen: The percentage of female students in the major. (Float)  
* Full_time: The number of graduates employed full-time. (Integer)  
* Part_time: The number of graduates employed part-time. (Integer)  
* Full_time_year_round: The number of graduates employed full-time year-round. (Integer)  
* College_jobs: The number of college jobs held by graduates from the major. (Integer)  
* Non_college_jobs: The number of non-college jobs held by graduates from the major. (Integer)  
* Low_wage_jobs: The number of low-wage jobs held by graduates from the major. (Integer)  

## Results

The total number of majors displayed in dataset is 172, but the distribution between the engineering, scientific or humanitarian majors is not uniform.

![Distribution of majors by category](/university_majors/images/fig0)
We have done a number of functions on the dataset such as Checking for NAs,Checking for Duplicates,Ensuring that the  entire dataset has consistent Formatting.
