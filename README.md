<img src="Pics/Header2.png" width="696" height="433">

# Pandas-Challenge

## Background
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.
As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

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

## Results
### Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.
Save the results in a DataFrame called "top_schools".

### Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
Save the results in a DataFrame called "bottom_schools".

### Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).
Use the code provided below to create four bins with reasonable cutoff values to group school spending.









# pandas-challenge
For the #4 Pandas -Challenge, I imported my dependencies pandas as pd, and set my path to my resource files, schools_complete.csv and students_complete.csv.  These newly created data frames school_data dataframes(df) & student_data df were then merged into school_data_complete df.  District wide variables student_count, total_budget, average_math_score, average_reading_score, passing_math_count, passing_reading_count, passing_math_percentage, passing_reading_percentage, passing_math_reading_count & overall_passing_rate was tabulated and placed in District_Summary df.  The District_Summary df was then utilized to produce a district wide summary table for viewing.  

From the previously created dataframes Per School information was then calculated to dig deeper into the data to assess school level trends.  Variables pulled for this School Summary include: school_types, per_school_counts, per_school_budget, per_school_capita (per studentspending), per_school_math, per_school_reading, students_passing_math, school_students_passing_math, students_passing_reading, school_students_passing_reading, students_passing_math_and_reading, school_students_passing_math_and_reading, per_school_passing_math(%), per_school_passing_reading(%) & overall_passing_rate(%).  This data was then utilized to produce a Per_School_Summary table visually breaking down the data at the per school level.  

Two tables were created displaying data from the Per School table outlining the Top Five Highest Performing and Lowest Performing Schools.  Two new tables were then created showing students passing (>70%) reading and math tests per school and by grade level (9th, 10th, 11th, 12th).  Finally, three tables were created to display Per Student Spending (<$585, $585-$629, $630-$644, $645-$680), School Size (<1000, 1000-2000, >2000), and by School Type (Charter vs District).  For my analysis of the data, please feel free to read PyCitySchools School Data Analysis. 

PyCitySchools School Data Analysis 
•	District statistics were tabulated looking at students from all 15 PyCitySchools high schools examining passing rates for reading and math (>70%).  The district wide passing rate for math was 74.98% while the district wide passing rate for reading was 85.80%.  The rate for students passing both math and reading was 65.17%.
•	The analysis was then broken down by High School outlining the School Type (District/Charter), the total school budget, the dollar amount invested per student, and the passing rates for each institution.  This analysis seemed to show a direct correlation between student population and scholastic success.
•	 The results were then categorized into the top five and top five lowest performing schools in the district. Notable trends include:
o	All the five highest performing schools were Charter Schools while all the five lowest performing schools were District schools.  
o	All the high performing Charters schools spent less dollars per student then the lowest performing District schools, showing that Charter schools were able to achieve higher scholastic performance at an overall reduced cost.
o	All the Charter schools had significantly lower student populations, frequently being half of their District school counterparts.
•	When examining the Reading and Math scores per school for 9th-12th graders, the scores remained consistent across the four years.
•	When examining statistics spanning school type, student population, school financials and test scores, higher test scores seem to correlate with a lower student population vs dollar spending at both the institution and student level.
•	 This correlation between scholastic success and student population is clearly outlined when the schools are broken down further by specific school size, with students attending institutions with a population size of less than 2000 students passing both reading and math tests at a 90.43% rate vs institutions with a student population between 2000-5000 passing both reading and math tests at a 58.28% rate.   
