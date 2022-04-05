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
![Pic_1](https://github.com/smithsh14/School_District_Analysis/blob/main/01_PyCitySchools_-DristrictSummary_Initial.png)

Replaced District Summary
![Pic_2](https://github.com/smithsh14/School_District_Analysis/blob/main/02_PyCitySchools_Challenge-DistrictSummary_Replaced.png)


*   Additionally, between the two images, we can see "Total Schools", "Total Students", and "Total Budget" remained the same.
    
*   However, there were slight decreases in the values in the following categories
    -   Average Math Score (difference of .05)
    -   Average Reading Score (difference of .01)
    -   Percentage Passing Math (difference of .22)
    -   Percentage Passing Reading (difference of .14)
    -   Percentage Overall Passing (difference of .31)

### School Summary Breakdown

We see a much higher percentatge different between the two data sets when reviewing the school summary information. 

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

The average math score and average reading scores dropped by 23-25 points.
The percentage of students passing for math and reading dropped by almost 27%.
The percentage of overall passing students dropped by almost 25%.
### Top 5 ann Bottom 5 Breakdown

Top 5 Schools based off of Initial values
![Pic_16](https://github.com/smithsh14/School_District_Analysis/blob/main/16_PyCitySchools_Top5_Initial.png)

Top 5 Schools with replacement values
![Pic_17](https://github.com/smithsh14/School_District_Analysis/blob/main/17_PyCitySchools_Bottom5_Initial.png)

Bottom 5 Schools based off of Initial values
![Pic_18](https://github.com/smithsh14/School_District_Analysis/blob/main/18_PyCitySchools_Challenge_Top5_Replaced.png)

Bottom 5 Schools with replacement values
![Pic_19](https://github.com/smithsh14/School_District_Analysis/blob/main/19_PyCitySchools_Challenge_Bottom5_Replaced.png)

-   The ranking of the top schools including Thomas High School was not affected by the update. Although the average math, reading and overall scores at Thomas High School were impacted with the update, the changes were not enough to change its relative ranking versus other schools. The changes only had a small impact of less than a change of 1 percentage point on each metric.

-   The ranking of the bottom schools was not affected by the update as the only metrics impacted where at Thomas High School as we are looking at each school's scores. Although the average math, reading and overall scores at Thomas High School were impacted with the update, the changes were not enough to change its relative ranking versus other schools. 

#### Scores by school size

Initial Average Math Score

![Pic_06](https://github.com/smithsh14/School_District_Analysis/blob/main/06_PyCitySchools_Math_per_Grade-Initial.png)

Replaced Average Math Score

![Pic_08](https://github.com/smithsh14/School_District_Analysis/blob/main/08_PyCitySchools_Math_per_Grade-NaNs.png)

Iniital Average Reading Score

![Pic_07](https://github.com/smithsh14/School_District_Analysis/blob/main/07_PyCitySchools_Reading_per_Grade-Initial.png)

Replaced Average Reading Score

![Pic_09](https://github.com/smithsh14/School_District_Analysis/blob/main/Reading_Grade_replacement.png)

-   The only score that is impacted on this DataFrame is that the grade 9 students at Thomas High School have Nan instead of a grade for both math and reading. If we ran a sum or mean of the DataFrame, we would see a difference between the orignal and updated.

#### Scores by school spending
![Pic_10](https://github.com/smithsh14/School_District_Analysis/blob/main/10_PyCitySchools_Spending_Initial.png)
![Pic_11](https://github.com/smithsh14/School_District_Analysis/blob/main/11_PyCitySchools_Spending_NaNs.png)

-   There was a slight change in the scores by school spending groups scores for the $630-644 per student grouping as this is where Thomas High School is grouped, however the change is small with each metric changing less than 0.1 percentage points (or change of less than 0.1%).

#### Scores by school size
![Pic_12](https://github.com/smithsh14/School_District_Analysis/blob/main/12_PyCitySchools_School_Size_Initial.png)
![Pic_13](https://github.com/smithsh14/School_District_Analysis/blob/main/13_PyCitySchools_School_Size_NaNs.png)

-   The scores for the Medium (1000-2000) size schools changed slightly (less than 1 percentage point). They were impacted as Thomas High School included in this group as it has 1,635 students who attend (including the grade 9 students).

#### Scores by school type
![Pic_14](https://github.com/smithsh14/School_District_Analysis/blob/main/14_PyCitySchools_School_Type_Initial.png)
![Pic_15](https://github.com/smithsh14/School_District_Analysis/blob/main/15_PyCitySchools_School_Type_NaNs.png)

-   Thomas High School is a Charter type school, so this is why we see changes to the scores for Charter (again less than change of 0.1% each metric), but no changes to District type school scores as Thomas High School not part of that group and no other school scores were affected.


## Summary
A summary of the four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School after being replaced with NaNs.


-   District Analysis - changes to all scores by less than 0.5 percentage points (or change by less than 0.5%) - no impact to school or student count.
-   Top School Ranking - no change to ranking, however Thomas High School scores did change, but by less than 1 percentage point (or changed by less than 1%) for each metric.
-   Scores by School Size - changes to Medium (1000-2000) grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).
-   Scores by School Type - chages to Charter type grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).

