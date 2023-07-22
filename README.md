# Calculator Package

The Calculator Package is a Python module that provides a simple calculator class with essential arithmetic operations. This package allows users to perform addition, subtraction, multiplication, division, taking roots, and resetting the calculator's memory.

## Installation

To install the calculator package, you can use `pip`:

## Purpose of Package 
Able to perform simple calculations

## Usage

1. Import the `Calculator` class:


from calculator.calculator import Calculator

#Create an instance of the Calculator class:

calc = Calculator()

Use the calculator methods to perform operations:

calc.add(5)
print(calc.memory)  # Output: 5

calc.subtract(2)
print(calc.memory)  # Output: 3

calc.multiply(3)
print(calc.memory)  # Output: 9

calc.divide(3)
print(calc.memory)  # Output: 3.0

calc.root(2)
print(calc.memory)  # Output: 1.7320508075688772

calc.reset()
print(calc.memory)  # Output: 0

Unit Tests
python -m unittest calculator_package.test_calculator


Remember to modify the installation command (`pip install calculator-package`) with the actual name of your package when you publish it on PyPI. Also, ensure that the file paths and package names in the code example are correct based on your project structure.

This `README.md` provides a brief introduction, installation instructions, usage examples, information about unit tests, and the package's license. Feel free to add any additional details or improve the content based on your specific project requirements.

## Author 

