# School_District_Analysis

## Overview of the school district analysis:

The purpose of this assignment is to help Maria run a technical analysis on math, reading, and overall scores for a series of schools. The analysis will help draw conclusions at the grade, school, school type, budget, and size level. In this assignment we have been informed of academic dishonesty in the 9th grade class of Thomas High School. Since we do not know the extent of the dishonestly we will simply be removing all data for that cohort to not skew the results 

## Results:
- How is the district summary affected?

In the data manipulation to remove any possible academic dishonesty we replaced the math and reading scores with a "nan" value, this means that the numbers that were affected in the district summary will be: Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing. All of the changes in these columns were equal to or less than 0.1 for the averaged and 0.4% for the percentages, indicating that there was not a very large change. See below the summaries for further details:

|  District Summary with Compromised Data  | ![district_summary_old](https://github.com/andreabassetti/School_District_Analysis/blob/main/Resources/district_summary_old.png)  |
| ------------------ | ----------------- |
|  District Summary with Uncompromised Data  | ![district_summary_new](https://github.com/andreabassetti/School_District_Analysis/blob/main/Resources/district_summary_new.png)  |

- How is the school summary affected?

In the data manipulation to remove any possible academic dishonesty we replaced the math and reading scores with a "nan" value, this means that the numbers that were affected will all fall under the data for Thomas High School. Like above, the impact on the  numbers for Thomas High School were equal to or less than 0.1 for the averages and 0.4% for the percentage.  See below for further details:

| School Summary with Compromised Data | ![school_summary_old](https://github.com/andreabassetti/School_District_Analysis/blob/main/Resources/school_summary_old.png) |
| ------------------ | ----------------- |
| School Summary with Uncompromised Data | ![school_summary_new](https://github.com/andreabassetti/School_District_Analysis/blob/main/Resources/school_summary_new.png) |

- How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?

As mentioned above, the changes were very minimal and therefore it does not affect Thomas High Schools performance relative to other schools. It remains the second highest performing school. 

- How does replacing the ninth-grade scores affect the following:

**Math and reading scores by grade**: Replacing the ninth-grade scores only affects the scores shown for Thomas High School for 9th grade. These values will no longer be numerical, they will now display "nan". All other values will remain unchanged. This applies both to the math and reading scores by grade. 

**Scores by school spending**: Since Thomas High School is in the $630-644 spending per student bracket, only the values in that row will be affected. When looking at the values with only one decimal point, no change is observed. When looking at the values with multiple decimal points the values were very minimally affected, see below for more details. 

|  School Spending with Compromised Data  |  ![school_brackets_old](https://github.com/andreabassetti/School_District_Analysis/blob/main/Resources/spending_brackets_old.png) |
| ------------------ | ----------------- |
|  School Spending with Uncompromised Data  |  ![school_brackets_new](https://github.com/andreabassetti/School_District_Analysis/blob/main/Resources/spending_brackets_new.png)  |
 
**Scores by school size**: Since Thomas High School is in the Medium(1000-2000) category, only the values in that row will be affected. When looking at the values with only one decimal point, no change is observed. When looking at the values with multiple decimal points the values were very minimally affected, see below for more details: 

|  School Size with Compromised Data  |  ![school_size_old](https://github.com/andreabassetti/School_District_Analysis/blob/main/Resources/school_size_old.png)  |
| ------------------ | ----------------- |
|  School Size with Uncompromised Data  |  ![school_size_new](https://github.com/andreabassetti/School_District_Analysis/blob/main/Resources/school_size_new.png)  |

**Scores by school type**: Since Thomas High School is in the Charter category, only the values in that row will be affected. When looking at the values with only one decimal point, no change is observed. When looking at the values with mutiple decimal points the values were very minimally affected, see below for more details: 

|  School Type with Compromised Data  |  ![school_type_old](https://github.com/andreabassetti/School_District_Analysis/blob/main/Resources/school_type_old.png)  |
| ------------------ | ----------------- |
|  School Type with Uncompromised Data  |  ![school_type_new](https://github.com/andreabassetti/School_District_Analysis/blob/main/Resources/school_type_new.png)  |

## Summary:

After replacing the math and reading scores for the ninth grade at Thomas High School we can conclude that every step of the analysis was affected in some way.
It is important to note that this effect was minor and did not change the ranking by performance or lead to different conclusions. Below we find a summary table on how each statistic was affected for each scenario. We can see that generally, the scores decreased once the math and reading scores for the ninth grade at Thomas High School were replaced. However, the average reading scores in most scenarios slightly increased. 

|        -         | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ------------------ | -----------------| ------------------ | ----------------- | ------------------ | ----------------- |
| District Level | Decreased | Decreased | Decreased | Decreased | Decreased | 
| School Level | Decreased | Increased | Decreased | Decreased | Decreased | 
| School Spending | Decreased | Increased | Decreased | Decreased | Decreased | 
| School Size | Decreased | Increased | Decreased | Decreased | Decreased | 
| School Type |  Decreased | Increased | Decreased | Decreased | Decreased | 

