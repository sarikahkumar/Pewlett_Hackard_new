# Pewlett Hackard Analysis

## Overview of the analysis

This is an analysis of the employee database of Pewlett Hackard for future-proofing the company for the upcoming "silver tsunami". This analysis provides the following:

-  Number of retiring employees per title

- Employees who are eligible to participate in a mentorship program.(The company's proposed mentoring program requires the current employees who were born between January 1,    1965 and December 31, 1965)

Please note that the analysis was done using SQL
## Results

A complete list of employees who will be retiring i.e who are born between January 1, 1952 and December 31, 1955 was created and is styled as _retirement_titles_. As there were employees who held multiple positions/titles, another table styled _unique_titles.csv_ was also created that contains the employee number, first and last name, and most recent title of the above retiring employees.The number of employees retiring, based on titles was also created, named as _retiring_titles_  for detailed analysis purpose. 
Please click on the following to view the csv files.

[retirement_titles.csv](https://github.com/sarikahkumar/Pewlett_Hackard_new/files/7361219/retirement_titles.csv) , 
[unique_titles.csv](https://github.com/sarikahkumar/Pewlett_Hackard_new/files/7361189/unique_titles.csv) ,
[retiring_titles.csv](https://github.com/sarikahkumar/Pewlett_Hackard_new/files/7361220/retiring_titles.csv)

A snapshot of the retiring employees based on titles is given below:

 ![retiring_titles](https://user-images.githubusercontent.com/89427676/137653331-79ce11dd-7d2a-426e-aabe-1db71b818ea8.PNG)
 
Based on these data, it was found that,
  - 90398 employees were retiring from the company
  - 29414 Senior Engineers,28254 Senior Staff,14222 Engineer,12243 Staff,4502 Technique Leader,1761 Assistant Engineer, and 2 Managers were found to be retiring
---
A mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965 was created. Please click on the following link to view the file.

[mentorship_eligibility.csv](https://github.com/sarikahkumar/Pewlett_Hackard_new/files/7361193/mentorship_eligibility.csv)

![mentorship_eligibility](https://user-images.githubusercontent.com/89427676/137652504-d153e14d-5cbd-4a34-a803-414c2f287460.PNG)

Based on the above, it was found that,
  - 1549 current employees were eligible for the mentorship program.
  - Out of these, 78 Assistant Engineers, 501 Engineers, 169 Senior Engineers, 569 Senior Staff, 155 Staff and 77 Technique Leaders eligible for mentorship program (An       additional table containing available mentors based on title styled as "mentorship_titles" was created to provide a detailed outlook)

## Summary

The analysis revealed the following:

1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?

90398 positions will need to be filled up. More specifically,29414 Senior Engineers, 28254 Senior Staff, 14222 Engineer, 12243 Staff, 4502 Technique Leader, 1761 Assistant Engineer, and 2 Managers are retiring.

2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

Out of the current employees, around one-third are retiring, and to mentor the next generation of employees, only 1549 employees are available. Therefore, it can be concluded that the Pewlett Hackard does not have enough experienced employees for mentoring the next generation, considering the size of the company.

---
### Additional queries for detailed analysis

  - Two queries for creating 2 new tables containing department wise retirees and department wise mentors available, were created to provide an insight into which department    requires more attention to address the "Silver tsunami".
  - Department wise retirees table is styled as "department_retirees" and csv file is department_retirees_Deliverable3.csv 
  [department_retirees.csv](https://github.com/sarikahkumar/Pewlett_Hackard_new/files/7361235/department_retirees.csv)
  - Department wise available mentors table is styled as "department_mentors" and csv file is department_mentors_Deliverable3.csv
  [department_mentors.csv](https://github.com/sarikahkumar/Pewlett_Hackard_new/files/7361236/department_mentors.csv)
