# School_District_Analysis

## Overview of the school district analysis
The purpose of this analysis was to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. I then repeated the school district analysis in order to come up with a more accurate report of grades in the school districts.

## Results
- How is the district summary affected?

Before the data cleanup:
<img width="806" alt="Screen Shot 2021-09-05 at 9 52 11 PM" src="https://user-images.githubusercontent.com/88108455/132149671-9bf69965-65d3-4ed3-931e-e32238dc8c05.png">

After the data cleanup:

<img width="796" alt="Screen Shot 2021-09-05 at 9 54 00 PM" src="https://user-images.githubusercontent.com/88108455/132149766-ef1709be-6313-49e5-a8e3-0dc96bb3fa28.png">

We can conclude from these images that the changes in district summary were very minor.


- How is the school summary affected?

Before the cleanup, Thomas High School's Overall Passing Percentage was 91%. After the cleanup, the Overall Passing Percentage was 65%. This is a very dramatic change!

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The ranking for Thomas High School changed from 2nd place to 8th place because its overall passing percentage decreased dramatically.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade: The total passing value decreased due to the removal of 9th grade scores.
  - Scores by school spending: the scores decreased in the $630-644 spending bucket.
  - Scores by school size: schools under 2000 students have much higher passing rates than the schools with over 2000 students.
  - Scores by school type: the top five performing schools are charter schools while the bottom five performing schools are all district schools. 
  
  
 ## Summary
 
Four changes in the updated school district analysis were seen in the Average Math and Reading Scores, % Passing Math and Reading Scores, Overall Passing Percentages, and the funding for each student. 
