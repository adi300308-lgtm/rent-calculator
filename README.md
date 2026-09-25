# Rent Calculator

## Overview

Rent Calculator is a simple Python-based project designed to calculate the amount each person should pay when sharing a flat. The program takes the flat rent, food expenses, electricity usage, electricity charge per unit, and number of people as input. It then calculates the total electricity bill and divides the combined expenses equally among the residents.

This project demonstrates basic Python programming concepts such as user input, variables, arithmetic operations, integer division, and output.

## Features

- Accepts flat rent from the user.
- Accepts food expenses from the user.
- Accepts total electricity units consumed.
- Accepts electricity charges per unit.
- Accepts the number of people living in the flat.
- Calculates the total electricity bill.
- Calculates the amount payable by each person.
- Displays the final amount clearly.

## Functional Modules

### 1. Input Module
Collects all required information from the user:
- Flat rent
- Food expenses
- Electricity units
- Electricity charge per unit
- Number of residents

### 2. Calculation Module
Calculates the electricity bill and combines it with rent and food expenses.

### 3. Output Module
Displays the amount that each person needs to pay.

## Technologies Used

- Python 3
- Python input/output
- Variables
- Arithmetic operators
- Integer division (`//`)

## Formula Used

Electricity Bill:

```text
Electricity Bill = Electricity Units × Charge Per Unit
```

Amount Per Person:

```text
Amount Per Person = (Rent + Food + Electricity Bill) // Number of Persons
```

## Project Workflow

```text
Start
  ↓
Enter Rent
  ↓
Enter Food Expense
  ↓
Enter Electricity Units
  ↓
Enter Charge Per Unit
  ↓
Enter Number of Persons
  ↓
Calculate Electricity Bill
  ↓
Calculate Amount Per Person
  ↓
Display Amount
  ↓
End
```

## How to Run

1. Install Python 3 on your computer.
2. Download or clone this project.
3. Open a terminal in the project folder.
4. Run:

```bash
python rentcalculator.py
```

5. Enter the requested values.
6. The program will display the amount each person should pay.

## Example

For example, if the user enters:

```text
Rent = 10000
Food = 5000
Electricity Units = 200
Charge Per Unit = 8
Persons = 4
```

The electricity bill is:

```text
200 × 8 = 1600
```

The amount per person is:

```text
(10000 + 5000 + 1600) // 4 = 4150
```

Output:

```text
Each person will pay = 4150
```

## Testing

The program can be tested using different values for rent, food expenses, electricity usage, electricity charges, and number of residents.

### Test Case 1
- Rent: 10000
- Food: 5000
- Electricity Units: 200
- Charge Per Unit: 8
- Persons: 4
- Expected output: 4150 per person

### Test Case 2
- Rent: 8000
- Food: 4000
- Electricity Units: 100
- Charge Per Unit: 10
- Persons: 2
- Expected output: 6500 per person

## Non-Functional Requirements

- **Usability:** The program uses simple prompts so that a beginner can enter the required information easily.
- **Performance:** The calculation uses basic arithmetic operations and completes immediately.
- **Reliability:** The same inputs produce the same calculated result.
- **Maintainability:** The program uses clear variable names and a simple calculation flow, making it easy to understand and modify.

## Project Structure

```text
Rent-Calculator/
│
├── rentcalculator.py
├── README.md
└── statement.md
```

## Future Enhancements

Possible improvements include:
- Adding input validation for invalid values.
- Supporting decimal amounts.
- Adding separate categories for other shared expenses.
- Creating a graphical user interface.
- Storing previous calculations.
- Splitting the project into multiple Python modules as the project grows.

## Conclusion

The Rent Calculator provides a simple way to divide common flat expenses among residents. It applies basic Python programming concepts to solve a practical expense-sharing problem.
