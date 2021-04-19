# School_District_Analysis
## Overview
The district school board has notified Maria and her supervisor about academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Methodology
Jupyter notebook and pandas was used for this challenge.

## Results

![DistrictSummary](https://user-images.githubusercontent.com/76858662/115239896-344bac80-a0ed-11eb-97f0-4dc1bc3c0615.PNG)

![PerSchoolSummary](https://user-images.githubusercontent.com/76858662/115239912-39106080-a0ed-11eb-84eb-eb9c97d068b6.PNG)

Analysis shows that charter schools are high performing school and Thomas High School is a one of the top performing school. the reason can be that the charter school have less number of students than district schools. Small and medium size schools have higher percentage than larger schools.
Also it seems that higher the per student spending,preferrably above $600, lower the overall percentage. 

The task was to recreate ninth graders at st. Thomas School-
1. Replace reading and math scores with NaN.
2. Recreate the district and school summary DataFrames.
3. Calculate the top 5 and bottom 5 performing schools.
4. Calculate the average math and reading score received by students in each grade level at each school.
5. Calculate school performance based on spending per student.
6. Calculate the school performance based on school type and size of the school.

## Summary

The new district summary shows that there is slight difference in math, reading and overall percentage by changing the math and reading scores of the 9th grade students of the Thomas High School by NaN but there is not much effect on the average math and reading scores.
The passing percentage for Thomas High School for math, reading and overall passing percentage has dratstically reduced from 90% to 60%.
Based on the spending, there is huge fall in overall percentage as the spending has increased to above $600.
Based on the school size, there is considerable fall in the percentage for the math, reading and overall as compared to the previous dataframe for medium (1000-2000 students) size school due to the fact that the Thomas High School has 1635 students which comes in the category of medium size schools.
There is no change in the average math and reading scores based on the school type. But since Thomas High School is charter type school, there is a slight reduction in the math and reading passing percentage. 


![MathReadingScoreRemoved](https://user-images.githubusercontent.com/76858662/115232081-568cfc80-a0e4-11eb-83f4-795d2137c38a.PNG)



