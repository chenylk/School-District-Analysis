# School-District-Analysis

## Overview of the school districrt analysis
  * The purpose of this analysis was to analyze different schools in a school district to determine what factors led to successful student performance in standardized math and reading testing. Categories such as budget per capita, school type and school size were examined to determine any trends. After the analysis was done, the school board determined that reading and math scores for the Thomas High School 9th graders were altered. This data was taken out of the data set and the data analysis was reran. 
  
## Results
  * The district summary was affected across the board. Each category decreased after removing the 9th grade scores for math and reading at Thomas High School. Reading, math and overall percentage passing students dropped by about 1 percent.  
  ![Old_district_summary](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/old_district_summary.PNG)
  ![New_district_summary](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/new_district_summary.PNG)
  
  * The school summary was unchanged for all schools except for Thomas High School, where the 9th grade scores were removed. This is because no other data was altered for any other school with the exception of Thomas High School. 
  
  * The ninth grade scores significantly pulled up the average scores at Thomas High School. The % passing in both math and reading and overall passing rate dropped by about 30 percent.
  ![Old_school_summary](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/old_school_summary.PNG)
  ![new_school_summary](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/new_school_summary.PNG)
  
  * Replacing ninth-grade scores effects:
   1. The Thomas High School ninth grade math and reading scores were high amongst their ninth grade peers at other high schools. They ranked third in math and and fifth in reading. Removing their scores brought the overall average for the ninth graders in the district down. 
   ![math_scores](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/math_scores_bygrade.PNG)
   ![reading_scores](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/reading_scores_bygrade.PNG)
   
   2. For the scores by school spending, the only group that changed was the $630-644 range because Thomas High School fell in that range and only Thomas' grades were changed in the analysis. The average reading and math score stayed reletively the same but the % passing in math, reading and overall all dropped in this per capita range. 
   
   ![old_spendingscores](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/old_schoolspending.PNG)
   ![new_spendingscores](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/new_schoolspending.PNG)
   
   3. The school size data was affected similarly to the school spending data. Since Thomas High School was in the medium school size range, the small and large school size data were unaffected. Just like for school spending, the average reading and math scores stayed reletively the same and the % passing in math, reading, and overall all decreased. 
   ![old_schoolsize](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/old_schoolsize.PNG)
   ![new_schoolsize](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/new_schoolsize.PNG)
   
   4. The school type data was affected similarly to the school size and school spending data. Only the charter school data was affected because Thomas High School was considered a charter school. The district school data remained unchanged. The average scores stayed reletively the same and the % passing in each category decreased with the removal of the 9th grade data from Thomas High School. 
   ![old_schooltype](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/old_schooltype.PNG)
   ![new_schooltype](https://github.com/chenylk/School-District-Analysis/blob/master/Resources/new_schooltype.PNG)
   

## Summary
 * After updating the questionable results from the 9th grade class at Thomas High School, there were several changes in the district data. Overall, the scores from those 9th grade students were good, so removing those brought the percentage of passing students down and the averages of the reading and math scores were slightly lower (by fractions of a percent). Also, Thomas High Schools individual performance was significantly altered. Their passing rates decreased significantly after removing the 9th grade data. I think the percentages are so different because the code does not account for the change in student popoulation after you make the 9th graders' scores at Thomas High School NaN. Lastly, the different categories of data analyzed were changed because of this data removal. School type, size and spending categories by schools were altered in their reading and math scores and percent passing percentage.  
 * One item to keep in mind for this code is that the total student count was not altered when calculating percentages. So the 9th grade students were counted towards the total student count but not as a passing or failing student. Thus, the passing rates are highly questionable. 
 
   

