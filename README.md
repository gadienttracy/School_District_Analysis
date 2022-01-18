# School_District_Analysis
## Overview of the school district analysis:
The purpose of this analysis is to compare the math, reading, and overall passing percentages for each school district in the analysis.  After gathering this information we were able to provide an overview of key metrics for each school:
Top 5 and bottom 5 performing schools, based on the overall passing rate
The average math score received by students in each grade level at each school
The average reading score received by students in each grade level at each school
School performance based on the budget per student
School performance based on the school size 
School performance based on the type of school 

After performing the analysis it was requested that the 9th grade scores from Thomas High School be removed.  Key differences in the findings after removing that information are listed below.

## Results:
After removing the scores for 9th graders at Thomas High School we were able to see the adjustments to the key metrics.
- Top 5 and bottom 5 performing schools, based on the overall passing rate: The schools rankings were not affected by the removal of the scores
- The average math score received by students in each grade level at each school: Thomas High Schools 9th grade math scores returned "nan"
- The average reading score received by students in each grade level at each school: Thomas High Schools 9th grade reading scores returned "nan"
![nan](https://user-images.githubusercontent.com/91269696/149867068-ac03c290-db7b-4d6f-b87f-8b1afd27ac06.PNG)
*9th grade scores from Thomas High School return 'nan'*
- School performance based on the budget per student: the budget per student was affted in the $630-644 bin.  While the differences were only seen in the hundreths place the Overall passing was 62.78% without the 9th grade students from Thomas High School and 62.86% with them included.
- School performance based on the school size: the performance based on school size was mostly unaffected by the removal of the THS 9th grade scores
- School performance based on the type of school: The average math score dropped one-hundreth's of a point, the average reading score increased one-hundreth's of a point, the % passing math and reading were affected in a minor way as well. Finally the overall passing score for Charter schools was 90.39% with the removal of the scores, it was 90.43% with them included.
![challenge](https://user-images.githubusercontent.com/91269696/149866876-9cdcc396-fbfb-4762-b445-cf50941be070.PNG)
*challenge summary*
![prechallenge](https://user-images.githubusercontent.com/91269696/149866988-2c9bdcb0-5088-468e-8a06-520e0ce8ca04.PNG)
*results before the removal of the 9th grade students from Thomas High School*

## Summary:
In summary the tables for average reading and math scores received by students in each grade returned 'nan' for the 9th grade students from Thomas High School after the removal of their scores.  The school performance based on type of school was not significantly affect, however there was a difference in the hundreths place for averages and percentages in reading and math.  Finally, the spending per student was not signicantly impacted by the change in data, however it could be noticed in the hundreths position for each of the categories.
