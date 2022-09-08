# School_District_Analysis
## Overview of the School District Analysis
For this project, we were tasked with helping Maria take care of some innaccurate/dishonest data in regards to grades for students in Thomas High School. We looked at the average math scores, average reading scores, the passing scores for both, the overall percentage of students passing, scores by grade, scores by spending, scores by school size, and scores by school type.
## Results: Using bulleted lists and images of DataFrames as support, address the following questions
### How is the district summary affected?
The district summary is affected by a slight decrease in Average Math Scores, % Passing Math, % Passing Reading, and % Overall Passing
<img width="957" alt="OriginalDistrictSummary" src="https://user-images.githubusercontent.com/111014191/189040888-1624b4d3-ceb8-4ac1-8602-b83f3c073504.png">
<img width="957" alt="ModifiedDistrictSummary" src="https://user-images.githubusercontent.com/111014191/189040898-ef68657c-8472-4e12-9701-7943f74a5730.png">
### How is the school summary affected?
There is a slight drop in the Average Math Score, a slight increase in the Average Reading Score, and a large decrease in the % Passing Math, % Passing Reading, and % Overall Passing
<img width="981" alt="OriginalSchoolSummary" src="https://user-images.githubusercontent.com/111014191/189042535-0abcbd4a-dfa5-4288-9f2a-2ffa762ad2fb.png">
<img width="1077" alt="ModifiedSchoolSummary" src="https://user-images.githubusercontent.com/111014191/189042546-f80775ed-5b4b-447c-a056-81bcade2ce4f.png">
### How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
There is a significant drop in the % of Students Passing Math, Reading, and Overall. Decreases going from 93% to 67%, 97% to 70%, and 91% to 65% respectively.
### How doe replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
  - All scores remained the same besides the 9th grade scores which were removed.
- Scores by school spending
  - Thomas falls in the $631-$644 category. There were no metrics changed by removing the 9th graders once we rounded to whole integers.
- Scores by school size
  - Thomas falls in the Medium category. There were no metrics changed by removing the 9th graders once we rounded to whole integers. 
- Scores by school type
  - Thomas falls in the Charter category. There were no metrics changed by removing the 9th graders once we rounded to whole integers.
## Summary: Summarize four changes in the updated school district analysis after reading and math scores for teh ninth grade at Thomas High School have been replaced with NaNs.
The four things that were changed were the number of students taken into consideration for analysis, the % of Students Passing Math, the % of Students Passing Reading, and the % of Students Passing Overall. By taking out the students with grades that were not reported correctly, Thomas High School has a more accurate reporting of their grades. Unfortunately for the school, the numbers reflected better before. Hopefully they can turn turn things around and find themselves with more students passing in the next school year.
