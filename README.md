# School_District_Analysis

## Project Overview
The Chief Data Scientist for a city school district has requested assistance with aggregating school related data, including standardized test scores and student funding. The goal of this analysis is to highlight performance patterns across the schools and help inform discussions and strategic decisions at the school and district level. 

The school board subsequently notified the Chief Data Scientist that the ninth grade reading and math scores for Thomas High School were possibly altered. She requested that those scores be replaced with NaNs while keeping the rest of the data intact.

## Resources
- Data sources: schools_complete.csv, students_complete.csv 
- Jupyter Notebook 6.4.11
- Python 4.13.0 

## Analysis of the school data determined that:
The overall district summary dropped slightly as a result of replacing Thomas High School’s 9th grade reading and math scores with NaNs. There was less than a percentage point change across each category:

#### Overall District Scores
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/Original/Overall1.png)

#### Updated District Scores
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/THS_9th/Overall2.png)

Outside of Thomas High School’s 9th grade class, no other math or reading scores were impacted

#### Initial Math and Reading Scores by Grade
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/Original/Math_by_Grade1.png)
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/Original/Reading_by_Grade1.png)

#### Updated Math and Reading Scores by Grade
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/THS_9th/Math_by_Grade2.png)
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/THS_9th/Reading_by_Grade2.png)

-The top five and bottom schools remained the same. Thomas High School is still considered a top five school, despite adding NaNs to the 9th grade class and subsequently lower overall reading and math scores.

-School spending should not have changed. Although an error is indicated for the updated passing math and reading percentages. 

-Scores by school size should not have changed either. Although an error is indicated for the updated passing math and reading percentages.

-Scores by school type also did not change.

## Challenge Summary
There were four key changes in the updated school district analysis following the replacment of Thomas High Schools 9th grade math and reading scores:
  
  -
  -
  -
  -

