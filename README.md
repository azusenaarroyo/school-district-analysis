# School District Analysis with Pandas

## Overview of the School District Analysis
The purpose of this School District Analysis is to provide insights on performance trends and patterns of all standardized tests data. These insights will be used to drive discussions and strategic planning at the school and district level by showcasing trends in school performance. In addition, it will help the school board in establishing school budgets and priorities. An initial data analysis was performed, however, a second data analysis was requested due to academic dishonesty in a 9th grade class at Thomas High School that altered the findings. The results and summary will examine the differences and show how altering the data to account for the academic dishonesty impacted the final results.  


## Results
* How is the district summary affected? It lowered the Average Math Score, % Passing Math, % Passing Reading, and %Overall Passing, and the Average Reading Score stayed the same. Reference the differences in the images below from the initial analysis to the updated analysis, respectfully.
<img width="927" alt="District_summary_initial" src="https://user-images.githubusercontent.com/91927712/142799496-a9d310c0-c6cf-452d-b53d-e142c6228a42.png">
<img width="931" alt="District_summary_updated" src="https://user-images.githubusercontent.com/91927712/142799514-7071fbe0-8a3f-4a13-b0be-afddd7063107.png">

* How is the school summary affected? It lowered the Average Math Score, % Passing Math, % Passing Reading, and %Overall Passing, and increased the Average Reading Score. Reference the differences in the images below from the initial analysis to the updated analysis, respectfully.
<img width="1003" alt="School_summary_initial" src="https://user-images.githubusercontent.com/91927712/142799693-382957f5-042f-432b-9c31-b73c16d4f563.png">
<img width="998" alt="School_summary_updated" src="https://user-images.githubusercontent.com/91927712/142799703-0b48157e-3a59-4f7d-9a11-88fc67bb6c3c.png">

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? It lowered the overall passing percentage by about 3 tenths place, however, it did not change the placement of the school relative to the other schools. Reference the differences in the images below from the initial analysis to the updated analysis, respectfully.
<img width="999" alt="Top_school_initial" src="https://user-images.githubusercontent.com/91927712/142799793-dcc47a19-53ec-4c29-8457-70c3250c300f.png">
<img width="991" alt="Top_school_updated" src="https://user-images.githubusercontent.com/91927712/142799804-b46bc55f-28a9-4151-ba18-40ba2c3e5c62.png">

How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade: The only math and reading scores by grade affected were for grade level 9 which outputs as nan (not a number), instead of an average for the test scores like every other grade level. 
* Scores by school spending:These scores were affected in the hundredths place, but weren't affected after the results were formatted to it's whole number or to the tenths place format. 
* Scores by school size:These scores were affected in the hundredths place, but weren't affected after the results were formatted to it's whole number or to the tenths place format. 
* Scores by school type: These scores were affected in the hundredths place, but weren't affected after the results were formatted to it's whole number or to the tenths place format. 


## Summary
Four changes to occur after the reading and math scores for the ninth grade at Thomas High School were replaced with NaNs are as followed: 
* The Average Math Score for Thomas High School changed from 83.418349 to 83.350937
* The % Passing Math for Thomas High School changed from 93.272172 to 93.185690
* The % Passing for Thomas High School Reading changed from 97.308869 to 97.018739
* The % Overall Passing for Thomas High School changed from 90 948017 to 90.630324
