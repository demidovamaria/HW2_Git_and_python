# Mini Calculator

This is a simple command-line calculator program written in Python.\
It accepts a basic mathematical expression as input and outputs the result.

## Project Description

The program `calculator.py` takes a string from the user in the following format:

    <number> <operator> <number>

-   The numbers can be `int` or `float`.
-   The operator can be one of the four: `+`, `-`, `*`, `/`.
-   All elements are separated by spaces (example: `5 - 3`).

### Features

-   Addition, subtraction, multiplication, and division are supported.
-   Input is parsed and passed to one of four dedicated functions (one
    per operation).
-   A `main` function coordinates input, delegates to the proper operation function, and prints the result.

### Example

    Input:  7 * 3
    Output: 21

## Functions

-   `main()` - reads user input, chooses the correct operation, and
    prints the result.
-   `add(a, b)` - returns the sum of two numbers.
-   `subtract(a, b)` - returns the difference between two numbers.
-   `multiply(a, b)` - returns the product of two numbers.
-   `divide(a, b)` - returns the quotient of two numbers.

## Installation and Execution

1. Clone the repository:
```bash
git clone https://github.com/your-username/calculator-project.git
cd calculator-project
```
2. Run the program:
```bash
python calculator.py
```
3. Enter expressions when prompted in the format:
```bash
<number> <operator> <number>
```

## Team

-   Team Lead: [Maria Demidova](https://github.com/demidovamaria)
-   Developer: [Maria Domraceva](https://github.com/avedomra)
-   Developer: [Anastasiya Rozhkova](https://github.com/gitgen-art) 
-   Developer: [Polina Likhacheva](https://github.com/pmlikhacheva)

![Team](imgs/team.jpg)