# Assignment 2: Control Structures in Python

This repository contains the solutions for **Assignment 2**, which focuses on implementing **control structures (if-else statements and loops)** in Python, as part of **Module 3: Control Structures in Python**.

The assignment is divided into two distinct tasks, each addressed by a separate Python script.

---

##  Repository Contents

| File Name            | Description |
|:---------------------| :--- |
| `even or odd.py`     | Contains the solution for Task 1: Checking if a number is even or odd using an `if-else` statement. |
| `Sum of integers.py` | Contains the solution for Task 2: Calculating the sum of integers from 1 to 50 using a `for` loop. |
| `README.md`          | This file. |

---

## ✔️ Task 1: Check if a Number is Even or Odd

### Problem Statement
Write a Python program that takes an integer input from the user, checks whether the number is **even or odd** using an `if-else` statement, and displays the result.

### Implementation Details
The script uses the **modulo operator (`%`)** to determine if the remainder of the number divided by 2 is 0.
* If the remainder is $0$, the number is **even**.
* Otherwise, the number is **odd**.
The decision is handled by an `if-else` block.

---

## Task 2: Sum of Integers from 1 to 50 Using a Loop

### Problem Statement
Write a Python program that uses a **`for` loop** to iterate over numbers from **1 to 50**, calculates the **sum** of all integers in this range, and displays the final sum.

### Implementation Details
1.  A variable (`t`) is initialized to $0$.
2.  A `for` loop is used with the built-in `range()` function to generate numbers from 1 up to and including 50 (e.g., `range(1, 51)`).
3.  Inside the loop, each number is added to the running sum variable.
4.  After the loop completes, the final sum is printed.