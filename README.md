Prateek Sinha

24070123077

ENTC A3

# C++ Programs: Conditional Logic and Decision Making

## Overview

This document describes a series of beginner-level C++ programs that demonstrate decision-making using conditional statements and switch-case constructs. The goal of these programs is to help learners understand how to implement logic based on user input and how to handle different conditions effectively in C++.

---

## Program 1: Weekday Activity Selector (Switch Statement)

### Purpose

To display a specific activity based on the day of the week selected by the user.

### Concepts Covered

- Use of `switch` statement to make decisions.
- Mapping numeric input to day-specific outputs.
- Use of `break` statements to prevent fall-through.

### Logic Summary

1. Display a list of weekdays (Monday to Friday).
2. Take user input corresponding to a day (1–5).
3. Use a `switch` statement to display a related activity for that day.
4. Handle invalid input with a `default` case.

Output:-

  Monday

Tuesday

Wednesday

Thursday

Friday

Enter choice:5

gym


---

## Program 2: Simple Arithmetic Calculator

### Purpose

To perform basic arithmetic operations (+, -, *, /) based on the operator selected by the user.

### Concepts Covered

- Use of `switch` with character input.
- Arithmetic operations on floating-point numbers.
- Input validation (e.g., division by zero handling).
- Use of `default` case to handle invalid operators.

### Logic Summary

1. Prompt the user to input an arithmetic operator.
2. Accept two numbers as operands.
3. Use a `switch` to evaluate the expression based on the selected operator.
4. Display the result or an error message for invalid input.

Output:-

Enter operator(+,-,*,/):*

Enter two numbers: 45,66

45*66=2970

---

## Program 3: Even or Odd Number Checker

### Purpose

To check whether a given number is even or odd.

### Concepts Covered

- Use of `if-else` statement.
- Use of the modulo operator `%` to determine divisibility by 2.

### Logic Summary

1. Accept an integer from the user.
2. Use conditional logic to check if the number is divisible by 2.
3. Display whether the number is even or odd.

Output:-

Enter a number: 56

56 is Even

---

## Program 4: Vowel or Consonant Checker

### Purpose

To determine whether a character entered by the user is a vowel or a consonant.

### Concepts Covered

- Use of logical OR (`||`) in `if` conditions.
- Comparison of character input with vowel characters.

### Logic Summary

1. Accept a character input from the user.
2. Check if the character matches any of the vowels (a, e, i, o, u).
3. Display whether the character is a vowel or consonant.

Output:-

Enter a Character:b

b is Constant

---

## Program 5: Find the Largest of Three Numbers

### Purpose

To determine the largest number among three user-entered integers.

### Concepts Covered

- Nested `if-else` statements.
- Use of comparison operators (`>=`) to evaluate maximum.

### Logic Summary

1. Prompt the user to enter three numbers.
2. Use nested `if` conditions to compare the numbers.
3. Identify and display the largest number among the three.

Output:-

Enter three numbers:2,3,4

Largest number is:2

---

## Conclusion

These programs provide a practical introduction to control structures in C++. They cover both multi-branch decision-making using `switch-case` and condition checking using `if-else`. Learners gain insight into how to handle different inputs and execute specific logic based on those inputs. These foundational skills are essential for building interactive and logic-driven applications in C++.
