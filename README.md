# School_District_analysis
Module 4 PyCitySchools with Pandas
###### Project Overview
- Replace Thomas High Schools 9th Grade with NaNs to view and compare reading and math scores
- Analysis of the school districts spending, size and type. 
###### Resources
- schools_complete.cvs
- students_complete.cvs
- PyCitySchools_Challenge.ipynb
    - Reading and Math Scores without Thomas High School's 9th Grader
    - School district analysis
- PyCitySchools.ipynb
    - Full analysis to compare results in **PyCitySchools_Challenge** 
###### Results
**District Summary**
-![District Summary](https://github.com/robyndook/School_District_analysis/blob/e535caf0cab69bc9c03dd8ea1b9383273c01af02/Analysis/district_summary.PNG)
    - Final District Summary *Excluding* Thomas High School 9th Graders
-![District Summary with THS](https://github.com/robyndook/School_District_analysis/blob/e535caf0cab69bc9c03dd8ea1b9383273c01af02/Analysis/district_summary_with_ths.PNG)
    -Original District Summary *Inculding* Thomas High School 9th Graders
- Average Math Scores: Less 0.1
- Average Reading Scores: No Changes
- % Passing Math: Less 0.2%
- % Passing Reading: Less 0.3%
- % Overall Passing: Less 0.1%
**School Summary**
-![School Summary](https://github.com/robyndook/School_District_analysis/blob/e535caf0cab69bc9c03dd8ea1b9383273c01af02/Analysis/school_summary.PNG)
-![School Summary with THS](https://github.com/robyndook/School_District_analysis/blob/e535caf0cab69bc9c03dd8ea1b9383273c01af02/Analysis/school_summary_wth_ths.PNG)
- Average Math Scores: Less 0.1
- Average Reading Scores: No Changes
- % Passing Math: Less 0.1%
- % Passing Reading: Less 4.1%
- % Overall Passing: Less 0.3%
**Math Scores by Grade**
-![Math Scores by Grade](https://github.com/robyndook/School_District_analysis/blob/e535caf0cab69bc9c03dd8ea1b9383273c01af02/Analysis/math_by_grade.PNG)
- Thomas High 9th Grade Math removed 83.6
**Reading Scores by Grade**
-![Reading Scores by Grade](https://github.com/robyndook/School_District_analysis/blob/e535caf0cab69bc9c03dd8ea1b9383273c01af02/Analysis/reading_by_grade.PNG)
- Thomas High 9th Grade Reading removed 83.7
**Scores by School Spending**
-![Scores by School Spending](https://github.com/robyndook/School_District_analysis/blob/e535caf0cab69bc9c03dd8ea1b9383273c01af02/Analysis/school_spending.PNG)
- - % Passing Reading dropped by 0.1% for $630-644
**Scores by School Size**
-![Scores by School Size](https://github.com/robyndook/School_District_analysis/blob/e535caf0cab69bc9c03dd8ea1b9383273c01af02/Analysis/school_size.PNG)
- % Passing Reading dropped by 0.1% for Medium (1000-2000)
**Scores by School Type**
-![Scores by School Type](https://github.com/robyndook/School_District_analysis/blob/e535caf0cab69bc9c03dd8ea1b9383273c01af02/Analysis/school_type.PNG)
- % Passing Reading dropped by 0.1% for Charter Schools
###### Summary
Four main changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs
- 1. Grades and percentages dropped in District Summary except for Average Reading Scores
- 2. Percentage of Passing Reading dropped the most in the District Summary (4.1%)
- 3. Math and Reading Scores stayed the same for all other grades / schools
- 4. Percentage of Passing Reading dropped by 0.1% in School Spending, School Size, School Type. 

<!--
1. [x] Overview of the school district analysis: Explain the purpose of this analysis.

2. [x] Results: Using bulleted lists and images of DataFrames as support, address the following questions.
-[x]How is the district summary affected?
-[x]How is the school summary affected?
-[x]How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
-[x]How does replacing the ninth-grade scores affect the following:
--[x]Math and reading scores by grade
--[x]Scores by school spending
--[x]Scores by school size
--[x]Scores by school type
3. [x]Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.-->
