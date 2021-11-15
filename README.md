# School District Analysis

## Overview of the Project
The overall purpose of this project was to aid a fellow Data Scientist named Maria in cleaning up her code and data frames that reflect information about a local school district.  Maria was informed that the grades of 9th graders at Thomas High School may have been eengaged in academic dishonesty and needs to prune their math and reading scores from the overall aveerages she dilligently coded to achieve.  Our job was to utilize knowledgee of dataframes through the Pandas dependency in Python to effectively clean and edit her data so that it reflects the required changes. 

## Results


After pruning Maria's data about the 9th graders, the following metrics were changed by the end of the project:

- The district summary had minimal changes to the average scores for math and reading but had a noticeable impact on the percentage that passed their reading class and those who passed overall (passed with both reading and math above or at 70%).  The district's percentage of students who passed reading dropped 0.1% while the % of students who passed both dipped a stark 0.3% which may not seem a lot but with over 39,000 kids the total number changed was well over 100!
  
- The summary for Thomas High school itself had a similar trajectory with the average scores for the classes but reading actually increasing by roughly 0.1% suggesting the freshmen perhaps had low scores compared to the average.  The percentage of students that passed however dipped by 0.1% for math, 0.2% for reading and 0.3% for combination of both!  It makes sense the metric changes would have a greater affect on the smaller pool of kids at Thomas High School vs the entire district at large.
  
- As stated earlier, the average math score compared to the other schools changed negligibly but the reading score actually dipped a noticeable amount!  The exclusion of the scores for the freshman for reading actually brought Thomas High School further from the average of the disctrict (81.9%) when the jumped from 83.8% to 83.9% suggesting that the school as a whole is well above the district average but that the freshmen bring them closer with their slightly lower scores.

## Summary



In summation, the exclusion of the freshman reading and math scores brought their average reading score closer to the district average despite their above average performance suggesting that they are strong in the district but weak within their own school.  At their own school, the total % of students who passed both reading and math dipped 0.3% with the averages of the frehsman absent which tells us that they had a positive contribution to the total number of passes even among other grades.  There was a similar trend when they were excluded amongst the averages of the entire district, a drop of 0.3%, which means even though they had the same affect on the average, they should be considered as greater contributors to a height of the district average because the pool of people increased dramatically in amount between just their own high school and the population of the entire disctrict!  Finally, it should be noted that there was very minute change among the average math scores when compared with the district and the school which tells us that the freshmen's average score for math was almost exactly the same when compared to the district and, more specifically, Thomas High School!
