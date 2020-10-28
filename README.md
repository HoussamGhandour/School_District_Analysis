# School_District_Analysis

## Overview
The school district board requested us to redo an analysis that we previously performed because it found that one of the schools (Thomas High School) had inaccurate math and reading scores for grade 9. Our team decided to disregard the inaccurate data by replacing them with "NaN's". In addition, we recalculated all statistics and presented results focused on district and school-level performance measures including: spending per capita, size of school, and school type.

## Results
The summary results is explained by answering the questions below:  

**1. How is the district summary affected?**  

The district summary is affected slightly because the scores for grade 9 in Thomas High School are replaced by nan's and are no longer considered in the calculations. The district performance measures changed as follows:

 - The average Math score decreased by 0.2 points to 78.9  
 - The average Reading score remained the same at 81.9  
 - The percentage passing Math decreased by 0.2% to 74.8%  
 - The percentage passing Reading decreased by 0.1% to 85.7%  
 - The percentage passing both Math and Reading decreased by 0.3% to 64.9%  

**2. How is the school summary affected?**

The Thomas High School summary is affected slightly because the scores for grade 9 are replaced by nan's and are no longer considered in the calculations. The changes are summarized as follows:

 - The average Math score remained at 83.4  
 - The average Reading score increased by 0.1 to 83.9 
 - The percentage passing Math decreased by 0.1% to 93.2%  
 - The percentage passing Reading decreased by 0.3% to 97.0%  
 - The percentage passing both Math and Reading decreased by about 0.4% to 90.6% 
 
**3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

As shown above, the overall percentage of students passing Math and Reading decreased by about 0.4% to 90.6% at the Thomas High School. However, this change didn't affect it's ranking among the top ranking schools. Thomas High School remains ranked as the second best performing school based on the overall percentage passing Math and Reading.

**4. How does replacing the ninth-grade scores affect the following:**
  - **Math and reading scores by grade**: No effect on grades 10, 11, and 12. Grade 9 scores for Thomas High Score have a "nan" assigned during the data cleaning process.   
  - **Scores by school spending**: No effect on three of the four bins as no changes in data was done in these bins. However, the ($630-644) bin which contains Thomas High School values got updated slightly due to the data cleaning for grade 9. Comparing initial and final values using the first decimal point for scores and whole numbers for percentages, no changes were observed. Please refer to the code for exact decimal changes. 
  - **Scores by school size**: No effect on two of the three bins as no changes in data was done in these bins. However, the (1000-2000) bin which contains Thomas High School values got updated slightly due to the data cleaning for grade 9. Comparing initial and final values using the first decimal point for scores and whole numbers for percentages, no changes were observed. Please refer to the code for exact decimal changes.
  - **Scores by school type**: No effect on the district type of school as no changes in data was done in these bins. However, the Charter school type which contains Thomas High School values got updated slightly due to the data cleaning for grade 9. Comparing initial and final values using the first decimal point for scores and whole numbers for percentages, no changes were observed. Please refer to the code for exact decimal changes.
  
 ## Summary
 
There was no big change in the school performance due to the change in scores for grade 9 especially looking at the numbers with the required formatting (one decimal place for scores and whole number for percentages). Some observations and conclusions are listed below:
1. Although the reading score increased for Thomas High School, the percentage passing decreased. This is a sign that the removed data for grade 9 have higher scores than the district average but more students in grade 9 of Thomas High School failed than the average of other schools.  
2. The highest change observed was at the district level among the % of overall passing which reduced by about 0.4% to 64.9%.  
3. An average of existing average grades was often used in the analysis per request from the school district board. It is advised to use a weighted average instead.    
4. No significant change was observed in the results in top performing schools, scores by school spending, scores by school size, and scores by school type.     
5. A negative correlation was observed between the spending per capita bins and the performance based on overall passing.   
