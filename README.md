# School_District_Analysis

## Project Overview 

A City School System data scientist has requested to perform the following school analysis to determine the upcoming budget funding to the schools:

- Find the top 5 and bottom 5 performing schools. 
- Calculate the average student math score in each grade level at each school. 
- Calculate the average student reading score in each grade level at each school. 
- Calculate the school performance based on the spending per student. 
- Calculate the school performance based on the size of the school. 
- Calculate the school performance based on the type of school. 

However, there was evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Thus, the school district analysis was repeated. 

## Resources 

- Data Source : schools_complete.csv , students_complete.csv 
- Tools : Python 3.7.6, Pandas, Jupyter Notebook 
 
## Summary of Analysis

## District Level

After removing the 9th grade data of Thomas High the School district summary was affected as noted by the following changes:

- % Passing Math moved from 74.98% to 73.9%	
- % Passing Reading moved from 85.80% to 84.7% (1 percentage point)
- % Overall Passing moved from 65.17% to 64.1% (1 percentage point)

### Conclusion at District level
Analysis of the data after removal of 9th grade scores from Thomas High School support the theory that score inflation could have occurred.

## School Level

At the school level, the impact were the following:

- Average percent passing Math at Thomas decreased from 93.3% to 66.91% 
- Average percent passing Reading at Thomas decreases from 97.3% to 69.75% 
- Average percent overall passing decreased from 90.9% to 65.1% 

### Performance Rankings
Thomas High was no longer in the top 5 schools by performance. 

## Scores by Spending Level
When looking at the overall passing percentages by spending level, there is an effect at the per capita levels of $630-644, which may be an artifact of the spending level for Thomas High (at this same level).  With the removal of the 9th grade scores, the overall passing percentage decreased from 62.9% to 56.4% (6.5% decrease).

## Scores by School Type

The Charter schools demonstrate higher academic performance, even with the removal of the 9th grade Thomas High scores. However, Thomas High School was not a District school type, so there were no expected effects.

## Scores by School Size

I created four categories with the following bins: 0-1000 ("small"), 1000-2000 ("medium"), 2000-5000 ("large"). Removal of the 9th grade Thomas High scores did not affect performance based on school size. 
