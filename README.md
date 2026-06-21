# Employee Salary Sheet

A simple Python program to calculate an employee's salary based on the basic salary.

## Features

- Takes employee name as input
- Accepts basic salary
- Calculates:
  - Dearness Allowance (DA = 85%)
  - Travel Allowance (TA = 15%)
  - House Rent Allowance (HRA = 15%)
  - Gross Salary
  - Provident Fund (PF = 8.33%)
  - Net Salary

## Formula Used

- DA = Basic Salary × 85%
- TA = Basic Salary × 15%
- HRA = Basic Salary × 15%
- Gross Salary = Basic + DA + TA + HRA
- PF = Gross Salary × 8.33%
- Net Salary = Gross Salary − PF

## Requirements

- Python 3.x

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/employee-salary-sheet.git
```

2. Navigate to the project folder.

```bash
cd employee-salary-sheet
```

3. Run the program.

```bash
python salary.py
```

## Example Output

```
========== EMPLOYEE SALARY SHEET ==========
Enter Employee Name: Rahul
Enter Basic Salary: 50000

========== SALARY SHEET ==========
Employee Name : Rahul
Basic Salary  : ₹50000.00
DA            : ₹42500.00
TA            : ₹7500.00
HRA           : ₹7500.00
Gross Salary  : ₹107500.00
PF            : ₹8954.75
Net Salary    : ₹98545.25
```

## Author

Subhasish Roy