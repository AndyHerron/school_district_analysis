# PyCitySchools

## Overview of Project
We have been provided with two sets of data on schools and students in a particular school district.  Using Python and Pandas, we were tasked with creating a variety of reports to present to the school leadership.
After initially going through the data, it was determined that the math and reading scores for ninth graders at Thomas High School were not usable.  The calculations and reports were then redone to omit the suspect data.

## Resources
* Data Source: schools_complete.csv and students_complete.csv
* Software: Python 3.8.8, Jupyter Notebook

## Results
* How is the district summary affected? Removing the 9th grade data from Thomas HS did slightly improve the percentages of students passing for all three categories - Math, Reading and Overall.

* How is the school summary affected? Obviously the other schools results did not change, but Thomas High School percentages improved dramatically.

* How does replacing the ninth graders math and reading scores affect Thomas High School's performance relative to the other schools? It moved them up to the second-best performing school in the whole district.

* How does replacing the ninth-grade scores affect the following:
	1. Math and reading scores by grade - 
	2. scores by school spending
	3. scores by school size
	4. scores by school type


## Challenge Summary
The scores for the ninth-graders at Thomas High School were obviously poor.  Removing that data dramatically improved the percentages for that individual school, and marginally improved the overall percentages for the district.
The district-wide % of students who passed math rose from 73.6% to 74.8%.  The % passing reading increased from 84.5% to 85.7%.  The percentage of students who were passing in both categories improved from 63.7% to 64.9%.
