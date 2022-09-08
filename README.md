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
  - Thomas falls in the $630-$644 category. The only metric effected was a drop in % Overall Passing
  - <img width="858" alt="OriginalSpendingRange" src="https://user-images.githubusercontent.com/111014191/189045446-62313a9b-7bea-40f0-a7fc-e08b70f59d8c.png">
  - <img width="858" alt="ModifiedSpendingRange" src="https://user-images.githubusercontent.com/111014191/189045496-c3bd771d-0bc9-47b7-9f7a-e28da0b6d84b.png">
- Scores by school size
  - Thomas falls in the Medium category. The only metric effected was a drop in % Overall Passing.
  - <img width="786" alt="OriginalSchoolSize" src="https://user-images.githubusercontent.com/111014191/189045535-b8f41eca-bb3d-4c86-965c-172f86f77a59.png">
  - <img width="786" alt="ModifiedSchoolSize" src="https://user-images.githubusercontent.com/111014191/189045575-bd9e6ca4-216d-44a8-9ce8-e6bb84faa5bd.png">
- Scores by school type
  - Thomas falls in the Charter category. The only metric effected was a drop in % Overall Passing.
  - <img width="738" alt="OriginalSchoolType" src="https://user-images.githubusercontent.com/111014191/189045612-37ec3877-b823-4c0d-9d12-e4f4dd899ef5.png">
  - <img width="738" alt="ModifiedSchoolType" src="https://user-images.githubusercontent.com/111014191/189045635-108542a6-ca69-45c3-9237-6be854cc1c8f.png">
## Summary: Summarize four changes in teh updated school district analysis after reading and math scores for teh ninth grade at Thomas High School have been replaced with NaNs.
