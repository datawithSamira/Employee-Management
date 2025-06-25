**Employee Management Project**

In this project, I worked with **employee management data**, including:

- **Employee ID**
- **Full Name**
- **Department**
- **Designation**
- **Hire Date**
- **Annual Salary**

**Project Objectives**

Analyze employee salary data across departments  
Identify top earners  
Create dynamic, interactive reports for salary distribution  
Enable flexible search and filtering of employee records

**Tasks Completed**

- **Average Salary Analysis**
  - Calculated the average annual salary across all departments
  - Determined average salaries for each specific department
  - Identified departments with the **highest** and **lowest** average salaries
- **Top Earners**
  - Identified the **top 5 employees** with the highest salary
  - Used a pivot table with:
    - _Full Name_ in the row area
    - _Annual Salary_ in the values area
  - Sorted the pivot table to easily extract the top salary earners
- **Salary Distribution Visualization**
  - Created a pivot table showing salary distribution by **designation** for each department
  - Built a **stacked column chart** for visualization
  - Added **slicers** for dynamic filtering by department and designation
- **Dynamic Search Box**
  - Implemented a **search feature** using the FILTER function:

excel

CopyEdit

\=FILTER(

A2:F41,

(ISNUMBER(SEARCH(J5, B2:B41)))

\+ (ISNUMBER(SEARCH(J5, C2:C41)))

\+ (ISNUMBER(SEARCH(J5, D2:D41))) > 0,

"No match found"

)

- - This allows dynamic filtering of rows where the search term (entered in J5) matches the **Full Name**, **Department**, or **Designation**
    - Displays "No match found" if no match is detected

**Tools Used**

- Excel / Google Sheets
- Pivot Tables & Pivot Charts
- Slicers
- FILTER, SEARCH, ISNUMBER functions

**Features**

- Interactive salary distribution chart
- Search box for flexible data lookup
- Quick identification of top earners
- Department-level salary insights
- 
##  Author

** [Samira]**  
[https://www.linkedin.com/in/samira-j-a60b8b1a0/] 

---

## License

This project is for educational/demo purposes and is provided under the MIT License.
