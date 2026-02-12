
# Compound Interest Calculator 

## Overview

This is an intermediate-level Python project that calculates compound interest based on user input. The program allows users to choose different compounding frequencies and displays the final amount along with total interest earned.

This project is ideal for beginners transitioning to intermediate Python who want to practice:
- Functions
- Input validation
- Mathematical formulas
- Clean program structure

## Features

- Calculates compound interest using the standard formula:
  
  A = P(1 + r/n)^(nt)

- Supports multiple compounding frequencies:
  - Yearly
  - Half-Yearly
  - Quarterly
  - Monthly

- Validates user input to prevent invalid entries
- Displays:
  - Principal amount
  - Final amount
  - Total interest earned

## Technologies Used

- Python 3
- Built-in functions only (no external libraries)

## Demo

https://github.com/himanihassija/compound-interest-calculator-python/blob/main/compound%20interest%20calculator.png
https://github.com/himanihassija/compound-interest-calculator-python/blob/main/compound%20interes%20calculator%202.png
## How to Run

1. Make sure Python 3 is installed on your system.
2. Clone this repository:

   git clone https://github.com/your-username/compound-interest-calculator-python.git

3. Navigate into the project folder:

   cd compound-interest-calculator-python

4. Run the program:

   python main.py

## Example Output

Enter principal amount: 10000  
Enter annual interest rate (%): 8  
Enter number of years: 5  
Choose compounding frequency: 4  

Final Amount: 14,693.28  
Total Interest Earned: 4,693.28  

## Project Structure

compound-interest-calculator-python/
│
├── main.py
└── README.md

## Learning Outcomes

By building this project, you practice:
- Writing reusable functions
- Handling user input errors
- Implementing financial formulas
- Structuring a clean CLI application

## Future Improvements

- Add yearly breakdown of investment growth
- Add graphical visualization using matplotlib
- Convert to a GUI version using Tkinter
- Build a web version using Streamlit

## License

This project is open-source and free to use for educational purposes.
