# EmployeePayrollSystem
A simple Java console application to manage employee records and automate payroll calculation. This project simulates real-world salary processing with automatic computation of HRA, DA, tax, bonus, and net salary for each employee.


# 💼 Employee Payroll Management System

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Status](https://img.shields.io/badge/status-Completed-brightgreen?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Console-blue?style=for-the-badge)

A console-based Java application to manage employee records and automate salary calculations. This project simulates a simplified payroll system using core Java concepts like OOP, HashMap, and basic salary computation logic (HRA, DA, tax, bonus).

---

## 📌 Features

- ✅ Add new employee records
- ✅ Auto salary breakdown (HRA, DA, Tax, Bonus)
- ✅ Calculate net salary
- ✅ Search employee by ID
- ✅ Display all employee records
- ✅ User-friendly console menu

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Java       | Core Programming Language |
| HashMap    | To store employee records |
| Scanner    | For user input in console |
| OOP        | To structure the logic using classes and objects |

---

## 📁 Project Structure

```bash
PayrollManagementSystem.java
└── Employee class
    ├── Fields: id, name, basicSalary, hra, da, tax, bonus, netSalary
    └── Methods: calculateSalary(), display()
└── Main class: PayrollManagementSystem
    ├── Menu-driven user interface
    ├── addEmployee(), displayAllEmployees(), searchEmployeeById()
```

---

## 💻 Sample Output

```
--- Employee Payroll Management System ---
1. Add Employee
2. Display All Employees
3. Search Employee by ID
4. Exit

Enter your choice: 1
Enter Employee ID: 101
Enter Name: John
Enter Basic Salary: 30000

Employee added successfully!

--- Employee Details ---
ID         : 101
Name       : John
Basic Pay  : 30000.0
HRA        : 6000.0
DA         : 3000.0
Bonus      : 1500.0
Tax        : 2400.0
Net Salary : 38100.0
```

---

## 🎯 Concepts Demonstrated

- **Encapsulation**: Employee details encapsulated in a class
- **Abstraction**: Salary calculation hidden behind method calls
- **HashMap Usage**: Fast employee lookup using ID
- **Modular Programming**: Separated logic into clean functions

---

## 📈 Future Scope

- 📁 Store employee data in files or databases (MySQL + JDBC)
- 🧾 Export payslips to PDF/Excel
- 🖥️ Build GUI using Swing/JavaFX
- 💠 Add update/delete functionality
- 🔐 Add login system for HR/Admin role

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/employee-payroll-system.git
   ```
2. Compile the Java file:
   ```bash
   javac PayrollManagementSystem.java
   ```
3. Run the program:
   ```bash
   java PayrollManagementSystem
   ```

---

## 🤛 Author

**Nivas A**  
🔗 [LinkedIn](https://www.linkedin.com/in/a-srinivas-9b1986272/)  
📧 [annavarapusrinivas3@gmail.com]  
💻 Java Enthusiast | Beginner Java Projects Contributor

---

## ⭐ Give a Star

If you found this project useful, please ⭐ star this repo to support the work!
