# School_District_Analysis

## Overview of the school district analysis

The client, Maria, requested an original analysis of students' standardized test scores to define each schools' performance, school trends including school type: district or charter, budget of the school and captia per student for each school.  This will help assist the school board on developing a future budget allotment.  This was achieved using Jupyter Notebook, Pandas and NumPy.  After the original analysis, Maria discovered that there was potential academic fraudulence with the ninth grade reading and math testing from Thomas High School.  School board has asked to remove the Thomas High School ninth grade standardized test from the sample.  This will ensure integrity within the analyzation.  The results will determine the impact on original findings to the adjusted findings.     

## Results: 
* District summary affected
    * Orginal Data Analysis
    ![alt text](https://github.com/bmliddicoat/School_District_Analysis/blob/9e28c0eb03a1abff75dc68653b43cc84ee44d839/Screenshots/Org_District_Summary.png)
    * Altered Data Analysis:
    ![alt text](https://github.com/bmliddicoat/School_District_Analysis/blob/9e28c0eb03a1abff75dc68653b43cc84ee44d839/Screenshots/Altered_District_Sum.png)
        * There was minor impact removing the possible "cheating" scores from ninth-graders.
        * Average math scores (79 to 78.9)
        * Percent of passing math (75% to 73.9%)
        * Percent of passing reading (86% to 84.7%)
        * Overall passing percentage (65% to 64.1%)

* School summary affected
    * Average math score (83.42 to 83.5)
    * Percent of students passing math decrease (93.27% to 66.91%)
    * Percent of students passing reading decreased (97.31% to 69.66%) 
    * Overall passing percentage of students decrease (90.95% to 65.08%).  
    * Average reading score for the school increased from decreased (83.85 to 83.90%).  

* Replacing the ninth graders’ math and reading scores effect on Thomas High School’s performance relative to the other schools
    * Original Top 5 Schools
    ![alt text](https://github.com/bmliddicoat/School_District_Analysis/blob/9e28c0eb03a1abff75dc68653b43cc84ee44d839/Screenshots/top_schools_org.png)
    * Altered Top 5 Schools:
    ![alt text](https://github.com/bmliddicoat/School_District_Analysis/blob/958c70c288e6892f40d929e35191baeeeb9b6c4a/Screenshots/Alter_top_school.png)
    * Thomas High School Adjusted Results
    ![alt text](https://github.com/bmliddicoat/School_District_Analysis/blob/f50feaa0bc115724d20df3d25d45491cc9c4af0f/Screenshots/alt_ths_sum.png)
    * Thomas High School drops from a top five school rank (2) to being the (8th).  
    * This makes Thomas High School the lowest ranking for charter schools but still outperforms district schools.    

* Replacing the ninth-grade scores affect:
    * Math and reading scores by grade.
        * Only impact is that ninth grade scores for math and reading are affected.  Other grades were not adjusted or altered because their scores were not in question. 
        * Ninth-grade mean of reading scores (82.51 to 82.43) 
        * Ninth grade mean of math scores (80.35 to 80.12) 

    * Scores by school spending
        * Original Data Analysis
        ![alt text](https://github.com/bmliddicoat/School_District_Analysis/blob/f50feaa0bc115724d20df3d25d45491cc9c4af0f/Screenshots/org_spending.png)
        * Altered Data Analysis:
        ![alt text](https://github.com/bmliddicoat/School_District_Analysis/blob/f50feaa0bc115724d20df3d25d45491cc9c4af0f/Screenshots/new_spending.png)
        * Minor changes.  Change occurred within the hundredths place.  

    * Scores by school size
        * Original Data Analysis
        ![alt text](https://github.com/bmliddicoat/School_District_Analysis/blob/f50feaa0bc115724d20df3d25d45491cc9c4af0f/Screenshots/org_school_size.png)
        * Altered Data Analysis:
        ![alt text](https://github.com/bmliddicoat/School_District_Analysis/blob/f50feaa0bc115724d20df3d25d45491cc9c4af0f/Screenshots/new_school_size.png)
        * Minor changes.  Change occurred within the hundredths place. 

    * Scores by school type
        * Original Data Analysis
        ![alt text](https://github.com/bmliddicoat/School_District_Analysis/blob/f50feaa0bc115724d20df3d25d45491cc9c4af0f/Screenshots/old_school_type.png)
        * Altered Data Analysis:
        ![alt text](https://github.com/bmliddicoat/School_District_Analysis/blob/f50feaa0bc115724d20df3d25d45491cc9c4af0f/Screenshots/new__school_type.png)
        * Minor changes.  Change occurred within the hundredths place. 

## Summary: 

There was an interesting impact on the school district analysis when replacing the Thomas High School ninth grade scores with NaNs.  Overall, the impact on the district summary and metrics such as school size, school spending and school type showed minor changes.  The district summary was affected in by average math scores (79 to 78.9), percent of passing math (75% to 73.9%), percent of passing reading (86% to 84.7%) and overall passing percentage (65% to 64.1%). These minor changes did not truly alter results.  An example is large schools (2000-5000) continue to show poor performance compared to small (<1000) and medium (1000 -2000).  Budget spending per student continues to show that less spent per student achieved higher school compared to higher spending ranges.  Charter schools still performed at a higher rate of success compared to district schools.  Even the mean scores of reading (82.51 to 82.43) and math (80.35 to 80.12) of ninth-graders was not radically affected.  

The largest impact was on Thomas High School's results.  The high school dropped from second rank school in the district to eighth in overall performances.  Areas which performed quite poorly after adjustment were the percent of students passing math decrease (93.27% to 66.91%), percent of students passing reading decreased (97.31% to 69.66%) and overall passing percentage of students decrease (90.95% to 65.08%). This can be attributed to fact that ninth grader all received failing results which caused success rate within the school to decrease dramatically.  Although, when investigating the average scores of math and reading changes are not quite drastic.  Surprisingly, the averages saw small improvements.  

In conclusion, there is minor effect on whole district and a large effect on the Thomas High School.  This due to fact that subtracting the students from the total count of district does not cause a huge impact on results.  Subtracting from a smaller sample size such as the Thomas High School will show drastic changes in some metrics.  The interesting finding is that smaller school size shows higher success.  It could be advised that school district further investigate this finding.  Decreasing the school size population may be the key for achieving higher schools.      
