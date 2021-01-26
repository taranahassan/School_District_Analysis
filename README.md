# School_District_Analysis

## Overview of School District Analysis

The Chief Data Scientist of a city School District, Maria has been tasked with preparing data from the students' standardized test scores.  This data will be used for analysis; which includes reporting and presenting to each school and district levels.  This information will initiate informed discussions and strategic decisions about the proficiency of city schools testing.  
Maria has asked us for assistance in analyzing the data further to analyze student funding and student standardized test scores.  We have aggregated the data and showcased trends in school performance based on categories which will help the school board and superintendants make decision regarding school budgets and alocations.

After compiling data from 2 sources, we obtained:
  
  *1.  District Summary - provides a snapshot of the districts' key metrics*
  
  *2.  Per School Summary - provides key metrics for each school*
  
  *3.  A table presenting the top 5 and bottom 5 performing schools based on overall students passing*
  
  *4.  Average math and reading scores in each grade, each school*
  
  *5.  School performance based on budget per student*
  
  *6.  School performance based on school size*
  
  *7.  School performance based on school type*
  

After the original analysis was stated above, we were advised that there was a discrepency on the math and reading scores for the 9th grade students attending the Thomas High School.  The results noted below are based on the revised outcome.

### Resources used:
[schools_complete.csv](https://github.com/taranahassan/School_District_Analysis/blob/main/Resources/schools_complete.csv)

[students_complete.csv](https://github.com/taranahassan/School_District_Analysis/blob/main/Resources/students_complete.csv)

*After verifying and cleaning data* clean_students_complete.csv](https://github.com/taranahassan/School_District_Analysis/blob/main/Resources/clean_students_complete.csv)


## School Analysis Results
Firstly we removed all the scores for grade 9 students for Thomas High School which was a total of 461 students.  The following are the effects of the new analysis.
  
  **1.**  Below are the screenshots of the District summary - providing a snapshot of the total population, budget, average scores and passing rates for the entire district.  The 9th grade from Thomas High amounted to 1.17% of the total student population.


**Original District Summary:**

![Original_District_summary](https://github.com/taranahassan/School_District_Analysis/blob/main/Screenshot_examples/Original_District_summary.png?raw=true)


**Revised District Summary:**

![Revised_District_summary](https://github.com/taranahassan/School_District_Analysis/blob/main/Screenshot_examples/Revised_District_summary.png?raw=true)
  
  
  **2.**  There are a total of 1635 students at Thomas High School.  73% of the students are from grade 10th to 12th.  Once we eliminated the grade 9 scores, the percentage of students passing each subject or both together dropped by an average of 26%, since the calculation was still taking the total number students into account.  
  
**Original Per School Summary:**

![Original_School_summary](https://github.com/taranahassan/School_District_Analysis/blob/main/Screenshot_examples/Original_Per_School_summary.png?raw=true)

However, after recalculating with only the number of students with scores at Thomas High School, the passing percentages was barely impacted by an average of .37%.  Below are the screenshot of the summaries with the grade 9 as student count but no scores, and without the grade 9 students completely out of the calculation.

**Revised Per School Summary without grade 9 scores:**

![Revised_Per_School_summary_without_9th_scores](https://github.com/taranahassan/School_District_Analysis/blob/main/Screenshot_examples/Revised_Per_School_summary_without_9th_scores.png?raw=true)


**Revised Per School Summary without grade 9 students:**

![Revised_Per_School_summary_without_9th_grade](https://github.com/taranahassan/School_District_Analysis/blob/main/Screenshot_examples/Revised_Per_School_summary_without_9th_grade.png?raw=true)
  
  
  **3.**  After the revised analysis with the 9th grade scores replaced the overall passing percentage for the school was at 65%, it would have placed Thomas High School within the bottom 10 schools, placing them at the 8th position.  However once the scores were replaced and taking the grade 9's out of the equation, the school falls within the top 5 performers, placed 2nd on the list as the original analysis.  


**Top 5 schools list:**

![Revised_top_5_schools](https://github.com/taranahassan/School_District_Analysis/blob/main/Screenshot_examples/Revised_top_5_schools.png?raw=true)
  
  
  **4.**  Effects of replacing the grade 9 scores for Thomas High School:
  
  -  The math and reading scores by grade tables didn't change since the grouping was done by each school.  Even without grouping, the effect would have been minimal since  the      9th graders at Thomas High School amount to less than half a percent of the total 9th grade population in the district.
  -  No changes to the School Spending Summary.
  -  No changes to the School Size Summary.
  -  No changes to the School Type Summary.


## School District Analysis Summary

Overall the discrepency of the scores impacted the entire analysis.  The revised analysis would not be a true statement as we are not calculating the actual true student population for this district.  Though the student count of 461 from 9th grade attending Thomas High is minimal compared to a total of 39,170 students; their true scores may still impact the results positively or negatively.  

  **1.**  The performance for Thomas High individually situates them at the second place in the top 5 schools list.  This may change if we had the actual results from the 9th grade.  The results may put them in the bottom producing schools.

  **2.**  The performance results on each grade level may be impacted as well.  Currently the results have the 9th grade per school performing at the same rate.  Actual results may show Thomas High's 9th grade performing better or worse than the other schools.
  
 **3.**  Based on the performance the budget per student may change as well which will impact the decision for the school boards funding allocation.  The true results may change the averages and the passing percentages, placing them in the next higher or lower bin of spending.
  
  **4.**  Once the true results from Thomas High's 9th grade is received, and if the averages are low, this may pull the overall passing rate down for the school itself, trickling down and change the results of the School Type summary.  We may see District schools out performing the Charter schools.
  
