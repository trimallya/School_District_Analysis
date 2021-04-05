# School_District_Analysis

## Overview of the school district analysis
This analysis examines student funding and student standardized test scores for a variety of high schools to determine trends in school performance. Insights generated will  help the school board determine whether to modify the school budgeting and how to prioritize when making such decisions. 

## Results
- The district summary was not affected (as seen below).
- The only data in the school summary which was affected was in the row for Thomas High School. As seen in the images below, the % Passing Math, % Passing Reading, and % Overall Passing dropped very slighlty for Thomas High School but remained the same for the high schools listed above and below. Percentages dropped by less than 1% after removing all ninth grade data. 
- Replacing the ninth graders' math and reading scores did not affect Thomas High School's performance relative to the other schools as it remained as second in the top five schools. 
- Replacing ninth-grade scores had the following results:
    - Math and reading scores by grade were not affected for the most part. The only big difference is seen in the "9th" column for Thomas High School which now has "NaN" as those score are now not being used. An example of this can be seen in the image below.
    - Scores by school size were not affected (as seen below).
    - Scores by school type were also not affected (as seen below).

## Summary
Even after reading and math scores for the ninth grade at Thomas High School were replaced by NaNs, many of the scores and rankings remained relatively the same. However, it should be noted that one slight change did occur in the percentage of students who passed math for Thomas High School in the school summary. This means that the average ninth grade score raised the overall percentage of math scores for the whole school by less than a percent. A similar change can be seen in the percentage of students who passed reading in Thomas High School, with percentage decreasing by less than 1% after removing all ninth grade scores. These two changes led to a similar slight decrease in the overall percentage of students passing math and reading for Thomas High School. In addition, all scores pertaining to math and reading scores for ninth grade students in Thomas High School have been replaced with "NaN" for all DataFrames, including the math and reading scores by grade.
