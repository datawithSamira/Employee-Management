# Employee-Management
In this project, I have worked with employee management data, including Employee ID, Full Name, Department, Designation, Hire Date, and Annual Salary. 
The tasks I completed are as follows:
1.	Determined the average annual salary across all departments as well as for specific departments, and identified the departments with the highest and lowest average salaries.
2.	Identified the top 5 employees with the highest salary values.
3.	Created a dynamic chart to display the salary distribution by designation for each department.
To identify the top 5 employees by salary, I used a pivot table with the employees’ Full Names placed in the row area and their Annual Salaries in the values area. This allowed me to easily sort and extract the highest salary earners.
To show the salary distribution by designation for each department, I used a pivot table and created a stacked column chart. I also added slicers to enable dynamic filtering by department and designation.
Finally, the last sheet in this file displays my search box, which I created using the FILTER function to allow dynamic searching based on specified criteria.
n the last sheet, I implemented a search box using the FILTER function. The formula:
php
CopyEdit
=FILTER(
  A2:F41,
  (ISNUMBER(SEARCH(J5,B2:B41))) +
  (ISNUMBER(SEARCH(J5,C2:C41))) +
  (ISNUMBER(SEARCH(J5,D2:D41))) > 0,
  "No match found"
)
allows dynamic filtering of rows where the value entered in the search box (cell J5) is found in either the Full Name (column B), Department (column C), or Designation (column D). If no match is found, it returns "No match found".

