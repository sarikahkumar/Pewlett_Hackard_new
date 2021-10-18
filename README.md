# Pewlett Hackard Analysis

## Overview of the analysis

This is an analysis of the employee database of Pewlett Hackard for future-proofing the company for the upcoming "silver tsunami". This analysis provides the following:

- (i) Number of retiring employees per title

- (ii)Employees who are eligible to participate in a mentorship program.(The company's proposed mentoring program requires the current employees who were born between January 1,    1965 and December 31, 1965)

--
## Results
---
A complete list of employees who will be retiring i.e who are born between January 1, 1952 and December 31, 1955 was created and is provided as a csv file named retirement_titles.csv in the Resources folder of this repository. As there were employees who held multiple positions/titles, a file named as unique_titles.csv was also created that contains the employee number, first and last name, and most recent title of the above retiring employees.The number of employees retiring, based on titles was also created, named as retiring_titles.csv for detailed analysis purpose. A sample of employees retiring (unique data) tables are given below.

---
[unique_titles.csv](https://github.com/sarikahkumar/Pewlett_Hackard_new/files/7361189/unique_titles.csv)

---

Based on these data, it was found that,
  - 90398 employees were retiring from the company
  - 29414 Senior Engineers,28254 Senior Staff,14222 Engineer,12243 Staff,4502 Technique Leader,1761 Assistant Engineer, and 2 Managers were found to be retiring
---
A mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965 was created and exported to mentorship_eligibilty.csv (saved in  Resources folder)

---	
[mentorship_eligibility.csv](https://github.com/sarikahkumar/Pewlett_Hackard_new/files/7361193/mentorship_eligibility.csv)

---
Based on the above, it was found that,
  - 1549 current employees were eligible for the mentorship program.
  - Out of these, 78 Assistant Engineers, 501 Engineers, 169 Senior Engineers, 569 Senior Staff, 155 Staff and 77 Technique Leaders eligible for mentorship program (An       additional table containing available mentors based on title styled as "mentorship_titles" was created to provide a detailed outlook)

## Summary
---
A summary of the analysis based on the questions is given below:

How many roles will need to be filled as the "silver tsunami" begins to make an impact?

---
90398 positions will need to be filled up. More specifically,29414 Senior Engineers,28254 Senior Staff,14222 Engineer,12243 Staff,4502 Technique Leader,1761 Assistant Engineer, and 2 Managers are retiring.

---
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

---
Out of the current employees, around one-third are retiring, and to mentor the next generation of employees, only 1549 employees are available. Therefore, it can be concluded that the Pewlett Hackard does not have enough experienced employees for mentoring the next generation, considering the size of the company.

---
  - Two queries for creating 2 new tables containing department wise retirees and department wise mentors available, were created to provide an insight into hich department    requires more attention to address the "Silver tsunami".
  - Department wise retirees table is styled as "department_retirees" and csv file is department_retirees_Deliverable3.csv
  - Department wise available mentors table is styled as "department_mentors" and csv file is department_mentors_Deliverable3.csv
