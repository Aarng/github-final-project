# Simple Interest Calculator

A simple calculator that computes the simple interest based on the given principal amount, annual rate of interest, and time period in years.

## Formula

The simple interest is calculated using the formula:

\[ \text{Simple Interest} = P \times T \times R / 100 \]

Where:
- **P** = Principal amount
- **T** = Time period in years
- **R** = Annual rate of interest (percentage)

## Input
The program requires the following inputs:
- `P`: Principal amount (numeric value)
- `T`: Time period in years (numeric value)
- `R`: Annual rate of interest (numeric value in percentage)

## Output
The program computes and returns the simple interest based on the provided inputs.

## Example Usage (Bash Script)

```bash
#!/bin/bash
# This script calculates simple interest given principal,
# annual rate of interest and time period in years.
# Do not use this in production. Sample purpose only.
# Author: Upkar Lidder (IBM)
# Additional Authors:
# <your GitHub username>

# Input:
echo "Enter the principal:"
read p
echo "Enter rate of interest per year:"
read r
echo "Enter time period in years:"
read t

# Calculation:
s=$((p * t * r / 100))

echo "The simple interest is: $s"
```

### Expected Output:
```
Enter the principal:
1000
Enter rate of interest per year:
5
Enter time period in years:
5
The simple interest is: 250
```

## Usage
This calculator can be implemented in any programming language that supports basic arithmetic operations. It can be useful for financial applications, educational purposes, or personal finance calculations.

## License
This project is open-source and available under the MIT License.

