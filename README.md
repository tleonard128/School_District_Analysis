# School District Analysis
## Purpose 
Using Python's pandas library, I analyzed standardized testing scores data for a school district based on different attributes amongst schools and students. After analyzing the data inititally, the school board found that some of the test scores had been altered, so I manipulated the dataset to remove the incorrect data and reran the analysis with the new data to get more a more accurate analysis.

## Results
The following list of questions and answers explains how the analysis changed when the altered test scores were removed from the dataset.
- How is the district summary affected?
  - The district summary remaned mostly unchanged after the scores for 9th Graders at Thomas High School were replaced. The overall percentage passing math and reading both slightly dropped and the overall passing percentage only decreased by 0.1%

    **Before**
![image](https://user-images.githubusercontent.com/49666078/168406958-5feefe14-4f46-493c-a6bf-db0043fc89d6.png)

    **After**
![image](https://user-images.githubusercontent.com/49666078/168406887-c8a55dc7-ce69-429a-bbe5-152f8bf213b1.png)

- How is the school summary affected?
  - The only affect on the school summary is for Thomas high school where a minimal change was scene. All of the scores were altered by less than 1%.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Replacing the scores from the ninth graders with null values did not affect Thomas High School's performance relative to other schools as it still ranked as the second school in the list. 
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade: The only affect that replacing the scores for ninth-graders is that now the column shows as Nan for 9th graders at Thomas High School where previously this value showed a value of 83.6 for math and 83.7 for reading.    
  - Scores by school spending: There was no changed to the data on school spending after the scores were replaced.
  - Scores by school size: There was no changed to the data on school size after the scores were replaced. Small and medium schools still performaed much higher than larger schools (schools with more than 5000 students).
  - Scores by school type: There was no change to the data on school type after the scores were replaced. Charter schools still out performed district schools by a large margin.

## Summary
Four changes that occured after replacing the math and reading scores are as follows: 
- There was no longer data on 9th grade student test scores from Thomas High School in the analysis.
- Even though there were minimal changes to the summary data, the data is now more accurate due to the fact that there were no altered scores in the data set.
- Thomas high schools overall percentage of passing was slightly lowered but not by more than 1%.
- The amount of students at Thomas high school did not change, however the amount of students with useable test score data at Thomas High School decreased from 1174 to 1094 since all of the 9th grade scores were replaced with Nan's
