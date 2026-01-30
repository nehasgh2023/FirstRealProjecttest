# Total Salary Calculator - Git Demo Project

## Overview
This script reads an Excel file named `mock_data.xlsx` and calculates the total of all salaries listed in the file.

## Files
- `mock_data.xlsx` – Excel file containing employee data
- `total_salary.py` – Python script to calculate and display total salary

## How it Works
1. The script loads the Excel file using `openpyxl`.
2. It skips the header row.
3. It reads all values from the Salary column.
4. It sums them and prints the total salary.

## How to Run
```bash
pip install openpyxl
python total_salary.py
```
