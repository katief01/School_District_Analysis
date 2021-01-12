# School_District_Analysis
Module 4

## Overview of the School District Analysis
  The purpose of this analysis was to repeat the original School District Analysis done in this module and determine the extent, if any, of academic dishonesty with Thomas High School (THS) ninth grade scores.  The repeated analysis involved replacing the math and reading scores for THS with NaNs while keeping the rest of the schools' data intact.

## Results of Repeated Analysis: 
  * District Summary: 
      The district summary results after THS 9th grade scores were removed did not change the output dramatically.  Both summaries saw an average math score of 79 and an average reading score of 82.
  * School Summary: 
      The school summary showed quite a big difference between the two analyses.  The THS scores in the original analysis were at 93 for math and 97 for reading.  This repeated analysis with 9th grade scores removed showed an 83 average for math and 84 for reading, as noted in this Jupyter Notebook file - PyCitySchools_Challenge.ipynb.
  * Thomas High School's performance relative to the other schools:  
      The school's performance went down dramatically after removing the 9th grade scores.  The overall pass percentage went ofrom 90% down to 64%. The percent of students passing math went from 93% down to 67%.  The percent of students passing reading went from 97% down to 70%, also seen in this file - PyCitySchools_Challenge.ipynb.
  * Affect when replacing Thomas High School ninth-grade scores on:
      * Math and reading scores by grade: The 10th-12th grade math and reading scores stayed the same for both analyses since 9th grade math and reading scores were removed for the repeated analysis.
      * Scores by school spending: The scores in this category stayed very similar exect in the $630 - $644 category. This makes sense because THS falls into this category with $638 in spending per student.
      * Scores by school size: These scores also stayed similar except in the category of 1,000 - 2,000 students. This also makes sense since THS has 1,635 students and their entire ninth grade population (461 students) was removed for this analysis.
      * Scores by school type: These scores stayed the same for District schools but Charter school scores went down by 3 points upon removing the THS ninth graders (90.4 down to 87).

## Summary: 
  In summary, out of the four major categories reviewed above comparing the two school district analyses, after reading and math scores for the ninth graders at THS were replaced with NaNs, Thomas High School's individual performance relative to other schools was the best indicator of possible dishonesty.  The percentage of students who were passing reading, math, and overall changed most dramatically in this category once the 9th grade scores from THS were removed.  The School Summary dataframe also showed a noticeable difference between the original averages for math and reading compared to when 9th graders at THS were removed.  The scores went down approximately 10 points in each category. The changes to scores based on school spending, size and type showed expected changes due to THS's metrics, but nothing to suggest dishonesty.   
