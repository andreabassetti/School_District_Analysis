# School_District_Analysis

## Overview of the school district analysis:

The purpose of this assignment is to help Maria run a technical analysis on math, reading, and overall scores for a series of schools. The analysis will help draw conclusions at the grade, school, school type, budget, and size level. In this assignment we have been informed of academic dishonesty in the 9th grade class of Thomas High School. Since we do not know the extent of the dishonestly we will simply be removing all data for that cohort to not skew the results 

## Results:
- How is the district summary affected?
In the data manipulation to remove any possibe academic dishonesty we replaced the math and reading scores with a "nan" value, this means that the numbers that were affected in the district summary will be: Average Math Score, Average Reeading Score, % Passing Math, % Passing Reading, and % Overall Passing. All of the changes in these columns were equal to or less than 0.1 for the averaged and 0.4% for the percentages, indicating that there was not a very large change. See below the summaries for further details:
|  Summary with Compromised Data  |  IMAGE  |
|  Summary with Uncompromised Data  |  IMAGE  |

- How is the school summary affected?
In the data manipulation to remove any possibe academic dishonesty we replaced the math and reading scores with a "nan" value, this means that the numbers that were affected will all fall under the data for Thomas High School. Like above, the impact on the  numbers for Thomas High School were equal to or less than 0.1 fo rthe averages and 0.4% for the percentage.  See below for further details:
|  Summary with Compromised Data  |  IMAGE  |
|  Summary with Uncompromised Data  |  IMAGE  |

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
As mentioned above, the changes were very minimal and therfore it does not affect Thomas High Schools preformance realtive to other schools. It remains the second highest performing school. 

- How does replacing the ninth-grade scores affect the following:
**Math and reading scores by grade**: Replacing the ninth-grade scores only affects the scores shown for Thomas High School for 9th grade. These values will no longer be numerical, they will now display "nan". All other values will remain unchanged. This applies both to the math and reading scores by grade. 
**Scores by school spending**: Since Thomas High School is in the $630-644 spending per student bracket, only the values in that row will be affected. When looking at the values with only one deciaml point, no change is observed. When looking at the values with mutiple decimal points the values were very minimally affected, see below for more details. 
|  Summary with Compromised Data  |  IMAGE  |
|  Summary with Uncompromised Data  |  IMAGE  |
 
**Scores by school size**: Since Thomas High School is in the Medium(1000-2000) category, only the values in that row will be affected. When looking at the values with only one deciaml point, no change is observed. When looking at the values with mutiple decimal points the values were very minimally affected, see below for more details: 
|  Summary with Compromised Data  |  IMAGE  |
|  Summary with Uncompromised Data  |  IMAGE  |

**Scores by school type**: Since Thomas High School is in the Charter category, only the values in that row will be affected. When looking at the values with only one deciaml point, no change is observed. When looking at the values with mutiple decimal points the values were very minimally affected, see below for more details: 

##Summary:
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
