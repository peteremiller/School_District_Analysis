<img src="Resources/readmeimage2.jpg">

# PyCity Schools: School District Analysis Overview
Maria, the chief data scientist for PyCity School District, has requested my help analyzing data on student funding and student's standardized test scores. The task is to aggregate the student data and showcase trends in performance to assist the School Board and Superintendent in making decisions regarding school budgets and priorities. 

Maria was notified by the school board that the analysis we initially completed shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. After I replaced the math and reading scores, I repeated the school district analysis and a m now prepared to present this written report that will describe how these changes affected the overall analysis. 

The purpose of our analysis is to find the overall passing percentages of the students and see if there is any correlation with the budget per student. The analysisi has uncovered that some of the test scores from the 9th grade students at Thomas High School are missing. Since these values are missing we want to take all of the scores from this one high school so that the questionable data will have the least amount of influence on the district summary findings.


# Results
#How is the district summary affected?

After taking a look at both district summaries from pycityschools and pycityschools_challenge there is not a change.

#How is the school summary affected?

The over all passing for Thomas High School was 90.94% in pycityschools, with the 9th graders taken out the overall passing shrinks by 0.3 %.

#How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Overall it does not affect either the reading scores or math scores. We are doing an investigation because we believe they are not including most of the 9th graders scores because they might bring the school even further down in test scores.

#How does replacing the ninth-grade scores affect the following: #Math and reading scores by grade

The only difference now between the scores is that under 9th graders who attended Thomas High School it shows an NaN.

#Scores by school spending

The numbers stay nearly identical since the 9th graders are nullified from the statistics.

#Scores by school size

Overall passing percentage does not change.

#Scores by school type

Scores by school type are not altered at all.

# Summary

After we have replaced the scores of the 9th grade students we learn that not much has changed. We have nullified the values that we felt would alter size,district, spending and overall passing percentage of the students.

______________________________________________________________________________

The analysis should contain the following:

Overview of the school district analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type
Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
