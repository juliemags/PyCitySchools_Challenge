# School_District_Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.
A school board found potentially altered Reading and Math scores, indicating academic dishonesty among ninth graders in a school district. In order to keep this altered data from skewing the overall scores for Thomas High School, we are creating a program to omit the Reading and Math scores of the ninth graders. 

In order to omit the ninth grade data, we replaced the values with "NaN" (Not a Number) so that the system would not calculate the grades into the total school metrics. 

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- How is the district summary affected? 
  - The passing percentage of students fell for the entire district
  - Thomas High School fell from the Top 5 School rankings
- How is the school summary affected?
  -  The average scores for Thomas High's math and reading increased by less than 0.1 for both
  -  The overall passing percentage decreased by about 0.1%
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Thomas High School remained a top-five school in the district even when omitting the ninth graders. The tenth-twelfth graders had an overall passing rate of 90.6%
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade: It appears for most schools scores increased as students aged through the grades. For Thomas High, they remained relatively stagnant across tenth to twelfth grade. 
  - Scores by school spending: Spending more money per student led to a lower overall passing rate. The highest overall passing rates were from the lowest spending range per student. 
  - Scores by school size: The smaller schools saw the highest math an dreading scores. Medium schools saw the highest overall passing rate (91%). 
  - Scores by school type: Charter schools had overwhelmingly higher passing scores than district schools. 

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

From this data, there was a visible impact on school rankings from omitting the ninth graders' grades. Adding NaNs did not change the tenth-twelfth grades, so the data for reading and math for those grades was unaffected. 

Thomas High did drop from the Top 5 rankings, however they did not fully drop into the Bottom 5, which is promising that the academic dishonesty was not so disproportionate to the entire school (skewing the average Overall Passing percentages extremely high) 

School Spending was the most surprising outcome, as people generally hold the belief that spending more money leads to higher grades and higher overall passing percentages. This was not the case, in fact it was the opposite. We saw the highest scores in the lowest spending range, and the lowest passing percentage in the highest spending range. This is especially curious, as charter schools (which are typically more expensive) held overwhelmingly higher scores than the district grades (where public schools generally see lower spending budgets). 

