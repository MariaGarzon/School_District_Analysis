# School District Analysis

## Project Overview 

A City School System data scientist Maria requested me to perform the following school analysis to determine the upcoming budget funding to the schools:

- Find the top 5 and bottom 5 performing schools. 
- Calculate the average student math and reading score in each grade level at each school. 
- Calculate the school performance based on the spending per student, the size of the school, and the type of school. 

After compiling all of the data, there was evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Thus, the school district analysis was repeated replacing the 9th graders scores at Thomas High School with numpy. 

## Resources 

- Data Source : schools_complete.csv , students_complete.csv 
- Tools : Python 3.7.6, Pandas, Jupyter Notebook 
 
## Summary of Analysis

## Change at the District Level 

After removing the 9th grade data of Thomas High the School District Summary was affected as following:

- % Passing Math moved from 74.98% to 73.9%	(1 percentage point)
- % Passing Reading moved from 85.80% to 84.7% (1 percentage point)
- % Overall Passing moved from 65.17% to 64.1% (1 percentage point)

### Conclusion at District level
Analysis of the data after removal of 9th grade scores from Thomas High School support the theory that score inflation could have occurred.

## Change at Thomas High School

At the school level, the impact were the following:

- Average % passing Math decreased from 93.3% to 66.91% 
- Average % passing Reading from 97.3% to 69.75% 
- Average % overall passing from 90.9% to 65.1% 

### Change in the Performance Rankings
Thomas High was no longer in the top 5 schools by performance - it dropped from 4th to 7th highest scores in the district. 

## Change in the Scores by Spending Level
When looking at the overall passing percentages by spending level, there is an effect at the per capita levels of $630-644, which may be an artifact of the spending level for Thomas High (at this same level).  With the removal of the 9th grade scores, the overall passing percentage decreased from 62.9% to 56.4% (6.5% decrease).

## Change in Scores by School Type

The Charter schools demonstrate higher academic performance, even with the removal of the 9th grade Thomas High scores. However, Thomas High School was not a District school type, so there were no expected effects.

## Change in Scores by School Size

I created four categories with the following ranges: 0-1000 ("small"), 1000-2000 ("medium"), 2000-5000 ("large"). Removal of the 9th grade Thomas High scores did not affect performance based on school size. 

## Summary

Overall, there were two evident changes upon dropping the 9th graders' scores from Thomas High School: 

1. Thomas High School is no longer a top competitve school. 
2. 9th graders' reading and math scores dropped. 

