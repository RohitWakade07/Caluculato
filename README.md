# Caluculato
# Simple Interest Calculator

## Introduction
A Simple Interest Calculator is a basic program that calculates the simple interest on a principal amount based on the annual interest rate and time period.

## Formula
Simple Interest (SI) is calculated using the following formula:

**SI = (P × R × T) / 100**

Where:
- **P** = Principal amount
- **R** = Annual rate of interest (in percentage)
- **T** = Time period (in years)

**Total Amount = Principal + Simple Interest**

## Python Program

```python
# Simple Interest Calculator

principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the annual interest rate (%): "))
time = float(input("Enter the time period (in years): "))

simple_interest = (principal * rate * time) / 100
total_amount = principal + simple_interest

print("Simple Interest:", simple_interest)
print("Total Amount:", total_amount)
```

## Example

Suppose:
- Principal = 1000
- Rate = 5%
- Time = 2 years

Calculation:

SI = (1000 × 5 × 2) / 100 = 100

Therefore:
- **Simple Interest:** 100
- **Total Amount:** 1100

## How to Run
1. Install Python 3 on your computer.
2. Copy the program into a file named `simple_interest.py`.
3. Open a terminal in the file's directory.
4. Run the command:

   ```bash
   python simple_interest.py
   ```

5. Enter the principal amount, annual interest rate, and time period when prompted.

## Features
- Calculates simple interest quickly.
- Accepts decimal values.
- Displays both simple interest and total amount.
- Beginner-friendly Python implementation.

## Technologies Used
- Python 3
- GitHub for version control and project hosting

## License
This project is available for educational and personal use.
