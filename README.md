
# MY-LITA-JOURNEY
---
 ### PROJECT TITLE:BASICS OF EXCEL ANALYTICAL TOOL
---
### MY OUTLINE
---
#### [PROJECT OVERVIEW](#project-overview)
#### [DATA SOURCES](#data-sources)
#### [TOOLS USED](#tools-used)
#### [DATA CLEANING AND PREPARATIONS](#data-cleaning-and-preparations)
#### [EXPLORATORY OF DATA ANALYSIS](#exploratory-of-data-analysis)
#### [DATA ANALYSIS](#data-analysis)
#### [DATA VISUALIZATION](#data-visualization)

### PROJECT OVERVIEW
---
 This project will provide a foundational understanding of data analytical tools. it is designed for beginners who want to learn how to efectively use excel and SQL (Structured Query Language) for data analysis.

### DATA SOURCES:
---
The Primary source of data used here is the demo data given in class

### TOOLS USED:
---
- Microsoft [Download Here](https://www.microsoft.com)
   1. Data management
   2. Data Analysis
   3. Data Visualization
- SQL - Structured Query Language
   1. Querying of Data
- GitHub [Download Here](www.github.com)
   1. Portfolio Building

### DATA CLEANING AND PREPARATIONS:
---
In the initial phase of the data cleaning and preparations, I perform the following actions:

- Data loading and inspection

- Handling of Missing variables

- Data cleaning and formatting

### EXPLORATORY OF DATA ANALYSIS
---
Exploratory of Data Analysis involved the exploration of the Data to answer some questions about the data

### DATA ANALYSIS

---
    ~~~ CREATE TABLE Empoyee(
    staffid varchar (10) not null,
    FirstName varchar (255) not null,
    SecondName varchar (255),
    Gender varchar (10),
    Date_of_Birth date,
    HireDate datetime,
    primary key (staffid)
    )
    Select * FROM Employee
    ~~~

    ~~~ insert into Employee (staffid, firstname, secondname, gender,Date_of_Birth, hiredate)
values ( 'AB401', 'ayan', 'olakun', 'female', '1992-08-22', '2018-02-09'),
( 'AB212', 'okorie', 'mercy', 'female','1988-10-09', '2018-10-09'),
( 'AB223', 'joshua', 'chukwuemeka', 'male','1980-10-09', '2022-02-09'),
( 'AB234', 'sanni', 'ibrahim', 'male','1958-10-09', '2019-09-23'),
( 'AB254', 'mercy', 'olanipekun', 'female','1982-10-09', '2020-02-09'),
( 'AB249', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB298', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB260', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB281', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09')
~~~

### DATA VISUALIZATION:

![Query to create Employee Table](https://github.com/user-attachments/assets/9a9d371c-8958-4766-8ecd-0deff5639564)

![outcome of the above query](https://github.com/user-attachments/assets/2503a695-06a2-46ec-ad98-c6dbf1f01ff0)

