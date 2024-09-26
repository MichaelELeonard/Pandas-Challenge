<img src="Pics/Header.png" width="696" height="433">

# Pandas-Challenge
Link to code - https://github.com/MichaelELeonard/pandas-challenge/blob/main/PyCitySchools/PyCitySchools_working_v2.ipynb
## Background Scenario 
For this challenge I have been placed in the role of Chief Data Scientist for my city's school district. In this capacity, I'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, I've been asked to analyze the district-wide standardized test results. I’ve been given access to every student’s math and reading scores, as well as various information regarding the schools they attend. My task is to aggregate the data to showcase trends in school performance.

## District Summary
A high-level snapshot of the district's key metrics includes the following:
* Total number of unique schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

<img src="Pics/District Summary.png" width="1003" height="72">

## School Summary
A school summary was established highlighting key metrics for each school.  These metrics include:
* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

<img src="Pics/School Summary.png" width="1303" height="420">

## Results

### District Highest-Performing Schools (by % Overall Passing)

<img src="Pics/Highest-Performing Schools.png" width="1300" height="185">

### District Lowest-Performing Schools (by % Overall Passing)

<img src="Pics/Lowest-Performing Schools.png" width="1307" height="183">

### Math Scores Per School by Grade

<img src="Pics/Math Scores by Grade.png" width="479" height="393">

### Reading Scores Per School by Grade

<img src="Pics/Reading Scores by Grade.png" width="481" height="393">

### Per Student Spending Range by School

<img src="Pics/Scores by School Spending by Student.png" width="1516" height="392">

### Scores Per School Size

<img src="Pics/School Size Breakdown.png" width="841" height="141">

### Scores Per School Type

<img src="Pics/School Type Breakdown.png" width="789" height="125">

## Analysis

When examining the results from the data analysis of the PyCitySchools District High Schools, some interesting results can be observed.  These results include:
* The district wide passing rate for math was 74.98%, while the district wide passing rate for reading was 85.80%.  The rate for students passing both math and reading was 65.17%.
* The analysis examined School Type (District/Charter), total school budget, dollar amount invested per student, and the passing rates for each institution.  This analysis seemed to show a direct correlation between student population and scholastic success.
* The results were categorized into the top five and top five lowest performing schools in the district. Notable trends include:
  * The five highest performing schools were all Charter schools while all the five lowest performing schools were all District schools.  
  * The high performing Charters schools spent less dollars per student than the lowest performing District schools, showing that Charter schools were able to achieve higher scholastic performance at an overall reduced cost.
  * Charter schools had significantly lower student populations, frequently being half of their District school counterparts.
  * When examining the reading and math scores per school for 9th-12th graders, student scores remained consistent across the four years.
  * When examining statistics spanning school type, student population, school financials and test scores, higher test scores seem to correlate with a lower student population vs dollar spending at both the institution and student level.
  * The correlation between scholastic success and student population can by clearly observed when comparing schools by size, with institutions with student populations of 1000-2000 students passing both reading and math tests at a rate of 90.62% vs institutions with a student population between 2000-5000 passing both reading and math tests at a rate of 58.28%.   
