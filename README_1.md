# Assignment 3: Functions & Modules in Python

This repository contains the solution for **Assignment 3**, covering the use of user-defined **Functions** and Python's built-in **`math` Module** for calculations.

The repository includes two Python scripts:
1.  `Factorial function.py` (Task 1)
2.  `Math Module assignment.py` (Task 2)

---

## 1. Task 1: Calculate Factorial Using a Function

### `Factorial function.py`

This script defines a recursive function to calculate the factorial of a given number.

### Functionality
* **Function Definition:** A function named `factorial(n)` is defined.
* **Calculation Method:** It uses **recursion** to compute the factorial ($n!$).
    * **Base Case:** If $n < 2$, it returns $1$ (since $0! = 1$ and $1! = 1$).
    * **Recursive Step:** Otherwise, it returns $n \times \text{factorial}(n-1)$.
* **User Input & Output:** It prompts the user to enter a number and prints the calculated factorial.

---

## 2. Task 2: Using the Math Module for Calculations

### `Math Module assignment.py`

This script demonstrates the use of the built-in `math` module to perform common mathematical operations.

### Functionality
* **Module Import:** It imports the necessary `math` module.
* **User Input:** It prompts the user to enter a number (as a float).
* **Calculations:** It uses three key functions from the `math` module:
    1.  `math.sqrt()`: Calculates the **square root**.
    2.  `math.log()`: Calculates the **natural logarithm** (base $e$).
    3.  `math.sin()`: Calculates the **sine** of the number (assuming the input is in radians).
* **Output:** It displays all three calculated results.