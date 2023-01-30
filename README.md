# Pewlett-Hackard-Analysis

## Overview of the analysis:
The purpose of this analysis was to use the postgreSQL tool called pgAdmin to gather the necessary data for employees at Pewlett Hackard nearing retirment eligibility and to fill the job positions they will be leaving behind. We map out the relationship in data by building entity relationship diagrams in a quick database diagram app (DBD) so we can better assign primary and foreigh key used to build our specified tables of information. The SQL code can be tailored to the desired information needed so we can filter data by department, managers, employees, salaries, and job titles.

## Results:
We begin by performing the JOIN function to merge employees table and the titles table into a new table displaying the titles of employees who are coming up on the their retirment dates. Listed below is a filter image for the retirement titles table that holds all the titles of employees who were born between January 1, 1952 and December 31, 1955.

![Deliverable1](https://user-images.githubusercontent.com/118647523/215585354-8971f066-4eb1-417a-85ad-eea8f8722f6b.png)

The DISTINCT function was then performed to filter out or exclude duplcates of the retiring employees who carried multiple jobs within the company and left the company before January 1, 1999.

![Deliverable1-2](https://user-images.githubusercontent.com/118647523/215585363-518e12b3-04ea-4941-a44f-978f9875af60.png)

After querying the necessary data we are able to generate the total number of employees by their most recent job title who are about to retire in all fileds. We can see from the image below that there is a total of 72458 employees who will be retiring from Pewlett Hackard. 

Here are some obvious takeaways from the retiring titles table generated:
  * Most of the seniors employees have the highest amount of upcoming retirments throughout the company totaling almost 50k.
  * Only very few managers at Pewlett Hackard will be retiring soon.
  * The general employees including technique leaders, engineers, and staff have an average amount of employees retiring anywhere from 1k-10k per group.

![Deliverable1-3](https://user-images.githubusercontent.com/118647523/215585376-9e63171a-2495-46c1-bfc8-04e54c1951be.png)

Using the entity relationship diagram built we create a new table to analyze which employees are eligible to participate in the mentorship program. The employee table, department employees table, and titles table were joined together through specific dates to list the data needed for eligibility. .

  * The employees eligible for the mentorship program were filtered for people born in the year 1965.
  * The table columns list the employee number, first & last name, birth date , and job title. 

![Deliverable2](https://user-images.githubusercontent.com/118647523/215585386-1c346a84-00bf-4f9d-b0d6-f6ee3901b7ba.png)

## Summary:
The summary addresses the two questions and contains two additional queries or tables that may provide more insight. (5 pt)
