# School District Analysis

## Overview of the school district analysis: 
The purpose of this project was to assist Maria and her supervisor with school district analysis.  The original list of deliverables for the analysis of the school district are as follows: 
- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics:
  - Top 5 and bottom 5 performing schools, based on the overall passing rate
  - The average math score received by students in each grade level at each school
  - The average reading score received by students in each grade level at each school
  - School performance based on the budget per student
  - School performance based on the school size 
  - School performance based on the type of school

According to Maria, the school board notified her and her supervisor of the following:

> ...The students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. 

Specifially for this portion of the project, Maria would like the deliverables to repeat the school district analysis, replacing the math and reading scores and a report to describe how these changes affected the overall analysis.

## Results: 
- Using bulleted lists and images of DataFrames as support, address the following questions. There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data (10 pt).

-	District Summary:
  - Although Maria asked that we replace the ninth grade scores with "NaN" for Thomas High School, the District Summary numbers do not appear to be much different.	
  - Original District Summary:
  
    ![District_Summary_DataFrame_Original](Resources/District_Summary_DataFrame_Original.PNG)
    
  - Updated District Summary:  
    
    ![District_Summary_DataFrame_Updated](Resources/District_Summary_DataFrame_Updated.PNG)
    
- School Summary:
  - Original School Summary:
  
    ![THS_School_Summary_Original](Resources/THS_School_Summary_Original.PNG) 
    
  - Updated District Summary:
   - Thomas High School Including 9th Grade "NaN":

   ![THS_School_Summary_Updated_Step4](Resources/THS_School_Summary_Updated_Step4.PNG) 
   
   - Thomas High School Including Only 10th to 12th Grades:
   
   ![THS_School_Summary_Updated_Step14_10to12](Resources/THS_School_Summary_Updated_Step14_10to12.PNG)
    
-	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Top Schools Original
    ![Top_Five_Original](Resources/Top_Five_Original.PNG)
  - Top Schools Updated
    ![Top_Five_Updated](Resources/Top_Five_Updated.PNG)
  
- How does replacing the ninth-grade scores affect the following Math and reading scores by grade:
  - Scores by school spending
    - THS Spending Original
      ![THS_School_Spending_Range_Original](Resources/THS_School_Spending_Range_Original.PNG)
    - THS Spending Updated
      ![THS_School_Spending_Range_Updated](Resources/THS_School_Spending_Range_Updated.PNG)
    - Overall School Spending Formatted Same
      ![Overall_School_Spending_Summary_Formatted_Same](Resources/Overall_School_Spending_Summary_Formatted_Same.PNG)
    - Overal Spending Summary Original
      ![Overall_School_Spending_Summary_NoFormatting](Resources/Overall_School_Spending_Summary_NoFormatting_Original.PNG)
    - Overall Spending Summary Updated
      ![Overall_School_Spending_Summary_NoFormatting_Updated](Resources/Overall_School_Spending_Summary_NoFormatting_Updated.PNG)
  - Scores by school size
    - Overall School Size Formatted Same
      ![Overall_School_Size_Summary_Formatted_Same](Resources/Overall_School_Size_Summary_Formatted_Same.PNG)
    - Overall School Size summary Not formated original
      ![Overall_School_Size_Summary_NotFormatted_Original](Resources/Overall_School_Size_Summary_NotFormatted_Original.PNG)
    - Overall School Size summary Not Formatted Updated 
      ![Overall_School_Size_Summary_NotFormatted_Updated](Resources/Overall_School_Size_Summary_NotFormatted_Updated.PNG)
  - Scores by school type
    - Overall School Type Formatted Original
      ![Overall_School_Type_Summary_Formatted_Original](Resources/Overall_School_Type_Summary_Formatted_Original.PNG)
    - Overall School Type summary Formatted Updated
      ![Overall_School_Type_Summary_Formatted_Updated](Resources/Overall_School_Type_Summary_Formatted_Updated.PNG)
    - Overall School Type summary Not Formatted Original
      ![Overall_School_Type_Summary_NotFormatted_Original](Resources/Overall_School_Type_Summary_NotFormatted_Original.PNG)
    - Overall School Type summary Not Formatted Updated 
      ![Overall_School_Type_Summary_NotFormatted_Updated](Resources/Overall_School_Type_Summary_NotFormatted_Updated.PNG) 

## Summary: 
- Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. There is a statement summarizing four major changes to the school district analysis after reading and math scores have been replaced (5 pt).
- 1)
- 2)
- 3)
- 4)
-
