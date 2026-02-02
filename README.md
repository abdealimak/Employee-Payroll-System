Employee Payroll System (C++)

A console-based C++ application to manage employee payroll using Object-Oriented Programming concepts and file handling.

Features

Add Permanent, Part-Time, and Contract employees

Automatic salary calculation

Display employee payslips

Store employee records in a file

View all employee records

Remove employee by ID

Employee Types
Permanent Employee

Basic Salary

HRA: 20%

DA: 10%

Tax: 5%

Net Salary = Basic + HRA + DA − Tax

Part-Time Employee

Hours Worked

Rate per Hour

Net Salary = Hours × Rate

Contract Employee

Fixed contract amount

Technologies Used

C++

Object-Oriented Programming (OOP)

File Handling

File Structure
.
├── main.cpp
├── employees.txt
└── README.md

File Format

Employee records are stored in employees.txt in the following format:

EmployeeID | Name | BasicSalary | NetSalary | EmployeeType

How to Run

Compile the program:

g++ main.cpp -o payroll


Run the executable:

./payroll

Menu Options
1. Add Permanent Employee
2. Add Part-Time Employee
3. Add Contract Employee
4. Display All Employees
5. Remove Employee
6. Exit

OOP Concepts Used

Inheritance

Polymorphism

Abstraction

Encapsulation

Contributions

Yatharth – Base Employee class

Rutuja – PermanentEmployee class

Abdeali – PartTimeEmployee, ContractEmployee, Main Menu

Aayush – File handling (Display & Remove records)

Future Enhancements

GUI-based interface

Graphical salary reports

Employee search feature

Report export
