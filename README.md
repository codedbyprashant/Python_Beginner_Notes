#          Python Beginner Note

# Introduction
Welcome! This repository is a carefully curated set of notes that I have used to teach myself the Python programming language. The purpose of this repository is to guide learners from novice to expert in Python programming

As a learner, a hobbyist, or a budding developer, these notes will explain complex notions in simple terms that are 'human-readable'. There will be no 'tech speak', no 'filler', just the very foundation upon which one can start creating projects of one’s own.
## 💡Tips :
Don't try to memorize everything. Coding is an open-book skill. Even professional developers Google how to do basic things every single day. Understand the logic, not the syntax.
# Table of Contents

## 1. Introduction to Python
- [1.1 What is Python?](#what-is-python)
- [1.2 History & Evolution](#history--evolution)
- [1.3 Why Learn Python?](#why-learn-python)
- [1.4 Features of Python](#features-of-python)
- [1.5 Real-World Uses of Python](#real-world-uses-of-python)

## 2. Installation & Setup
- [2.1 Installing Python](#installing-python)
- [2.2 Checking Python Version](#checking-python-version)
- [2.3 Running Python Terminal vs IDE](#running-python-terminal-vs-ide)
- [2.4 Setting Up VS Code](#setting-up-vs-code)

## 3. Python Fundamentals
- [3.1 Creating a Python File](#creating-a-python-file)
- [3.2 Comments Single & Multi-line](#comments-single--multi-line)
- [3.3 The print Function](#the-print-function)
- [3.4 Variables](#variables)
- [3.5 Naming Rules & Conventions](#naming-rules--conventions)
- [3.6 Keywords](#keywords)

## 4. Data Types & Operators
- [4.1 Built-in Data Types](#built-in-data-types)
  - [Integer (int)](#integer-int)
  - [Float (float)](#float-float)
  - [String (str)](#string-str)
  - [Boolean (bool)](#boolean-bool)
- [4.2 The type Function](#the-type-function)
- [4.3 Type Conversion](#type-conversion)
- [4.4 Arithmetic Operators](#arithmetic-operators)
- [4.5 Assignment Operators](#assignment-operators)
- [4.6 Comparison Operators](#comparison-operators)
- [4.7 Logical Operators](#logical-operators)

## 5. User Input & Control Flow
- [5.1 Taking User Input (input)](#taking-user-input-input)
- [5.2 Input Type Casting](#input-type-casting)
- [5.3 if Statement](#if-statement)
- [5.4 if-else Statement](#if-else-statement)
- [5.5 elif Ladder](#elif-ladder)
- [5.6 Nested Conditions](#nested-conditions)
- [5.7 Indentation Rules](#indentation-rules)
- [5.8 Ternary Operator (Conditional Expression)](#)

## 6. Loops & Iteration
- [6.1 For Loop](#for-loop)
- [6.2 While Loop](#while-loop)
- [6.3 The range Function](#the-range-function)
- [6.4 Loop Control Statements](#loop-control-statements)
  - [break](#break)
  - [continue](#continue)
  - [pass](#pass)

## 7. Strings
- [7.1 Creating Strings](#creating-strings)
- [7.2 String Indexing](#string-indexing)
- [7.3 String Slicing](#string-slicing)
- [7.4 Common String Methods](#common-string-methods)
- [7.5 F-Strings](#f-strings)
- [7.6 String Formatting Basics](#string-formatting-basics)

## 8. Data Structures
- [8.1 Lists](#lists)
- [8.2 List Methods](#list-methods)
- [8.3 List Comprehensions Intro](#list-comprehensions-intro)
- [8.4 Tuples](#tuples)
- [8.5 Sets](#sets)
- [8.6 Dictionaries](#dictionaries)
- [8.7 Choosing the Right Data Structure](#choosing-the-right-data-structure)

## 9. Functions & Reusability
- [9.1 What are Functions?](#what-are-functions)
- [9.2 Defining & Calling Functions](#defining--calling-functions)
- [9.3 Parameters & Return Values](#parameters--return-values)
- [9.4 Default Arguments](#default-arguments)
- [9.5 Local vs Global Scope](#local-vs-global-scope)
- [9.6 Writing Clean Functions](#writing-clean-functions)

## 10. Modules & Packages
- [10.1 What is a Module?](#what-is-a-module)
- [10.2 Importing Built-in Modules](#importing-built-in-modules)
- [10.3 Creating User-Defined Modules](#creating-user-defined-modules)
- [10.4 Installing Packages with pip](#installing-packages-with-pip)
- [10.5 Virtual Environments venv](#virtual-environments-venv)

## 11. Errors & File Handling
- [11.1 Types of Errors](#types-of-errors)
- [11.2 Exceptions](#exceptions)
- [11.3 Try-Except Blocks](#try-except-blocks)
- [11.4 Reading Files](#reading-files)
- [11.5 Writing Files](#writing-files)
- [11.6 The with Statement](#the-with-statement)

## 12. Object-Oriented Programming Intro
- [12.1 What is OOP?](#what-is-oop)
- [12.2 Classes & Objects](#classes--objects)
- [12.3 The init Method](#the-init-method)
- [12.4 Instance Variables](#instance-variables)
- [12.5 Class Methods Basics](#class-methods-basics)

## 13. Python Best Practices
- [13.1 Writing Readable Code](#writing-readable-code)
- [13.2 PEP 8 Style Guide](#pep-8-style-guide)
- [13.3 Common Beginner Mistakes](#common-beginner-mistakes)
- [13.4 Debugging Tips](#debugging-tips)

## 14. Useful Built-in Functions
- [14.1 len](#len)
- [14.2 range](#range)
- [14.3 sum](#sum)
- [14.4 max and min](#max-and-min)
- [14.5 abs](#abs)
- [14.6 round](#round)

## 15. Mini Projects
- [15.1 Number Guessing Game](#number-guessing-game)
- [15.2 Simple Calculator](#simple-calculator)
- [15.3 File-Based To-Do List](#file-based-to-do-list)
- [15.4 Password Generator](#password-generator)

## 16. What’s Next?
- [16.1 Where to Go After Python Basics](#where-to-go-after-python-basics)
- [16.2 Learning Paths](#learning-paths)
  - [Web Development](#web-development)
  - [Data Science](#data-science)
  - [Automation](#automation)
  - [AI & Machine Learning](#ai--machine-learning)

---
# What is Python?

A computer can be instructed using Python, a **programming language**. These instructions can be straightforward, like printing text on the screen, or intricate, like creating websites, doing data analysis, or developing artificial intelligence models.


## Why Python is Popular

Python is known for:

- **Simple syntax:** Easy to **read and write** thanks to its simple syntax.
- **Clear structure:**  The code is arranged logically according to its clear structure.
- **Large community support:** Numerous tutorials, libraries, and forums provide extensive community support.
- **High-level language:** You may **concentrate on solving problems** rather than **low-level issues like memory managemen**t when you use **high-level language**.


## High-Level Language

Python **hides low-level details** like memory allocation and hardware control because it is a high-level language. Python takes care of data storage, so you don't have to worry about it and can concentrate on the **logic of your program**.

## Interpreted Language

Because Python is a **interpreted language**, the Python interpreter runs code **line by line**. 

**Advantages of this:**
- Code testing is quicker
- errors are simpler to find
- code may be executed interactively in a REPL (`Read-Eval-Print Loop`)

---
# History and Evolution of Python

**Guido van Rossum** created Python at **CWI (Netherlands)** in the **late 1980s** and it was formally released in **1991**. The language was inspired by:
- The teaching language **ABC**
- The comedy show *Monty Python’s Flying Circus*

### Major Python Versions

- **Python 1.0 (1994):** **Class support** was one of the fundamental features introduced in `Python 1.0` (1994).
- **Python 2.0 (2000):** Significant enhancements and expanded library support were added in Python 2.0 (2000).
- **Python 3.0 (2008):**Python 3.0 (2008) was a significant overhaul that prioritised long-term growth, consistency, and clarity.
- Python 3 is the **current and recommended version** for all modern development.


### Origins & Early Days (Late 1980s–1991)

- **Creator:** Guido van Rossum, a Dutch programmer.
- **Why Python was created:** Guido was frustrated with existing languages like Perl and shell scripting. He wanted a language that was simple, powerful, and easy to read, inspired by the teaching language **ABC**.
- **Name origin:** Named after the BBC comedy show *Monty Python’s Flying Circus*, not the snake.
- **First release:** Released in early **1991**, featuring support for classes, core data types, and exception handling.

---

# Why Learn Python?

Python is easy to learn and use, yet versatile and robust enough to be employed

## Why people choose Python:

- Easy to learn

- It’s widely used in the industry

- It has thousands of libraries

- It helps you build real projects quickly
---

# Features of Python

Python is popular because it comes with many built-in features that make programming easier:

- **Easy to Learn and Read:** Python language syntax is easy to understand. It looks like English.  
  Example:
  ```python
  print("Hello, World!")
  ```
Can be easily read and does what it says.

- **Interpreted**: It is easier to see mistakes because Python runs code line by line.

- **High-Level Language**: The low-level details associated with memory management, for instance, are dealt with by the Python language, so the programmer deals with logic solutions.

- **Dynamic Typing**: You don’t need to declare types for variables Python will determine types for them:

```python
   age = 20      # Integer
   name = "Alex" # String
```

- **Comprehensive Libraries**: Thousands of inbuilt and third-party libraries available for math, web, AI, and other areas.
- **Cross-Platform**: Supports Windows, Mac, Linux, Raspberry Pi.
- **Community Support**: The availability of a strong and active community that can offer tutorials and support.
---
# Real-World Applications of Python

Python is versatile and widely used across industries:

- **Web Development:** Build websites and web apps using Django and Flask.
- **Data Science & Analytics:** Work with data using Pandas, visualizations using Matplotlib, predictions using NumPy.
- **Artificial Intelligence & Machine Learning:** Develop AI systems, bots, and recommendation engines with TensorFlow & PyTorch.
- **Automation and Scripting:** Automate repetitive activities such as file operations, web scraping, and sending emails.
- **Game Development:** Learn to create simple games using Pygame.
- **Internet of Things (IoT):** Controlling devices and sensors with Python programming in Raspberry Pi.
- **Education & Research:** Extensively used in educational institutions for teaching programming and problem-solving.
---

## [⬆ Back to Top](#table-of-contents)

---
# Installation & Setup
Before embarking on any coding project with Python, the software has to be installed and an environment created where the programs can be executed.

##  Python Installation

- Visit the Python download webpage: https://www.python.org/downloads/

- Download the latest version based on your **operating system (Windows, Mac, or Linux**).

- **Run the installer**:

Crucial (for Windows only): Make sure you check the box marked “Add Python to PATH.”

Wait for the installation to finish.

## Checking Python Version
Before moving ahead, make sure Python is installed in your computer by following these steps:
- **Open the terminal** (Command Prompt on Windows, Terminal on Mac/Linux).
Type:
```
python --version
```
- You will notice that Python version is installed, for example, Python 3.12.0.
- 
 ## Running Python (Terminal vs IDE)

There are **two ways** to run Python code:

**1. Using the Python Shell (Interactive Mode)**
-Open terminal and type python or python3.
-You’ll see >>> which is the interactive prompt.
-Example:
```
>>> print("Hello World!")
Hello World!
```
**2. Using Scripts (Files)**
- Your python file will have .py extension, for example, hello.py.
- Execute the above in terminal:
```
python hello.py
```
- This is the usual procedure for working on larger projects.


## VS Code Setup

 VS Code operates on the basis of a lightweight and easily accessible code editor.
- Download VS Code: https://code.visualstudio.com/
- Install it.
- Install the Python Extension in VS Code:
- Open VS Code → Extensions → Search “Python” → Install.
- Create a folder of your python projects and open .py files to begin writing code. ex: index.py
- You can execute code directly from within the VS Code using either the "Run" button or the integrated terminal.

### 💡 Tip:
For those who are beginning, start off with VS Code. It’s easier to manage files, see errors, and later work on bigger projects.

## [⬆ Back to Top](#table-of-contents)
---

# Python Fundamentals
These are the building blocks of Python, and you'll instantly see results while learning the basic concepts.

---
# Creation of a Python File:
- Open Visual Studio Code.
- Create a new file, and save it with a .py extension, for example hello.py.
- In a Python file, we write code to perform tasks.
- **💡 Tip:** Save all your scripts in a folder, say projects, so that you can maintain all your scripts at one place if you're a learner.
---
# Comments Single & Multi-line
These are lines in your code that Python will ignore. They explain what something in the code is doing. Comments are for humans, not the computer.

**Why Comments Matter:**
- Make code easier to understand
- Help others read your code
- Help you remember what your code does later

**Single-line Comment**
```python
# This is a single-line comment
```
**Inline Comment**
```python
print("Hello")  # This prints a message on the screen
```
**Multi-line Comment**
```python
"""
This is a multi-line comment.
It can be used for longer text composition.
"""
```
## Notes / Tips:
- Comments should explain why things are done, not just what is done.
- Excessive comments are annoying comments, but a complete absence of comments makes code readability unachievable.
- Python does not have multi-line comments. For description purposes, triple quotes can be used.

---
# The print() Function
The `print()` function is used to display output on the screen. It's the very basic way to see what your code has produced, and it's one of the first functions taught in Python.
## **Example / Use Case:**
- Display text messages.
- Show the numbers or calculations.
```python
# Printing simple text
print("Hello World!")  #output : Hello World!

# Printing numbers
print(5)               #output : 5
print(2 + 6)           #output : 8

# Printing multiple values
print("Hello", "World")  # outputs: Hello World
```
# Variables
- A variable is a symbol that holds data inside a program. The data can be a number, a word, or any other value that can be reused later on.
- A variable is thought of as a tag given to a value.

**Why Variables are Needed:**
- To store information
- To reuse values instead of repeating them
- To make programs dynamic and flexibility
```python
name = "Python"
age = 10
price = 99.99
```
**Here:**
- name: Stores text (string)
- age is stored as an integer
- The price field stores a decimal number (float)
- 
 **We will discuss string, integer, float, etc. later.             [Click Here](#built-in-data-types)**

**Using Variables with print()**
```python
name = "Python"
print(name)

age = 10
print(age)
```

**Output:**
```python
Python
10
```
## Displaying Variables with Text
### A. Using Commas (The Easiest Way)
You can separate your text and your variable with a comma inside the print() function. Python will automatically add a space between them for you.

```Python
name = "Alice"
print("Hello,", name) 
# Output: Hello, Alice
```
### B. F-Strings (The Modern & Best Way)
An "f-string" (formatted string) allows you to put variables directly inside a sentence using curly braces {}. You must put the letter f before the starting quote.
```Python
age = 25
print(f"I am {age} years old.")
# Output: I am 25 years old.
```
- Why use this? It is the cleanest way to write code and very easy to read.

### C. String Concatenation (Using +)
You can use the + sign to "glue" strings together. However, this only works with text (strings). If you try to glue a number, Python will give you an error.
```Python

city = "New York"
print("I live in " + city)

# ⚠️ This would cause an error:
# score = 10
# print("Score: " + score)
```
---
# Naming Rules & Conventions
Naming rules define how variables should be named in Python. These rules make sure Python understands your code and that it remains readable for humans.

**Why Naming Rules Matter:**
- Prevent syntax errors
- Make code easier to read
- Help others understand your code quickly

**Rules for Naming Variables:**
- Variable names can contain letters, numbers, and underscores (_)
- A variable name must not start with a number
- Variable names cannot be Python keywords---> **(e.g : print, input, if, else,etc cannot be used as variable name.)**
- Variable names are case-sensitive ---> **(Case sensitive means the Python recognizes the difference between capital and lowercase letters.)**

**Valid Variable Names**
```python
user_name = "Alex"
age = 20
_total = 100
user1 = "Sam"
```
**Invalid Variable Names**
```python
1user = "Alex"      # starts with a number
user-name = "Sam"   # hyphen is not allowed
class = "Math"      # keyword
```
**Case Sensitivity Example**
```python
name = "Alex"
Name = "Sam"

print(name)
print(Name)
```
- These are treated as different variables.

**Naming Conventions (Best Practice):**
- Use snake_case for variable names
```python
total_marks = 450
user_age = 21
```

- Use clear and meaningful names
```python
score = 95      # good
s = 95          # not recommended
```
**Notes / Tips:**
- Avoid single-letter variable names unless in loops (later topic).
- Good names reduce the need for comments.
- Follow consistency throughout your code
---
# Keywords
Keywords are reserved words in Python that have a special meaning. Python uses them to define its own syntax and structure. Because of this, keywords **cannot be used as variable names**.

**Why Keywords Matter:**
- They form the building blocks of Python programs
- They are used for conditions, loops, functions, and more
- Using them incorrectly will cause errors

**Python Keywords:**
![Python Keywords](images/Python_keywords-1024x485.jpg)

**Checking All Keywords in Python**
```python
import keyword
print(keyword.kwlist)
```
**Notes / Tips:**
- You do not need to memorize all keywords.
- You’ll learn them naturally as you write more code.
- If Python shows an error while naming a variable, check if it’s a keyword.

## [⬆ Back to Top](#table-of-contents)
---
# Data Types
Data types tell Python what kind of value a variable holds. Different data types allow Python to decide how the data should be stored and used.
Python figures out the data type automatically. You don’t need to declare it.

**Why Data Types Matter:**
- They decide what operations are allowed
- They help avoid logical errors
- They make your code predictable

# Built-in Data Types
## Integer (int)
- Whole numbers without decimals.
```python
age = 25
score = 100
```
## Float (float)
- Numbers with decimal points.
```python
price = 99.99
pi = 3.14
```

## String (str)
- Text data written inside quotes.
```python
name = "Python"
message = 'Hello'
```

## Boolean (bool)
- Represents true or false values.
```python
is_active = True
is_logged_in = False
```
**Notes / Tips:**
- Strings can use single or double quotes.
- Boolean values must start with a capital letter.
- Python is dynamically typed, so variable types can change.
```python
value = 10
value = "Ten"
```
---
# The type() function
The type() function is used to find the data type of a value or a variable. It helps you understand what kind of data Python is working with.

**Why type() Is Useful:**
- To check the data type of a value
- To debug unexpected behavior
- To understand how Python treats your data
```python
print(type(10))
print(type(3.5))
print(type("Hello"))
print(type(True))
```
**Output :**
```python
<class 'int'>
<class 'float'>
<class 'str'>
<class 'bool'>
```
**Checking Type of Variables**
```python
age = 25
price = 9.19
name = "Python"

print(type(age))
print(type(price))
print(type(name))
```
**Output :**
```python
<class 'int'>
<class 'float'>
<class 'str'>
```
**Notes / Tips:**
- type() does not change the value. It only tells you the type.
- Python decides the type at runtime.
- This function is commonly used while learning and debugging.
---

# Type Conversion
Type conversion is the process of converting a value from one data type to another. This can happen automatically (implicit) or manually (explicit).

## Implicit Type Conversion (Type Casting)
Python automatically converts one data type to another without the programmer’s intervention. This happens when Python wants to prevent data loss during operations.

**Example / Use Case:**
- Mixing integers and floats in calculations.
- Code:
```python
# Adding integer and float
num1 = 5      # int
num2 = 2.5    # float

result = num1 + num2
print(result)      # 7.5
print(type(result)) # <class 'float'>
```
**Notes:**
- Python converts the integer 10 to a float automatically.
- This is called implicit type conversion or type coercion.
- Safe conversions only,Python won’t automatically convert a string to a number.
---
## Explicit Type Conversion (Type Casting)
You manually convert a value from one data type to another using functions like int(), float(), str(), or bool().

**Example / Use Case:**
- Converting user input (string) to a number before calculations.
- Code:
```python
# String to integer
num = "10"
num = int(num)
print(num)       # 10
print(type(num)) # <class 'int'>

# Integer to float
num2 = 5
print(float(num2))  # 5.0

# Integer to string
num3 = 20
print(str(num3))    # '20'
```
**Notes:**
- Always ensure the value is compatible with the type you are converting to.
- Explicit conversion gives you control over the process, unlike implicit conversion.

  ## [⬆ Back to Top](#table-of-contents)
---
#  Arithmetic Operators
Arithmetic operators are used to perform **mathematical calculations** in Python, like addition, subtraction, multiplication, and division.
| Operator | Meaning             | Example       |
| -------- | ------------------- | ------------- |
| `+`      | Addition            | `5 + 3 = 8`   |
| `-`      | Subtraction         | `5 - 3 = 2`   |
| `*`      | Multiplication      | `5 * 3 = 15`  |
| `/`      | Division            | `5 / 2 = 2.5` |
| `//`     | Floor Division      | `5 // 2 = 2`  |
| `%`      | Modulus (Remainder) | `5 % 2 = 1`   |
| `**`     | Exponent / Power    | `5 ** 2 = 25` |

**Code Examples:**
```python
# Addition
print(5 + 3)  # 8

# Subtraction
print(5 - 3)  # 2

# Multiplication
print(5 * 3)  # 15

# Division
print(5 / 2)  # 2.5

# Floor Division
print(5 // 2) # 2

# Modulus (Remainder)
print(5 % 2)  # 1

# Exponent / Power
print(5 ** 2) # 25
```
**Notes / Tips:**
- / always returns a float, even if the result is a whole number.
- // gives the whole number part only.
- % is useful for checking even/odd numbers:
```python
print(4 % 2)  # 0 → even
print(5 % 2)  # 1 → odd
```
# Practice Questions
- Write a program to add the prices of three items: 120, 250, and 80. Print the total amount.
- Write a program that divides one number by another and prints the remainder.
- Write a program to find the square and cube of a given number.
- Write a program to check whether a number is even or odd using arithmetic operators.
- Write a program that converts seconds into minutes and remaining seconds. Example: 130 seconds → 2 minutes and 10 seconds.
---
# Assignment Operators
Assignment operators are used to **store or update values** in a variable. The simplest assignment operator is =, but there are shortcuts that combine arithmetic with assignment.

**Common Assignment Operators**
| Operator | Meaning                 | Example                  |
| -------- | ----------------------- | ------------------------ |
| `=`      | Assign a value          | `x = 5`                  |
| `+=`     | Add and assign          | `x += 3` → `x = x + 3`   |
| `-=`     | Subtract and assign     | `x -= 2` → `x = x - 2`   |
| `*=`     | Multiply and assign     | `x *= 4` → `x = x * 4`   |
| `/=`     | Divide and assign       | `x /= 2` → `x = x / 2`   |
| `//=`    | Floor divide and assign | `x //= 3` → `x = x // 3` |
| `%=`     | Modulus and assign      | `x %= 2` → `x = x % 2`   |
| `**=`    | Exponent and assign     | `x **= 2` → `x = x ** 2` |

**Code Examples:**
```python
# Basic assignment
x = 5
print(x)  # 5

# Add and assign
x += 3
print(x)  # 8  (5 + 3)

# Subtract and assign
x -= 2
print(x)  # 6  (8 - 2)

# Multiply and assign
x *= 4
print(x)  # 24 (6 * 4)

# Divide and assign
x /= 3
print(x)  # 8.0 (24 / 3)

# Floor divide and assign
x //= 3
print(x)  # 2.0 (8.0 // 3)

# Modulus and assign
x %= 2
print(x)  # 0.0 (2.0 % 2)

# Exponent and assign
x = 3
x **= 2
print(x)  # 9 (3 squared)

```
**Notes / Tips:**
- These operators update the value of a variable without writing it twice.
- +=, -=, *=, etc., are very common in loops and calculations.
- Floor division //= keeps the integer part only.
# Practice Questions
- Write a program where a number starts at 10. Then:
 **add 5**,**multiply the result by 2**, **subtract 4** and **Print the final value.**
- Write a program to increase a number by 10 using an assignment operator.
- Write a program to double a number using an assignment operator.
- Write a program that divides a number by 3 and updates the same variable using an assignment operator.
---
# Comparison Operators
Comparison operators are used to **compare two values**. They return a **Boolean value**: True or False.

**Why Comparison Operators Matter:**
- To make decisions in your program
- Often used in if statements, loops, and conditions

**Common Comparison Operators**
| Operator | Meaning               | Example          |
| -------- | --------------------- | ---------------- |
| `==`     | Equal to              | `5 == 5 → True`  |
| `!=`     | Not equal to          | `5 != 3 → True`  |
| `>`      | Greater than          | `5 > 3 → True`   |
| `<`      | Less than             | `5 < 3 → False`  |
| `>=`     | Greater than or equal | `5 >= 5 → True`  |
| `<=`     | Less than or equal    | `5 <= 3 → False` |

**Code Examples:**
```python
# Equal to
print(5 == 5)  # True
print(5 == 3)  # False

# Not equal to
print(5 != 3)  # True
print(5 != 5)  # False

# Greater than / Less than
print(5 > 3)   # True
print(5 < 3)   # False

# Greater than or equal / Less than or equal
print(5 >= 5)  # True
print(5 <= 3)  # False
```
**Notes / Tips:**
- Always remember: == is comparison, = is assignment.
- Comparison operators return True or False.
- Useful inside if statements and loops to control the program flow.
# Practice Questions
- Write a program to check if two numbers are equal.
- Write a program to check if one number is greater than another number.
- Write a program to check if a number is less than or equal to 100.
- Write a program to check if two numbers are not equal.
---
# Logical Operators
Logical operators are used to **combine multiple conditions** and return a Boolean value (True or False).

**Why Logical Operators Matter:**
- To check more than one condition at a time
- Often used in if statements, loops, and complex decisions

**Common Logical Operators**
| Operator | Meaning                      | Example                      |
| -------- | ---------------------------- | ---------------------------- |
| `and`    | True if both are True        | `(5 > 3) and (2 < 4) → True` |
| `or`     | True if at least one is True | `(5 < 3) or (2 < 4) → True`  |
| `not`    | Reverses the result          | `not (5 > 3) → False`        |

**Code Examples:**
```python
# AND operator
print((5 > 3) and (2 < 4))  # True
print((5 > 3) and (2 > 4))  # False

# OR operator
print((5 > 3) or (2 > 4))   # True
print((5 < 3) or (2 > 4))   # False

# NOT operator
print(not (5 > 3))          # False
print(not (5 < 3))          # True
```
**Notes / Tips:**
- **and** requires both conditions to be True.
- **or** requires at least one condition to be True.
- **not** simply reverses the result.
- Logical operators are often combined with comparison operators for decision-making

# Practice Questions
- Write a program to check if a number is greater than 10 **and** less than 50.
- Write a program to check if a number is less than 5 **or** greater than 100.
- Write a program to reverse the result of a comparison using a logical operator. Example: change True to False or False to True.
- Write a program to check if a person’s age is between 18 and 60.

## [⬆ Back to Top](#table-of-contents)

# Data Types & Operators(Practice Question)
- Create three variables: a = 10, b = "10", and c = 10.0. Use the type() function to print the data type of each. Are they the same?

- Create a variable birth_year = "2000". Convert it to an integer, subtract it from the current year (2026), and print: "You are [age] years old." (Use an f-string).
  
- You bought 3 loaves of bread at $2.50 each. Create variables for quantity and price, calculate the total, and print: "Total cost: $7.5".
  
- Start with score = 50. Use an assignment operator (like +=) to add 15 to the score, then divide the score by 2 using /=. Print the final score.
  
- Write a program that compares two numbers, x = 15 and y = 20. Print the result of x > y and x != y. What are the results? (True or False).
 
- Create two boolean variables: has_id = True and is_adult = True. Use the and operator to print if the person can enter the club.
  
- A customer gets a discount if they are a student or a senior. Create two booleans for these and use or to check if they get the discount.
  
- What happens when you "multiply" a string? Create a variable laugh = "Ha". Use the * operator to print "Ha" ten times in a row.
  
- Create a float pi = 3.14159. Use type conversion to turn it into an integer. What happened to the numbers after the decimal point?
  
- Create a variable is_raining = False. Use the not operator to print the opposite value.
  
---
# User Input & Control Flow
#  Taking User Input (`input`)
In Python, we can make programs interactive by **asking the user to type something.**
We use the `input()` function to get text from the user. Whatever the user types will be stored in a variable so we can use it later.
```python
# Ask the user for their name
name = input("Enter your name: ")

# Print a greeting
print("Hello", name)
```
**Explanation :**
- `input("Enter your name: ")` shows a message on the screen.
- Whatever the user types is stored in the variable `name`.
- `print("Hello", name)` displays a message along with the user input.
**Tiny tips:**
- Always store the input in a variable if you want to use it.
- Input is always **text (string)** by default. If you need numbers, you have to convert it (we’ll cover that later).
---
# Input Type Casting
When we use input() in Python, **everything the user types is treated as text (string)**, even if they enter numbers.
Sometimes, we want to use that input as a **number** to do calculations. For this, we need **type casting** (converting one data type into another).
### Converting Input to Integer
```python
# Ask the user for a number
num = input("Enter a number: ")

# Convert string to integer
num = int(num)

# Now we can do math
print("Double of your number is:", num * 2)
```
**OR**
```python
# Ask the user for a number and convert string to integer directly
num = int(input("Enter a number :"))

# Now we can do math
print("Double of your number is:", num * 2)
```
**Explanation:**
- `input()` returns a string by default.
- `int()` converts the string to an integer.
- After conversion, we can use it in arithmetic operations.

### Converting Input to Float
```python
# Ask for a decimal number
num = input("Enter a decimal number: ")

# Convert string to float
num = float(num)

print("Half of your number is:", num / 2)
```
**OR**
```python
# Ask the user for a number and convert string to float directly
num = float(input("Enter a number :"))

# Now we can do math
print("Half of your number is:", num / 2)
```
**Explanation:**
- `float()` converts string input to a decimal number.
- Useful for calculations involving fractions or money.

### Quick Tips for Beginners
- Always store the converted value in a variable if you need it.
- If the user enters something invalid (like letters instead of numbers), `int()` or `float()` will give an error. We’ll learn how to handle that later.
- Type casting lets you **mix input and calculations safely**.
## Practice Question
- Ask the user for their name and then print a greeting that says: `"Hello [name], welcome to Python programming!"`

- Create a program that asks for a user's birth year, subtracts it from the current year (2026), and displays: `"You are [age] years old."`
  
- Ask the user for two numbers. Multiply them together and print the result. Ensure the program can handle decimal numbers.

- Ask the user for two numbers and print their sum. Make sure to convert inputs to integers.
---
# if Statement
Python programs often need to **make decisions.**
We use the `if` statement to **check a condition** and run code only if the condition is true.
```python
age = 18

if age >= 18:
    print("You can vote")
```
**Explanation:**
- `age >= 18` is a condition (checks if age is 18 or more).
- The indented code under `if` runs only if the condition is true.
- If the condition is false, Python **skips it.**
---
# Indentation Rules
Python does not use curly braces `{}` like some other languages.
Instead, it uses **indentation (spaces at the start of a line)** to know which code belongs to `if`, `else`, or loops.
```python
if True:
    print("This line is indented")
```
**Rules for beginners:**
- Use **4 spaces** for each indentation level.
- Be **consistent**-don’t mix tabs and spaces.
- Wrong indentation will cause an error.
---
# if-else Statement
Sometimes we want to **do something if a condition is true, and something else if it is false**. That’s what `else` is for.
An if statement asks a question.
- **If** the answer is **Yes** (True), the code inside the `if` block runs.
- **Else** (if the answer is **No**), the code inside the `else` block runs.

It is impossible for both to run at the same time. It is always one or the other.
```python
age = 16

if age >= 18:
    print("You can vote")
else:
    print("You cannot vote")
```
**Explanation:**
- `if` checks the first condition.
- If it’s true → run the code under `if`.
- If it’s false → run the code under `else`.
---
# elif Ladder
When writing programs, sometimes we need to **check more than one condition.**

We could write many `if` statements, but Python would check **all of them** even if one is already true. This is inefficient and can give wrong results.

That’s why we use `elif`, which means “**else if**”.
- `if` → check the first condition
- `elif` → check another condition only if the previous `if` or `elif` was **false**
- `else` → runs if all conditions are false

**Example 1:**
```python
marks = int(input("Enter your marks: "))

if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
elif marks >= 60:
    print("Grade C")
else:
    print("Grade F")
```
**Explanation:**
- Python first checks `if marks >= 90.`
- If true → prints `Grade A` and skips the rest.
- If false, Python checks the first `elif` `(marks >= 75).`
- If that is also false, Python checks the next `elif`.
- If none of the conditions are true, the `else` block runs.

✅ Only **one block** runs, even if multiple conditions could be true.

**Example 2:**
```python
age = int(input("Enter your age: "))

if age < 13:
    print("Child")
elif age < 20:
    print("Teenager")
elif age < 60:
    print("Adult")
else:
    print("Senior Citizen")
```
**Explanation:**
- Python checks conditions **top to bottom**.
- First true condition stops the ladder; remaining conditions are skipped.
- This is more efficient than writing multiple separate `if` statements.

**Common Beginner Mistakes**
- Using multiple `if` statements instead of `elif`-can lead to multiple blocks running.
- Forgetting to put the **colon** `:` at the end of `elif` line.
- Placing `else` **before** `elif` (it must always come last).
---
# Nested Conditions
We may need to **verify a condition inside another condition** in a program. This is referred to as a nested if or nested condition.

The Benefits of Nested Conditions, Consider that you are creating a program to grant access to a club:

The individual must be at **least eighteen years old.**
They also need to have **identification.**
We run the risk of making mistakes or repeating code if we use two if statements for checking these conditions independently. We can **check one condition first** and then another only if the first is true thanks to nested conditions.

```python
age = int(input("Enter your age: "))
has_id = input("Do you have an ID? (yes/no): ")

if age >= 18:
    if has_id == "yes":
        print("Entry allowed")
    else:
        print("Entry denied: No ID")
else:
    print("Entry denied: Underage")
```
**Explanation:**
- First, Python checks `if age >= 18`.
- If false -> goes directly to `else` and prints “Underage”.
- If true -> checks the **nested** `if` for ID.
- If ID is “yes” -> prints “Entry allowed”
- Otherwise -> prints “Entry denied: No ID”

 Using nested conditions helps ``group related checks`` logically.

---
# Ternary Operator (Conditional Expression)
In Python, sometimes we want to **write an** `if-else` **statement in a single line**.
This is useful for **short**, **simple decisions**.

This is called the ternary operator or conditional expression.
