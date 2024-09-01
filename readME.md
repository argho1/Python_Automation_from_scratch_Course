# Python 101 - Beginner's Course

Welcome to the Python 101 Beginner's Course! This repository contains introductory lessons on Python programming, focusing on basic concepts and functionalities essential for new learners.

## Table of Contents
- [print()](#using-print-function)
- [input()](#using-input-function)
- [f-string](#f-string)
- [Challange](#challange)

## Introduction
This section provides a brief introduction to Python, a versatile and powerful programming language used in a wide range of applications, from simple scripts to complex machine learning algorithms.

## Using `print()` Function
The `print()` function in Python is used to output text or other data to the standard output device (usually the terminal).

### Single Line Printing
To print text simply on a single line:
```python
print("Hello, World!")
```
### Multi Line Printing
To print text simply on multiple lines:

```python
print("Hello, World!")
print("Hello, World!")
print("Hello, World!")
```
### OR the pro way
By using "\n" which stands for next line.
```python
print("Hello, World!\nHello, World!\nHello, World!")
```

## Using 'input()' Function
The `input()` function in Python allows the program to pause and wait for user input, which can be useful for interactive applications. This function reads a line from input, converts it into a string (stripping a trailing newline), and returns it.

### Usage
Prompt the user to enter some text and store it in a variable:
```python
name = input("Enter your name: ")
```
Then printing it:
```python
print(name)
```

## f-String
F-strings in Python let you include variables directly in strings for easier formatting, making it quicker and clearer to combine text and data.

### Usage
Prompt the user to enter some text and store it in a variable:
```python
name = input("Enter your name: ")
print("Hello ", name, "\nWelcom to your first python call.")
```
The 'pro' way with f-String:
```python
name = input("Enter your name: ")
print(f"Hello {name}.\nWelcome to the class.")
```

## Challange

1. **Take Input**
   - Prompt the user to enter their name, age, gender, and DOB.

2. **Print Normally**
   - Output the collected information in a single line.

3. **Print Using f-string**
   - Utilize Python's f-string formatting to cleanly insert variables into strings.

4. **Print Formats**
   - Display the information in one line.
   - Display the information on multiple lines for clarity.
