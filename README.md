# School_District_Analysis_Challenge

## Overview
The purpose of this challenge was to familiarze myself with the pyhton language to conduct an analysis of a school district. It was found that there was evidence of academic dishonesty within the data sets that were provided. I was tasked with several things to append the analysis to get the results without the inaccurate scores.
1. Use Jupyter Notebook to write the code.
2. Replace the reading and math scores of 9th grade students from Thomas High School with NaN.
3. Use the loc method to replace the scores
4. Complete an analysis with the updated values. 
5. Write a summary of the analysis and how the data was affected.

### Results
1. How is the district summary affected?
- Original district summary.
![Original_Analysis.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Original_Analysis.PNG)
- Adjusted district summary.
![Adjusted_Analysis.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Adjusted_Analysis.PNG)
- After nullifying the 9th grade math and reading scores from Thomas High School I found that there were a few differences. The overall passing percentage did decrease since there was suspected academic dishonesty. However, in every other category I found that there was very light changes in the averages for reading score and math score. I also found the same minimal change with the percentage passing both math and reading.
2. How is the school summary affected?
- Original School Summary.
![Original_School_Summary.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Original_School_Summary.PNG)
- Adjusted School Summary.
![Adjusted_School_Summary.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Adjusted_School_Summary.PNG)
- From the analysis it appears that there is a very minimal change between the original and the adjusted analysis. There was a small amount of students that were removed from the analaysis that it had a very low impact on the analaysis. Although there was academic dishonesty within the 9th graders at Thomas High School we can say that it did not affect significantly how well the school did in comparison to the other schools in the district.
3. How does replacing the ninth-grade reading scores affect the following:
- Math and reading scores by grade.
- Original Math By Grade.

![Original_Math_By_Grade.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Original_Math_By_Grade.PNG)

- Adjusted Math By Grade.

![Adjusted_Math_By_Grade.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Adjusted_Math_By_Grade.PNG)

- Original Reading By Grade.

![Original_Reading_By_Grade.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Original_Reading_By_Grade.PNG)

- Adjusted Reading By Grade.

![Adjusted_Reading_By_Grade.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Adjusted_Reading_By_Grade.PNG)

The biggest differences in the differece between the Reading By Grade and Math By Grade is that the 9th graders from Thomas High School have been changed to NaN. This has affected only the total 9th grader score, but very miniamally due to it now being a smaller sample size of students in 9th grade.

- Scores by school spending.

- Original

![Origina_Score_By_Spending.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Original_Reading_By_Grade.PNG)

- Adjusted

![Adjusted_Score_By_Spending.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Adjusted_Reading_By_Grade.PNG)

When looking at the Score by Spending we find that there is in fact no real change within the data. I removed 461 total students, being the 9th graders at Thomas High School. This affected the data minimally and there is no real change from the original Score By Spending to the adjusted.

- Scores by school size.

- Original

![Original_Score_By_Size.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Original_Score_By_Size.PNG)

- Adjusted

![Adjusted_Score_By_Size.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Adjusted_Score_By_Size.PNG)

I have found that there is a small change within the score by school size due to the lower amount of total students. I removed 461 students, being the 9th graders at Thomas High School and it appears that there was a difference about %.5 for the % Passing Reading, % Passing Math, and the % Overall Passing.

- Scores by school type.

- Original

![Original_Score_By_Type.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Original_Score_By_Type.PNG)

- Adjusted

![Adjusted_Score_By_Type.PNG](https://github.com/mselover21/School_District_Analysis_Challenge/blob/main/Adjusted_Score_By_Type.PNG)

In relation to the scores by type it also appears that there is a small change as well. There is a difference of about %.3 in relation to the % Passing Reading, % Passing Math, and the % Overall Passing.

#### Summary
- All in all the changes that were made due to academic dishonesty from the 9th graders at Thomas High School had a very low impact on the final results. Even though there were minimal changes there were noticiable changes. The two most notable changes were in relation to Scores by Size and Scores by School Type. I found that there was a %.5 difference when it came to School Size and a %.3 Change in relation to School Type. This is expected due to the removal of 461 9th graders from Thomas High School. I also found that there was no noticable change when looking at Score by Spending. I could have increased the amount of decimals to each percent to see the overall change, but found that it was so minimal that it was not necessary. Overal this challenge was frustrating to say the least but taught me a lot about the use of pandas and how it is beneficial in the world of data analytics.
