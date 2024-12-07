# Functional Programming Spreadsheet

This project is a **Functional Programming Spreadsheet** that allows users to input formulas using functional programming techniques. The spreadsheet supports basic arithmetic operations, custom functions, and cell references, similar to how Excel or Google Sheets works, but with an emphasis on functional programming.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Running the Project](#running-the-project)
- [Usage](#usage)
- [Example](#example)
- [Error Handling](#error-handling)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Basic Arithmetic Operations**: Supports `+`, `-`, `*`, `/`.
- **Spreadsheet Functions**: Functions like `sum`, `average`, `median`, `even`, `firsttwo`, `lasttwo`, and others.
- **Cell References**: Supports referencing individual cells (e.g., `A1`, `B2`) or ranges of cells (e.g., `A1:A5`).
- **Dynamic Grid**: Automatically generates a 10x100 grid for the spreadsheet, with cells for input and labels.
- **Error Handling**: Displays an error message when an invalid formula or cell reference is entered.
- **Recursive Formula Evaluation**: Evaluates formulas recursively and supports high-precedence operators.

## Getting Started

### Prerequisites

You need a modern web browser to run this project. No additional software is required.

### Running the Project

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/yourusername/functional-programming-spreadsheet.git

2. Open the index.html file in your browser
   ```
   open index.html
   ```
   (Or just double-click index.html in your file explorer.)

## Usage
 Enter formulas in any of the cells in the grid (e.g., =sum(A1, B1, C1)).
 Supported functions:
 sum(A1, B1, C1)
 average(A1:A5)
 median(A1:A5)
 even(A1:A5) (returns only even numbers)
 firsttwo(A1:A5) (returns the first two values)
 random(1, 100) (returns a random number between 1 and 100)
## Example
 To calculate the sum of values in cells A1, B1, and C1, you would enter the following formula in a cell:
 ```
 =sum(A1, B1, C1)
 ```
## Error Handling
 If an invalid formula is entered, the cell will be highlighted in red, and an error message will be displayed.

## Contributing
 Feel free to open issues, suggest features, or make pull requests if you have improvements for this project.

## License
 This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by spreadsheets like Excel and Google Sheets.
- Uses JavaScript's `eval` function for formula parsing and evaluation.
- Based on functional programming principles.
- This project was completed as part of the [FreeCodeCamp](https://www.freecodecamp.org/) curriculum.
- Special thanks to the FreeCodeCamp team for providing the resources and challenges that helped me develop this project.

