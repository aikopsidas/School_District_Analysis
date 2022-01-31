# School District Re-Analysis
## Overview of the Analysis
Our initial work was done with all the data provided including every school, grade, and student. It was then brought to Maria's attention that the data for Thomas High School's ninth graders reading, and math grades appeared to be altered. For this reason, we refactored the previous used coding in Jupyter Notebook, 1st removing the 9th grade data at Thomas High school, making a few changes, and re-running the code. 
## Results
- Effect on the District Summary:
  - As can be seen in the images below, there was a minimal change of .1% to the average math score, the remainder was unaffected
    - Before:
    ![Previous Summary](https://github.com/aikopsidas/School_District_Analysis/blob/0b72deb7f8b099e3e8cb253db07235587b89b1a5/Resources/old_district_summary.PNG)
    - After:
    ![Updated Summary](https://github.com/aikopsidas/School_District_Analysis/blob/e3a0030118447a9551122aebd6c550c208855398/Resources/new_district_summary.PNG)
- Effect on the School Summary:
  - There was not affect on the School Summary, except specifically for Thomas High School which can be seen in the next bullet
   
- Effect on Thomas High Schools Performance: 
  - Again, we can see the affect was minimal at best on Thomas High Schools Performance
    - Before:
    ![Previous Summary](https://github.com/aikopsidas/School_District_Analysis/blob/67a3d7160aeb772351290e919fbe17d96aa808e7/Resources/old_school_summaryv2.PNG)
    - After:
    ![Updated Summary](https://github.com/aikopsidas/School_District_Analysis/blob/67a3d7160aeb772351290e919fbe17d96aa808e7/Resources/new_school_summaryv2.PNG) 
## Summary
The overall effect of removing the scores of the 9th graders of Thomas High School was very small (less than a percent), but changes were made none the less. 
- District Summary Average Math Score dropped .1%
- Thomas High School had a less than 1% change in:
  - % Passing Math
  - % Passing Reading 
  - % Overall Passing
