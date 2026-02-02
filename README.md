🧾 Employee Payroll System (C++)
📌 Project Overview

The Employee Payroll System is a console-based C++ application that automates salary calculation and payroll management for different types of employees.
It uses Object-Oriented Programming (OOP) concepts such as inheritance, polymorphism, abstraction, and file handling to simulate a real-world payroll system.

🎯 Objectives

Automate employee salary calculation

Reduce manual errors in payroll processing

Demonstrate core OOP concepts in C++

Store and manage employee records using files

🛠️ Technologies Used

Language: C++

Concepts:

Inheritance

Polymorphism

Virtual Functions

Abstraction

Dynamic Memory Allocation

File Handling

👥 Employee Types Supported
1️⃣ Permanent Employee

Salary based on:

Basic Salary

HRA (20%)

DA (10%)

Tax (5%)

Net Salary = Basic + HRA + DA − Tax

2️⃣ Part-Time Employee

Salary calculated using:

Hours Worked

Rate Per Hour

Net Salary = Hours × Rate

3️⃣ Contract Employee

Salary is a fixed contract amount

⚙️ Features

Add Permanent, Part-Time, and Contract Employees

Calculate salary dynamically using polymorphism

Display formatted payslips

Save employee records to a file

View all employee records

Remove employee records using ID

🗂️ File Structure
EmployeePayrollSystem/
│
├── main.cpp
├── employees.txt
├── README.md

📁 File Handling Details

All employee records are stored in employees.txt

Format:

EmployeeID | Name | BasicSalary | NetSalary | EmployeeType


Temporary file (temp.txt) is used for safe deletion of records

▶️ How to Run the Program

Compile the program:

g++ main.cpp -o payroll


Run the executable:

./payroll

📋 Menu Options
1. Add Permanent Employee
2. Add Part-Time Employee
3. Add Contract Employee
4. Display All Employees
5. Remove Employee
6. Exit

🧠 OOP Concepts Demonstrated
Concept	Usage
Inheritance	Employee → Permanent / Part-Time / Contract
Polymorphism	Base class pointer calling derived methods
Abstraction	Pure virtual functions in base class
Encapsulation	Protected data members
File Handling	Store & retrieve employee records

✅ Future Enhancements

GUI-based interface

Graphical salary breakdown

Search employee by ID or name

Salary report generation

Login system for admin

📜 Conclusion

This project successfully demonstrates how OOP principles can be applied to solve real-world problems like payroll management in an efficient and structured manner.
