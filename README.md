<img src="Pics/Header.png" width="696" height="433">

# Pandas-Challenge
##### Link to code - https://github.com/MichaelELeonard/pandas-challenge/blob/main/PyCitySchools/PyCitySchools_working_v2.ipynb
## Background Scenario 
For this challenge I have been placed in the role of Chief Data Scientist for my city's school district. In this capacity, I'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.
As a first task, I've been asked to analyze the district-wide standardized test results. I’ve been given access to every student's math and reading scores, as well as various information on the schools they attend. My task is to aggregate the data to showcase obvious trends in school performance.

## District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Include the following:
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
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
Include the following:
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

### Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.
Save the results in a DataFrame called "top_schools".

<img src="Pics/Highest-Performing Schools.png" width="1300" height="185">

### Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
Save the results in a DataFrame called "bottom_schools".

<img src="Pics/Lowest-Performing Schools.png" width="1307" height="183">

### Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

<img src="Pics/Math Scores by Grade.png" width="479" height="393">

### Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

<img src="Pics/Reading Scores by Grade.png" width="481" height="393">

### Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).
Use the code provided below to create four bins with reasonable cutoff values to group school spending.


<img src="Pics/School Summary.png" width="1303" height="420">
<img src="Pics/School Size Breakdown.png" width="841" height="141">
<img src="Pics/School Type Breakdown.png" width="789" height="125">

## Results

When examining the results from the data analysis of the PyCitySchools District High Schools, some interesting results can be seen.  These results include:
* District statistics were tabulated looking at students from all 15 PyCitySchools High Schools examining passing rates for reading and math (>70%).  The district wide passing rate for math was 74.98% while the district wide passing rate for reading was 85.80%.  The rate for students passing both math and reading was 65.17%.
* The analysis was then broken down by high school outlining the School Type (District/Charter), the total school budget, the dollar amount invested per student, and the passing rates for each institution.  This analysis seemed to show a direct correlation between student population and scholastic success.
* The results were categorized into the top five and top five lowest performing schools in the district. Notable trends include:
   * All the five highest performing schools were Charter schools while all the five lowest performing schools were District schools.  
   * All the high performing Charters schools spent less dollars per student than the lowest performing District schools, showing that charter schools were able to achieve higher scholastic performance at an overall reduced cost.
   * All the Charter schools had significantly lower student populations, frequently being half of their District school counterparts.
   * When examining the reading and math scores per school for 9th-12th graders, the scores remained consistent across the four years.
   * When examining statistics spanning school type, student population, school financials and test scores, higher test scores seem to correlate with a lower student population vs dollar spending at both the institution and student level.
   * The correlation between scholastic success and student population can by clearly observed when comparing schools by size, with students attending institutions with than 2000 students passing both reading and math tests at a rate of 90.43% vs institutions with a student population between 2000-5000 passing both reading and math tests at a rate of 58.28%.   
