# Simple Calculator Library

A lightweight Python library that provides basic arithmetic operations: addition, subtraction, multiplication, and division.

## Features

- **Addition**: Add two numbers.
- **Subtraction**: Subtract one number from another.
- **Multiplication**: Multiply two numbers.
- **Division**: Divide one number by another (with zero-division handling).

## Installation

You can simply copy the Python file containing these functions into your project. No external dependencies are required.

## Usage

```python
from calculator import add, subtract, multiply, divide

# Addition
result = add(5, 3)
print(result)  # Output: 8

# Subtraction
result = subtract(10, 4)
print(result)  # Output: 6

# Multiplication
result = multiply(7, 3)
print(result)  # Output: 21

# Division
result = divide(10, 2)
print(result)  # Output: 5.0

# Division by zero
result = divide(10, 0)
print(result)  # Output: "Error Division by zero is not allowed."
