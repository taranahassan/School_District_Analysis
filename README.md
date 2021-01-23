# School_District_Analysis

## Overview of School District Analysis

The Chief Data Scientist of a city School District, Maria has been tasked with preparing data from the students' standardized test scores.  This data will be used for analysis; which includes reporting and presenting to each school and district levels.  This information will initiate informed discussions and strategic decisions about the proficiency of city schools testing.  
Maria has asked us for assistance in analyzing the data further to analyze student funding and student standardized test scores.  We have aggregated the data and showcased trends in school performance based on categories which will help the school board and superintendants make decision regarding school budgets and alocations.

After compiling data from 2 sources, we obtained:
  
  1.  District Summary - provides a snapshot of the districts' key metrics
  2.  Per School Summary - provides key metrics for each school
  3.  A table presenting the top 5 and bottom 5 performing schools based on overall students passing
  4.  Average math and reading scores in each grade, each school
  5.  School performance based on budget per student
  6.  School performance based on school size
  7.  School performance based on school type

After the original analysis was stated above, we were advised that there was a discrepency on the math and reading scores for the 9th grade students attending the Thomas High School.  The results noted below are based on the revised outcome.

### Resources used:
Schools Complete CSV file - https://github.com/taranahassan/School_District_Analysis/blob/main/Resources/schools_complete.csv
Students Complete CSV file - https://github.com/taranahassan/School_District_Analysis/blob/main/Resources/students_complete.csv
*After verifying and cleaning data* Clean Students Complete CSV file - https://github.com/taranahassan/School_District_Analysis/blob/main/Resources/clean_students_complete.csv


## School Analysis Results
Firstly we removed all the scores for grade 9 students for Thomas High School which was a total of 461 students.  The following are the effects of the new analysis.
  
  1.  The District Summary key metrics was barely impacted with the revision.  The grade 9 students at Thomas High School amounted to 1.17% of the total district student        population.  Therefore the difference for average math and reading scores plus the percentages of students passing math and reading was a low of 0.1%.  Below are the snapshots comparisons of the summary before and after the changes.

Original District Summary:
![Original_District_summary
  
  2.  There are a total of 1635 students for Thomas High School.  73% of the students are from grade 10th to 12th.  Once we eliminated the grade 9 scores, the percentage of students passing each subject or both together dropped by an average of 26%, since the calculation was still taking the total number students into account.  However, after recalculating the number of students with scores at Thomas High School, the passing percentages barely changed by an average of .37%.  Below are the snapshots of the summary with the highlighted field.
  
  3.  Based on the revised analysis with the 9th grade scores replaced and the overall passing percentage sitting at 65%, it would have placed Thomas High School within the bottom 10 schools, placing them at the 8th position.  However once the scores were replaced and taking the grade 9's out of the equation, the school falls within the top 5 performers, placed 2nd on the list as the original analysis.  
  
  4.  Replacing the grade 9 scores:
    a)  Didn't affect the math and reading scores for grade 10 to 12.  And the average for all 9th graders for math and reading scores barely changed as well since the number of 9th graders in Thomas High School is less than half a percent compared to the total grade 9's for all high schools.
    b)  The spending summary didn't change as well.
    c)  The school size summary didn't change at all.
    d)  the school type summary didn't change at all.


## School District Analysis Summary

