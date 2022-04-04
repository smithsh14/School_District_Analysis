# School_District_Analysis
Analysis of School District Data
## Overview of the School District Analysis
Through the course of the project, we have been assisting Maria gather the data she needs to conduct an analysis on the school district's key metrics, including school size, each school's budget, passing rates of the students, etc. We have been able to provide the analysis Maria needs to be able to review the school's performances based on their budget per student, school size and the type of school they are identified under. Using this data, Maria has been able to identify the top five high performing schools and the bottom five low performing schools. This data is going to be used to help make the decisions for the upcoming academic school year. One area that Marie asked for more data on was in math and reading test scores. Maria asked us to calulate the average math and reading scores based on the school size. She also asked for the percentage of students who passed math and reading and the average overall percentage. Using the data we presented to Maria, she has been alerted there appears to be evidence of academic dishonesty. We have now been tasked with rerunning our previous data set while replacing the math and reading scores for Thomas High School with NaNs while keeping the remaining data intact and report back on our findings. 
## Results
After removing the ninth-grade math and reading scores from Thomas High School, it affected the summary tables by reducing the average scores and decreasing the passing percentage rate, in both reading and math passing rates and overall passing percentage.
### How was the district summary affected?
Initial Image
![Pic_2]https://github.com/smithsh14/School_District_Analysis/blob/main/02_PyCitySchools_Challenge-JupyterNotebook.png

NaNs Image
![Pic_1]https://github.com/smithsh14/School_District_Analysis/01_PyCitySchools_Challenge-JupyterNotebook.png

    - The data was only slighly affected once it was reanalyzed after the reading and math test scores for Thomas High School were replaced with NaNs. 

    - Between the two images, we can see "Total Schools", "Total Students", and "Total Budget" remained the same.
    
    - However, there were slight decreases in the values in the following categories
        - Average Math Score (difference of .05)
        - Aveerage Reading Score (difference of .01)
        - Percentage Passing Math (difference of .22)
        - Percentage Passing Reading (difference of .14)
        - Percentage Overall Passing (difference of .31)
       

### How was the school summary affected? 
Initial Image
![Pic_3]https://github.com/smithsh14/School_District_Analysis/blob/main/03_PyCitySchools_Challenge-JupyterNotebook.perSchool_Initial.png 

Just as in the above analysis, there is only a slight difference in the overall passing rate for Thomas High School before replacing the math and reading scores at 90.94% and after replacing them at 90.63%. A total difference of only .31%.
![Pic_4]https://github.com/smithsh14/School_District_Analysis/blob/main/04_PyCitySchools_Challenge-JupyterNotebook.perSchool_Revised.png 
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
After replacing the ninth graders' math and reading scores, Thomas High School's overall performance remained in the top five relative to the other schools. 

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade
#### Scores by school spending
#### Scores by school size
#### Scores by school type

## Summary
A summary of the four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School after being replaced with NaNs.