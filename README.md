# Pewlett Hackard Analysis
## Overview of Project
Pewlett Hackard seeks to know the total number of employees who are close to retirement age and what positions they occupy according to their title. Similarly, due to the large number of people who are about to retire, a training program will be held where employees born between January 1, 1965, and December 31, 1965, will be able to provide mentoring to new employees.
Using the ERD that we created previously, four new tables will be created, in the first table "retirement_titles" the total number of employees close to retirement will be displayed, this table gave repeated names of employees given that many of them have more than one title, later in the second table "unique_titles" shows the total number of employees showing a single title, thus avoiding having repeated employees. In the third table "retiring_titles" the total number of employees to retire by title is counted. Finally, in the "mentorship_eligibility" table, all those employees who can enter the mentoring program are filtered by age for the employees who will occupy the next vacancies.
#### Figure 1. ERD
-------
![EmployeeDB.png](https://github.com/Ricardolpz99/Pewlett-Hackard-Analysis/blob/main/EmployeeDB.png)
-------
## Results
* In Pewlett Hackard Company 72458 employees will retire soon.
* There are a large number of Senior Engineers and Senior Staff employees who are close to retirement.
* The fewest number of vacant positions are those of manager, since there are only two employees
* There are a total of 1549 employees ready to provide mentoring.

## Summary
At Pewlett Hackard there is a total of 240,124 employees of which 72,458 are about to retire, this is a large percentage of employees within the company, however we still do not know at what rate this will happen. On the other hand, there are 1,549 employees who could fulfill the role of mentors. Two other tables should be created, in the first one that shows the count of titles of those who can give mentorships, in the other table a count by titles of those who are not yet ready to retire would be made. By adding these two new tables, we will be able to see how the positions would be affected, especially those of engineering and staff.
