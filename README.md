# School_District_Analysis
Analysis of School District Data
## Overview of the School District Analysis
Through the course of the project, we have been assisting Maria gather the data she needs to conduct an analysis on the school district's key metrics, including school size, each school's budget, passing rates of the students, etc. We have been able to provide the analysis Maria needs to be able to review the school's performances based on their budget per student, school size and the type of school they are identified under. Using this data, Maria has been able to identify the top five high performing schools and the bottom five low performing schools. This data is going to be used to help make the decisions for the upcoming academic school year. One area that Marie asked for more data on was in math and reading test scores. Maria asked us to calulate the average math and reading scores based on the school size. She also asked for the percentage of students who passed math and reading and the average overall percentage. Using the data we presented to Maria, she has been alerted there appears to be evidence of academic dishonesty. We have now been tasked with rerunning our previous data set while replacing the math and reading scores for Thomas High School with NaNs while keeping the remaining data intact and report back on our findings. 
## Results
After replacing the math and reading scores for Thomas High School with NaNs and keeping the rest of the data intact, we have analyzed the data using the initial results and the replaced results looking specifically at the following...

    The district summary.
    The school summary.
    The top 5 and bottom 5 performing schools, based on the overall passing rate.
    The average math score for each grade level from each school.
    The average reading score for each grade level from each school.
    The scores by school spending per student, by school size, and by school type.

### District Summary Breakdown

The data was only slighly affected once it was reanalyzed after the reading and math test scores for Thomas High School were replaced with NaNs. 

Initial District Summary
![Pic_2]

Replaced District Summary
![Pic_1]


*   Additionally, between the two images, we can see "Total Schools", "Total Students", and "Total Budget" remained the same.
    
*   However, there were slight decreases in the values in the following categories
    -   Average Math Score (difference of .05)
    -   Average Reading Score (difference of .01)
    -   Percentage Passing Math (difference of .22)
    -   Percentage Passing Reading (difference of .14)
    -   Percentage Overall Passing (difference of .31)
       

### School Summary Breakdown
Initial Image
![Pic_3](https://github.com/smithsh14/School_District_Analysis/blob/main/03_PyCitySchools_Challenge-JupyterNotebook.perSchool_Initial.png) 

NaNs Image
![Pic_4](https://github.com/smithsh14/School_District_Analysis/blob/main/04_PyCitySchools_Challenge-JupyterNotebook.perSchool_Revised.png)
 
When isolating out the data for Thomas High School after replacing the math and reading scores with NaNs, we recongnize the following:

    - Between the two images, we can see the following categories returned the same value
        - Total School Budget ($1,043,130.00)
        - Per Student Budget ($638.00)
    
    - However, there were differences in the values in the following categories
        - Average Math Score (.06 decrease in value from the initial analysis)
        - Aveerage Reading Score (.05 increase in the value from the initial analysis)
        - Percentage Passing Math (26.36% decrease from the initial analysis)
        - Percentage Passing Reading (27.65% decrease from the initial analysis)
        - Percentage Overall Passing (25.87% decrease from the initial analysis)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
In regards to Thomas High School's performance, we can see...

![Pic_5](https://github.com/smithsh14/School_District_Analysis/blob/main/05_PyCitySchools_PerSchoolSummary_initial.png)

![Pic_05](https://github.com/smithsh14/School_District_Analysis/blob/main/05_PyCitySchools_PerSchoolSummary_NaNs.png) 


    - Average Math Score and Average Reading scores dropped to 23-25.
    - % Passing Students for Math and Reading dropped to almost 27%.
    - % Overall passing students dropped to almost 25%.


### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade
Initial Average Math Score
![Pic_06](https://github.com/smithsh14/School_District_Analysis/blob/main/06_PyCitySchools_Math_per_Grade-Initial.png)
Replaced Average Math Score
![Pic_08](https://github.com/smithsh14/School_District_Analysis/blob/main/08_PyCitySchools_Math_per_Grade-NaNs.png)
Iniital Average Reading Score
![Pic_07](https://github.com/smithsh14/School_District_Analysis/blob/main/07_PyCitySchools_Reading_per_Grade-Initial.png)
Replaced Average Reading Score
![Pic_09]https://github.com/smithsh14/School_District_Analysis/blob/main/07_PyCitySchools_Reading_per_Grade-Initial.png)

#### Scores by school spending
![Pic_10](https://github.com/smithsh14/School_District_Analysis/blob/main/10_PyCitySchools_Spending_Initial.png)
![Pic_11](https://github.com/smithsh14/School_District_Analysis/blob/main/11_PyCitySchools_Spending_NaNs.png)

#### Scores by school size
![Pic_12](https://github.com/smithsh14/School_District_Analysis/blob/main/12_PyCitySchools_School_Size_Initial.png)
![Pic_13](https://github.com/smithsh14/School_District_Analysis/blob/main/13_PyCitySchools_School_Size_NaNs.png)

#### Scores by school type
![Pic_14](https://github.com/smithsh14/School_District_Analysis/blob/main/14_PyCitySchools_School_Type_Initial.png)
![Pic_15](https://github.com/smithsh14/School_District_Analysis/blob/main/15_PyCitySchools_School_Type_NaNs.png)

## Summary
A summary of the four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School after being replaced with NaNs.
