# school-district-analysis
A classwork example project analyzing standardized test data using Python
---

# Overview
In this project, I assist "the chief data scientist" for a city school district. We prepared all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns. These insights will promote discussions and decisions at the school and district level. 

Using Python, I extracted data from a csv file to create reports and visualizations. 

---

# Summary
## Math and reading scores
While Charter schools and Public schools score very closely on average in reading,

Public schools score significantly lower in math on average. 

Upperclassmen (11th and 12th graders) are, on average, scoring lower than the full school averages for reading and math.


![Math scores](/Resources/math_scores.png)

## School budgets
Public schools are spending the most on freshman students and then spend decreasingly less per grade. 

Public schools have larger budgets per grade. 

Charter schools are spending less on freshman students and increase spending per grade. 


![School Budgets graph](/Resources/school_budget.png)

## Suggestions
I believe it would be helpful to track in a new data frame: school name in the row. school_type, total_students, school_budget, average reading and math scores, and metrics of passing scores in columns. This way we could see what schools (and what type) are highly populated, which schools are successfully passing a majority of students, and funds spent per school (instead of per grade). 

I think it would also be helpful to track if Charter school upperclassmen are scoring better in math and reading than public school upperclassman due to the inverse budget spending activity observed between charter and public schools. 

Viewing which grades and schools have significant passing scores would help identify models of schools that have proven to be successful in getting the most amount of students to pass with the budget given. 
