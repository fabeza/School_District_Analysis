# School_District_Analysis

## Project Overview
Maria, the chief data scientist for a city school district asked us to analyze datasets containing student funding and student’s standardized test scores. Our analysis  helped her showcase trends in school performance and plan for the future. We assisted Maria with the following tasks:

* Collect the student data into a DataFrame.
* Prepare a cleaned version of the DataFrame.
* Summarize key pieces of the data.
* Drill down into the data to analyze specific subsets.
* Compare and contrast the data through grouping and aggregation functions.

## Resources
We used the following resources to perform this analysis:
* Data Source: [new_full_student_data.csv](https://github.com/fabeza/School_District_Analysis/blob/842867611834781ff2f413f4ca8d1771db1eea13/Resources/new_full_student_data.csv) 
* Software: Python 3.9.12, Jupiter Notebook, Pandas

## Summary
After successful completion of the tasks mentioned above, we are pleased to share the results of the student data analysis:

* The data set had approximately 3,000 null values, which we removed to improve the accuracy of our analysis. 

![null_values](https://github.com/fabeza/School_District_Analysis/blob/ee58c0e597fee948ed7f9f7907589ceecabec398/Resources/null_values.png)

* The average reading score of all schools combined is 72.35. The lowest reading score being 10.50 and the highest is 100.00. 
* The average math score of all schools combined is 64.67. The lowest math score being 3.70 and the highest is 100.00.
* The average school budget is $893,742.75. The school with the lowest budget receives $817,615 and the school with the highest budget receives $991,918.

![school_avg](https://github.com/fabeza/School_District_Analysis/blob/ee58c0e597fee948ed7f9f7907589ceecabec398/Resources/school_avg.png)

* There was special interest in the scores of 9th grade students:
  * The average reading score for 9th grade is 69.23, the lowest reading score being 17.90 and the highest 99.90.
  * The average math score for 9th grade is 66.58 math, the lowest math score being 5.30 and the highest 100.00.

![ninth_grade_avg](https://github.com/fabeza/School_District_Analysis/blob/ee58c0e597fee948ed7f9f7907589ceecabec398/Resources/ninth_grade_avg.png)

* Dixon High School (Charter) had the student with the lowest reading score of 10.5. The student is in 10th grade and the schools’ budget is $870,334.

![lowest_reading_score](https://github.com/fabeza/School_District_Analysis/blob/ee58c0e597fee948ed7f9f7907589ceecabec398/Resources/lowest_reading_score.png)

* The average reading score for all students in grades 11th and 12th combined is 74.90.

![11_12_reading_score](https://github.com/fabeza/School_District_Analysis/blob/ee58c0e597fee948ed7f9f7907589ceecabec398/Resources/11_12_reading_score.png)

* We grouped the schools by type calculated the average budget for each school type: 
  * Charter schools have an average budget of $872,625.65.
  * Public schools have an average budget of $911,195.55.

![school_budget](https://github.com/fabeza/School_District_Analysis/blob/ee58c0e597fee948ed7f9f7907589ceecabec398/Resources/school_budget.png)

* We calculated the number of students in each school:
  * Montgomery High School has the highest number of students at 2,038 students.
  * Chang High School has the lowest number of students at 171 students.

![total_student_count](https://github.com/fabeza/School_District_Analysis/blob/ee58c0e597fee948ed7f9f7907589ceecabec398/Resources/total_student_count.png)

* Finally, we calculated the average math score by grade for each school type:
  * Charter school 9th grade students had the highest score at 70.00.
  * Public school 11th grade students had the lowest math score at 59.0.

![math_scores](https://github.com/fabeza/School_District_Analysis/blob/ee58c0e597fee948ed7f9f7907589ceecabec398/Resources/math_scores.png)

## School District Analysis Summary
It would worthwhile to deepen the analysis and find the correlation between school budget and tests scores in order to identify any budget or pedagogical insufficiencies. 

The average math score is lower than the reading score, the school district should consider evaluating its math curriculum and methodology to find any shortcomings.
