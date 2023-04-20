# [Sergey Orlov](https://www.linkedin.com/in/orlovtsu/)


Hello everyone! Welcome to my portfolio. I am going to explain interesting projects which I do as a Data Scientist.
Previously, I have got experience in many different fields from scientific programming to product management, and now I dive deep into Data Science and am happy to invite you to this fascinating world with me. 

If you have any questions about these projects or any additions, please, fill free to connect with me via [LinkedIn](https://www.linkedin.com/in/orlovtsu/), email or phone.


**Table of Content**
- [Project "Students and choosing majors"](#university_majors) <br />
-- [Part 1. Analysis using Data Visualization](#university_majors_visualization) <br />
-- [Part 2. Statistical Data Analysis](#university_majors_stat) <br />


## Project "Students and choosing majors" <a name="university_majors"></a>

### Overview
The study project which was done for the courses "Working with Data and Visualization" and "Statistical Data Analysis" during my Master of Data Science and Analytics program at the University of Calgary. This project was made in group, the links to my classmates are made in the full reports. 

I spent a lot of my life time working at the university and found that many students do not understand how to make choices for their study major. But, in my opinion, the major choice is critically important for the young human future and can easily make future specialists happy or unhappy. This is why we decided to study distribution of majors, features and future opportunities for students. 

For our project we use data from the dataset “College Majors and their Graduates” collected from Kaggle. This dataset contains a comprehensive selection of lavish data and processing scripts behind the articles, graphics, and interactive experiences generated by FiveThirtyEight.

### Part 1. Analysis using Data Visualization <a name="university_majors_visualization"></a> [[report](https://github.com/orlovtsu/portfolio/blob/main/university_majors/)]

This part of project is focused on visualization tasks

What was done:
- the distribution of majors by category was described using piechart from plotly
- the distribution of graduate salaries and unemployment rate depending on major category, gender was investigated using boxplots describing 20th and 75th percentiles, medians and variance distributions.
- the categories with top 20 salaries and lowest unemployment rates were found using the scatterplot visualizations with plotly and matplotlib

Technology stack:
- Python
- matplotlib, plotly
- math, statistics
- pandas, numpy                                    

### Part 2. Statistical Data Analysis<a name="university_majors_stat"></a> [[report](https://github.com/orlovtsu/portfolio/blob/main/university_majors_stat/)]

The second part of this project is Statistical Data Analysis for the same dataset. 

What was done:
- Bootstrap analysis for each major median salary and confidence intervals
- Normality and homoscedasticity analysis for the distributions
- Difference analysis for each major category median salary
- Correlation analysis between women proportion and median salary
- Linear regression modeling 

Technology stack:
- R
- ggplot2, dplyr, scales, mosaic
- gridExtra, grid
