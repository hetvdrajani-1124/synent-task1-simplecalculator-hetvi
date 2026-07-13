# Project Report: Simple Calculator (CLI)
**Domain:** Python Development Internship  
**Task 1:** Command-Line Calculator  

---

## 1. Objective
The objective of this task is to build a functional, user-friendly command-line interface (CLI) calculator using Python. The application handles basic mathematical calculations efficiently while ensuring stability against incorrect user actions.

## 2. Requirements Implemented
The application successfully fulfills all project constraints:
* **Addition (+):** Computes the sum of two numerical values.
* **Subtraction (-):** Computes the difference between two numerical values.
* **Multiplication (*):** Computes the product of two numerical values.
* **Division (/):** Computes the quotient of two numerical values.

## 3. Key Features & Methodology
* **User Input Management:** The script interactively requests the user to pick an operation from a menu and then prompts them to provide two numbers.
* **Invalid Input Handling:** 
  * Uses `try-except` validation blocks to catch non-numerical inputs (like letters or symbols) so the application does not crash.
  * Includes logic checks during division to intercept division-by-zero errors gracefully.
* **Continuous Execution Loop:** Runs inside a continuous `while` loop, enabling users to perform multiple operations consecutively until they choose option `5` to exit.

## 4. System Output
All operations display clean, formatted outputs directly inside the terminal window. Results are clearly marked, and explicit error messages (such as "Invalid Input" or "Division by zero is not allowed") are printed immediately if an issue occurs.

## 5. Conclusion
The CLI Calculator application successfully meets all requirements provided in the internship guidelines. It serves as a practical demonstration of core Python capabilities, functional structure, conditional branching, and robust error handling.
