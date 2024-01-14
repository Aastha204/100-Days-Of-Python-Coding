# Day 14: Mastering If-Else and Elif Statements in Python

Welcome to Day 14 of my 100 Days of Python Coding Challenge! Today, I deepened my understanding of conditional statements in Python, including `if`, `else`, and `elif` statements.

## What I Explored

### Conditional Statements Overview
Conditional statements allow you to execute different blocks of code based on whether a specified condition evaluates to `True` or `False`.

- **`if` Statement**: Executes a block of code if the specified condition is `True`.
- **`else` Statement**: Executes a block of code if the preceding `if` condition is `False`.
- **`elif` Statement**: Short for "else if," it allows you to check additional conditions if the preceding `if` condition is `False`.
- **Nested Conditions**: Placing one or more conditional statements inside another.

### Examples
```python
# Basic if-else statement
age = 18
if age >= 18:
    print("You are eligible to vote.")
else:
    print("You are not eligible to vote.")

# if-elif-else statement
marks = 75
if marks >= 90:
    print("Grade A")
elif marks >= 80:
    print("Grade B")
elif marks >= 70:
    print("Grade C")
else:
    print("Grade D")

# Nested if statements
num = 10
if num > 0:
    if num % 2 == 0:
        print("Positive and even")
    else:
        print("Positive and odd")
elif num == 0:
    print("Zero")
else:
    print("Negative")
```

## Highlights
- **Decision-Making Flexibility**: Understanding how if-else and elif statements offer flexibility in decision-making.
- **Efficient Code Execution**: Leveraging conditionals for executing specific code blocks based on varying conditions.
- **Nested Conditions**: Realizing the power of nesting conditions for intricate decision trees.

## Next Steps
- **Logical Operators**: Explore logical operators (`and`, `or`, `not`) for combining multiple conditions.
- **Advanced Control Flow**: Dive into more advanced control flow structures for intricate program logic.

## Resources
- Code with Harry tutorials on if-else and elif statements for in-depth explanations.
- Python documentation on control flow tools for further reference.

Mastering conditional statements is fundamental for implementing dynamic and responsive logic in Python programs.

Happy Decision-Making! 🤔✨
