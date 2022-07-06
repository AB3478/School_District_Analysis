# School_District_Analysis

## Project Overview
The Chief Data Scientist for a city school district has requested assistance with aggregating school related data, including standardized test scores and student funding. The goal of this analysis is to highlight performance trends and patterns across the schools. The school board subsequently notified the Chief Data Scientist that the ninth grade reading and math scores for Thomas High School were possibly altered. She requested that those scores be replaced with NaNs while keeping the rest of the data intact. The following analysis should help inform discussions and strategic decisions at the school and district level.

## Resources
- Data sources: schools_complete.csv, students_complete.csv 
- Jupyter Notebook 6.4.11
- Python 4.13.0 

## Analysis of the school data determined that:
- The overall district summary dropped slightly as a result of replacing Thomas High School’s 9th grade reading and math scores with NaNs. There was less than a percentage point change across each category:

#### Overall District Scores
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/Original/Overall1.png)

#### Updated District Scores
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/THS_9th/Overall2.png)

-	Outside of Thomas High School’s 9th grade class, no other math or reading scores were impacted

#### Initial Math and Reading Scores by Grade
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/Original/Math_by_Grade1.png)
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/Original/Reading_by_Grade1.png)

#### Updated Math and Reading Scores by Grade
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/THS_9th/Math_by_Grade2.png)
![](https://github.com/AB3478/School_District_Analysis/blob/main/Images/THS_9th/Reading_by_Grade2.png)
