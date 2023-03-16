# pandas-challenge

Sean Guzman

Rutgers Data Sciences Bootcamp, Module 4 Challenge (20 March 2023)


In this analysis, data is taken from a school district where a series of calculations are performed to determine its success as a district, as well as by school, type of school, school spending.  The data is broken down even further by grade to uncover any trends as students progress through high school.  

Key Takeaways and Conclusions
- As a district, it averaged a 78.99 for Math and 81.88 for Reading. While the majority passed each subject respectively (Math - 74.98%, Reading 85.81%), only 65% of students passed both.
- Scores for both Math and Reading appear to stay relatively the same throughout high school.
- Spending more per student does not necessarily yield higher Overall Passing Percentages as shown in the spending summary dataframe but given the data, schools with smaller student populations have a higher Overall Passing Percentage despite having smaller budgets as shown in the school summary dataframe.
- Further validating the previous point, the 5 highest-performing schools of passing overall are charter schools (where budget and size are both smaller), whereas the lowest-performing are district schools.  Charter schools excel in all categories [ Average Math Score, Average Reading Score, Passing Math Percentage, Passing Reading Percentage, Overall Passing Percentage ] over district schools as shown in the type_summary dataframe.
- Scores and percentages in all categories [ Average Math Score, Average Reading Score, Passing Math Percentage, Passing Reading Percentage, Overall Passing Percentage ] improve signifcantly depending on size/number of students as shown in the size_summary dataframe. Higher marks in these categories can be seen Medium size schools (1000-2000 students) versus Large size schools (over 2000 students).  However, little improvement can be seen, if any, when comparing Medium size schools to Small size schools (less than 1000 students).