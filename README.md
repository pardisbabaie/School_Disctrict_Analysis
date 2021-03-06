# School_Disctrict_Analysis
## Overview of the school district analysis
The purpose of this assignment was to help Maria, a data scientist for the school district that is responsible for analyzing the data for the district school testing to ensure accuracy. Since academic dishonesty has been found in the data but the school district wants to uphold the state standard testing, we will need to modify the data by removing the test scores for math and reading for grade 9 in Thomas high School and replacing them with Nans so that data is diregarded in our overall analysis. The goal is to identify how this will affect the data and the results.
## Results
### District Summary
The district summary is only slightly affected with the removal of the grade 9 test grades. Once the numbers are formatted to the nearest whole number there is actually no difference in the results. 
### School Summary
When looking at the school summary with the grade 9 Thomas High School test results removed, there is a big difference seen with the % passing math, % passing reading & the overall % passing results for Thomas high School. There is a significant increase from before the removal of the grade 9 test scores to after as seen below: 
#### Before Grade 9 test scores removed
<img width="784" alt="Screen Shot 2020-09-19 at 8 09 07 PM" src="https://user-images.githubusercontent.com/69806770/93691503-15802b80-fab4-11ea-889c-292d4be4caf8.png">

#### After Grade 9 test scores removed
<img width="590" alt="Screen Shot 2020-09-19 at 8 11 44 PM" src="https://user-images.githubusercontent.com/69806770/93691529-71e34b00-fab4-11ea-9506-656a7edf6705.png">

### Thomas High School Performance 
The performance of Thomas High School relative to other schools significantly increases by removing the grade 9 test scores. By removing the grade 9 math and reading scores, Thomas High School gets ranked the #2 school based on overall passing percentage.
### Math and Reading scores by grade
Changing the 9th grade math and reading scores for Thomas High School does not affect the scores by grade view for any other school. The only change that takes place is the 9th grader scores for Thomas High school for both math and reading show up as NaN. 
### Spending Ranges
The results for score by spending ranges are not affected by the grade 9 scores for Thomas High School being removed at all as shown below:

<img width="795" alt="Screen Shot 2020-09-20 at 12 30 28 PM" src="https://user-images.githubusercontent.com/69806770/93716334-32ad0c80-fb3d-11ea-8991-56af630b664a.png">

### School Size
The size by score analysis is also not affected by the change in removing the grade 9 scores for Thomas High School as shown:

<img width="779" alt="Screen Shot 2020-09-20 at 12 34 44 PM" src="https://user-images.githubusercontent.com/69806770/93716423-bebf3400-fb3d-11ea-98f3-6aba9261f91e.png">

### School Type
The scores by school type are also not affected as Thomas High School is a charter school and the school type analysis before the grade 9 grades were removed showed that the charter school overall scores were higher and with the change in removing grade 9 scores the scores are higher for Thomas High school and the charter school scores are still higher as per below:

<img width="748" alt="Screen Shot 2020-09-20 at 1 15 14 PM" src="https://user-images.githubusercontent.com/69806770/93717433-ddc0c480-fb43-11ea-8c23-3a3b0a537c15.png">

## Summary
With removing the grade 9 test scores for math and reading in Thomas High School and replacing them with NaN there are slight changes that take place in our analysis. The most prominent change is the placement of Thomas High School in relation to the other schools. With the update to the % passing math, % passing reading and % passing overall, Thomas high school became ranked the 2nd top school based on overall passing percentage. The school district view is also changed as the % passing math, reading and overall scores for Thomas High School significantly increased and the increase is demonstrated in this view. As for the by grade view of each school, the data now shows a NaN for the math and reading scores in Thomas High School while all other schools are showing all grades. Finally, the district analysis results are slightly changed for % passing math, reading and overall but with the change being so small it does not fully reflect in the whole number results.
