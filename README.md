# EMPLOYEE-DATA
This was one of the hands-on class activity database created by inputting data

---
### EMPLOYEE DATA COMPILATION - SQL CLASS ACTIVITY
---

### Table of Contents

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Visualisation](#data-visualisation)


### Project Overview
---

This data analysis shows some of the steps taken in compilation of raw data inputed to create a data base of Employees in an Organisation. Each steps involves the creation of codes (Line of codes) to create several tables which was joined together to form a comprehensive list of Employee data in an Organisation.


### Data Sources
---

Raw sources of data were complied to form a data base of the Employee in the organisation. The data shows the name of the employees, their employment ID, Salary, department, Account details, Bank name, Age, state of origin  and all other Employee data.


### Tools Used
---

- Structured Query Language- SQL
- Github


### Data Cleaning and Preparation
---

A database was first created , then a an Employee table with various headings to arrange each details in the columns. in addition, the Salary, Person and Payment tables with corresponding data were created. thses tables were joined together using the Inner Join to form a full database of the Employee.


### Exploratory Data Analysis
---

 Using EDA, lots of insights were gotten from the data generated using SQL Syntax. A lot of insights like
 - Which Employee has the highest salary?
 - What would the new salary be if increased by 5%?
 - Which of the employee earns between a certain range of salary?
 - How many employee are from a certain state of origin?
 - What is the number of employees in each department?


### Data Analysis
---

This is where we include several codes during analysis. Codes like

Create database LITA_DB

Create table Person

Select * from table Employee

Insert into Payment (account_no,Staffid,payment_method) values (2033030303, 'AB200', 'Transfer'),

SELECT * FROM Payment WHERE Payment_Method = 'Cash'

SELECT COUNT(*) FROM EMPLOYEE WHERE STATE_OF_ORIGIN = 'LAGOS'

SELECT STAFFID, SALARY FROM SALARY WHERE SALARY < 700000

SELECT MAX(SALARY) FROM SALARY

select count(staffid), department from Salary GROUP BY DEPARTMENT

SELECT * FROM SALARY WHERE SALARY NOT BETWEEN 500000 AND 900000

From Employee LEFT JOIN Salary ON Salary.Staffid = Employee.Staffid


### Data Visualisation


![SQL SCREEN 2](https://github.com/user-attachments/assets/888cbf32-b7b6-4649-bb13-350a37d2a33b)


![SQL SCREEN 3](https://github.com/user-attachments/assets/9f07cc32-2137-470b-8a1e-271c3a745971)


![SQL SCREEN 4](https://github.com/user-attachments/assets/7daa6d3e-f9da-43a1-afe9-6e5000d1d187)



![SQL 5](https://github.com/user-attachments/assets/18a71928-1de8-463a-8042-1ce904ffe354)


