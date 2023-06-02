**SQL Assignments**


**Q1 (Creating Database and Tables) :**

	Question-1
	• Connected with SQL server database engine using SSMS.
	• Created database as school using query and Student database without using query.
	• Created a backup file of database and dropped the database using Drop query.
	• Backup file was restored from SQL server.
	• AdventureWork2019 Db was restored from web source.
	• Applied filters for Sales table.

 	 Question-2
	• Created table Locations with country_id,country_name and region_id columns.
	• Renames the table name as Locations_new from Locations.
	• Added a column region_name in Locations table using ALTER query.
	• Added a column ID to the table Locations.
	• Added a column state_province to the table Locations.
	

**Q2 (Constraints) :**

	• Created table as job_details with Not null constraint.
	• Inserted values to the table job_details.
	• Displaying the table using select query.
	• Created the table as order_details with Unique constraint.
	• Inserted values to order_details table.
	• Displaying the table using select query.
	• Created table job_deatils2 with 2 Unique,Not null constraints for agent_code and agent_name.
	• Inserted values to job_details table.
	• Created table customer_deatils with Unique constraint Unique,Null,Not null.
	• Displaying the table using select query.
	• Created table agent_com with Unique, Check constraints for agent_code, agent_name, commission with conditions.
	• Inserted values to agent_com table.
	• Altered the commission condition using Alter query to > 2.
	• Selecting the details for only working_area in London.Mumbai,Brisban.
	• Selecting the data for commissions < 1.
	• Created the table with different sizes in datatypes.
	• Inserting the values to agent_3 table.
	• Created table agent_4 with working_area is London,New york,or Mumbai.
	• Commission conditions applied by creating Constraint.
	• Inserted values to table agent_4.
	• Displaying the table using select query.

**Q3 ( Distinct Where clause)**

	• Created table salesman with Salesman_ID, Name, City, Commission.
	• Added auto increments for Salesman_ID.
	• SQL query to display all the information from the Salesman table.(using where clause)
	• SQL query to display distinct city from—To  the Salesman table.
	• SQL query to display all distinct rows from the Salesman table.
	• SQL query to display distinct name and city from Salesman table.
	• SQL query to display all records but city should be "Paris"
	• SQL query to display all records but city is "Paris" and commission is  greater than 0.14.
	• Added ascending using order by.
	• SQL query to display all records except San Jose city.

**Q4 (Aggregate functions)**

	• Created a table Persons with column names as  Personid, Last Name, First Name, Age.
	• Created a table Orders with column names as  Order Id, Order Number, Person Id.
	• Restored database AdventureworksDW2019 .
	• Sorted the LastName as ascending order and LastName column as first column from Dim Customer table.
	• SQL query to show top 20 Products from DimProduct Table.
	• SQL query to show 50 percentage of customers.
	• To find Minimum and Maximum yearly income from DimCustomer Table.
	
**Q5 ( Wildcard characters)**

	• SQL query to Select distinct records of EmailAddress .
	• EmailAddress having a letters combination "vi" from DimEmployee table.
	• SQL query to find english product name starts with 'b' and ends with 'e'.
	• English product names have "r" in the second position.
	• Working as 'Accountant' and 'Chief Financial Officer' from Title colum from DimEmployee table.
	• Aliase statement to show FirstName and LastName  as Employee Full Name.
	• Minimum unit price from UnitPrice column in FactInternetSales.(Aggregate function)
	• Total sales amount from SalesAmount column in FactInternetSales.
	• Average tax amount from Taxamt column in FactInternetSales.
	• FirstName and Birthdate, the birth date range between 01-01-1980 to 31-12-1985.
	
**Q6 (Joins)**

	• Created table as Employee_deatils and Project details.
	• Selecting details of employee those already assigned the projects using joins.
	• Selecting details of employee those even not assigned the projects using joins.
	• project name they have not matching any employeeid, in left table, order by firstname.
	• Completed record of employees and project details.

**Q7 (Union Concepts)**

	• Created Employee table with Id,name,Deptid,Salary.
	• Average salary in Dept wise is shown using aggregate function.
	• Having condition on Average Salary > 3000 and show the result.
	• Created department table with deptid,name,location.
	• Join on Employee and Department tables using the common column DeptID.
	• SQL query to display Dname, Avg. salary of Each dept. using Joins and Group by Clauses.
	• FirstName and BirthDate and birthdate should be between 01-01-1985 to 01-12-1985.

**Q8 (Join Groupby)**

**Question 1**

	• Created table EmployeeDetails EmployeeID, FirstName, Salary, LastName, JoiningDate, Department, Gender.
	• FirstName in upper case as "First Name". 
	• Combine FirstName and LastName and display it as "Name".
	• Employee details from EmployeeDetail table whose "FirstName" contains 'k' .
	• Employee details from EmployeeDetail table whose "FirstName" end with 'h' .
	• Employee detail from EmployeeDetail table whose "FirstName" not start with’a-p’.
	• Employee detail from EmployeeDetail table whose "FirstName" start with 'A' 
		and contain 5 letters.
	• Unique "Department" from EmployeeDetail table.
	• Highest "Salary"  & Lowest "Salary" from EmployeeDetail table.
	• First name, current date, joiningdate and diff between current date 
		and joining date in months.
	• Employee details from EmployeeDetail table whose joining year is 2013.
	• Employee details from EmployeeDetail table whose joining month is Jan(1).
	• Employee details from EmployeeDetail table whose joining date 
		between "2013-01-01" and "2013-12-01".
	• All employee detail with First name "Vikas","Ashish", and "Nikhil".
	• First name and Gender as M/F.(if male then M, if Female then F)(case is used).
	• First name from "EmployeeDetail" table prifixed with "Hello ".
	• Employee details from "EmployeeDetail" table whose Salary less than 700000.
	• employee details from "EmployeeDetail" table whose Salary between 500000 than 600000.
	• Second highest salary from "EmployeeDetail" table.

**Question 2**

	• Created projectDetails table with ProjectID,EmployeeID,Projectname.
	• The query to get the department and department wise total(sum).
	• The query to get the department and department wise total(sum) in descending order.
	• Total no. of departments, total(sum) salary with respect to department from "EmployeeDetail" table.
	• Average salary from "EmployeeDetail" table order by salary ascending.
	• Maximum salary from "EmployeeDetail" table order by salary ascending.
	• Employee name, project name order by firstname from "EmployeeDetail" and "ProjectDetail" for those employee which have 			assigned project already.
	• Employee even they have not assigned project.
	• Project name even they have not matching any employeeid, in left table, order by firstname from "EmployeeDetail" and 			"ProjectDetail".
	• Complete record(employeename, project name) from both tables.
	• The query to fetch EmployeeName & Project who has assign
		more than one project.
