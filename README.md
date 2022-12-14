# -School_District_Analysis

## Overview of the school district analysis: 
This school district analysis is to determine if there were signs of academic dishonest among 9th graders in Thomas High School. In order to do this, we removed those students' math and reading scores from the data set and compared to the reast of the data.  

## Results: 

### How is the district summary affected?
When 9th graders were removed, the district summary was affected:
  
- Old District summary:
  ![Old District Summary](https://raw.githubusercontent.com/ecost95/-School_District_Analysis/main/OldDistrictSummary.png)
  
- District Summary with Thomas 9th graders removed:
  ![Old District Summary](https://raw.githubusercontent.com/ecost95/-School_District_Analysis/main/NewDistrictSummary.png)
  
- As we can see in the photos, when 9th graders from Thomas High School were removed, the overall passing percent and passing math percent were lowered, while the percent passing reading increased. 
  
### How is the school summary affected?
When 9th graders were removed, the schools summary was affected:
  
- Old school summary:
  ![old School Summary](https://raw.githubusercontent.com/ecost95/-School_District_Analysis/main/perschoolinitialdf.png)
  
- New school summary:
  ![New School Summary](https://github.com/ecost95/-School_District_Analysis/blob/main/InitialPerSchoolSummary.png)
  
- As we can see from the data frames, when the Thomas High 9th graders' scores were removed, the percent passing reading, math, and overall fell sharply. The percentages for THS were 93.27 % (math) 97.03% (reading) and 90.95% (overall), but once the affected grades were removed, the percentages for THS were 66.9% (math)69.66% (reading) and 65.08% (overall)
  
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
When we replaced the 9th graders scores with only the 10-12th graders scores, the school summary was affected:
  
 - School summary 9th graders replaced:
 ![School Summary 9th grade replaced](https://github.com/ecost95/-School_District_Analysis/blob/main/THS_10_12_DF.png)
 
 - When 9th graders were replaced, we can see that the scores increased from our new school summary above, but are slighty lower than the initial school summary with THS 9th grader scores included. The new scores for THS: 93.19% passing math, 97.02 passing reading, 90.63 passing overall. 
 
 - Thomas High School remains one of the top schools in the district:
  ![New Top Performing Schools](https://github.com/ecost95/-School_District_Analysis/blob/main/HighLowPerformingNew.png)
  
### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
  
  - Initial math and reading scores:
   ![9th Math/Readingin initial](https://raw.githubusercontent.com/ecost95/-School_District_Analysis/main/_mathreadingininit.png)
   
   - Math and reading scores with THS 9th graders removed:
   ![9th Math Reading Chal](https://raw.githubusercontent.com/ecost95/-School_District_Analysis/main/_MathReadingChal.png)
   
- Scores by school spending
 
  
- Scores by school size
  
  
- Scores by school type
  - After replacing the 9th grade test scores, the changes to the scores by school size were to small to change the overall percentages. When rounded to the nearest hundredth, both analyses had the same summaries:
  ![Scores by school size](https://raw.githubusercontent.com/ecost95/-School_District_Analysis/main/Screenshot%20(125).png)
  
## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Although the percent passing percentages for Thomas High School are slightly lower when the 9th grade test scores are replaced with NaNs, the changes are so small that they are statistically insignificant. They do not affect THS performance relative to other schools, and the overall averages for charter schools remains the same. We would expect a larger change to the overall sumarries if there was academic dishonesty.
