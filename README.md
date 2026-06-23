# Financial Security Calculator

A secure Python application providing investment and home loan repayment calculations with robust input validation and error handling.

## Security Features

- **Input Validation**: Prevents malformed data from causing crashes or unexpected behavior
- **Type Safety**: Strict float/integer parsing with graceful error handling
- **Boundary Checking**: Validates reasonable ranges for financial inputs
- **Exception Handling**: Prevents Denial of Service (DoS) via unexpected input crashes
- **Secure Float Parsing**: Protection against floating-point manipulation attacks

## Features

- **Investment Calculator**: Calculate compound interest with monthly/annual contributions
- **Home Loan Repayment Calculator**: Calculate monthly repayments and total interest
- **Input Sanitization**: All user inputs are validated before processing

## Tech Stack

- Python 3.x

## Installation

```bash
git clone https://github.com/ZeakMeadows/financial-security-calculator.git
cd financial-security-calculator
python financial_calculator.py
