# Employee Directory Program

Review assignment for classes/objects, reading and writing files, and dictionaries.

**Author:** Kester Atuanya
**Date:** 9/28/2026

## What it does

- Reads employee data (ID, name, department, pay) from `employees.txt` into a list of `Employee` objects
- Adds new employees and skips duplicate IDs
- Deletes employees (prints a message if the ID doesn't exist)
- Writes the updated list back to `employees.txt`
- Puts the data in a dictionary of lists and prints it

## Files

- `employee_directory_Atuanya_Kester.py` - the program
- `employees.txt` - employee data file

## How to run

Keep both files in the same folder, then run:

```
python employee_directory_Atuanya_Kester.py
```

## Output

```
'ID:108 does not exist, deletion is aborted'
ID        : [101, 102, 103, 104, 105, 106, 107]
name      : ['JSmith', 'MJones', 'CBrown', 'TCook', 'JWhite', 'Emp1', 'Emp2']
department: ['Accounting', 'Sales', 'HR', 'IT', 'Sales', 'Accounting', 'Sales']
pay       : [75000.0, 60000.0, 55000.0, 95000.0, 70000.0, 56000.0, 80000.0]
Program is completed
```
