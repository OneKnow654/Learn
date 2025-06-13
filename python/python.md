# Python Quick Reference

## Overview

Python is a general-purpose, dynamic, high-level, and interpreted programming language. It supports multiple programming paradigms, including Object-Oriented, Imperative, and Functional programming styles.

## Key Features

- **Ease of Learning:** Python is simple and easy to learn, making it an ideal language for beginners.

- **High-Level Data Structures:** Python provides a variety of high-level data structures for efficient programming.

- **Interpreted Nature:** Being an interpreted language, Python offers a quick development cycle and ease of debugging.

- **Multipurpose:** Python is versatile and can be used for various applications, including web development, enterprise applications, 3D CAD, and more.

## Programming Paradigms

Python supports the following programming styles:

- **Object-Oriented Programming (OOP):** Python follows the Object-Oriented programming approach for application development.

- **Imperative Programming:** Python supports imperative programming for specifying step-by-step instructions for the computer.

- **Functional Programming:** Python allows functional programming, emphasizing the use of pure functions and avoiding mutable data.

## Dynamic Typing

Python is dynamically typed, meaning you don't need to declare data types for variables. For example:

```python
a = 10  # Assigning an integer value to a variable without specifying the data type
```

# Installing Python on Windows

To get started with Python on your Windows operating system, follow these steps:

## Step 1: Visit Python Website

Visit the official Python website at [python.org](https://www.python.org).

## Step 2: Download Python

1. On the Python homepage, click on the "Downloads" tab.

2. Click on the "Python 3.11.3" release or the latest version available.

3. Scroll down to the Files section, and under the Windows header, you will find options for the executable installer. Choose the installer that matches your system architecture (32-bit or 64-bit).

4. Click on the installer link to start the download.

## Step 3: Run the Installer

1. Once the installer is downloaded, locate the file (typically in your Downloads folder) and double-click on it to run the installer.

2. In the Python Installer, make sure to check the box that says "Add Python 3.x to PATH." This makes it easier to run Python from the command line.

3. Click "Install Now" to start the installation.

4. The installer will copy the necessary files and set up Python on your system.

## Step 4: Verify Installation

1. Open a command prompt or PowerShell window.

2. Type the following command and press Enter:

```batch
   python --version
```
# First Python Program

In this section, we will explore the basic syntax of Python and run a simple program to print "Hello World" on the console.

## Using Interactive Interpreter Prompt

Python provides an interactive interpreter prompt where you can execute Python statements and see the results immediately.

1. Open a command prompt or terminal window.

2. Type `python` and press Enter to enter the Python interactive shell.

3. Now, type the following command and press Enter:

    ```python
    print("Hello World")
    ```

   You should see the output `Hello World` displayed on the screen.

4. To exit the interactive shell, type `exit()` or press `Ctrl + Z` and then press Enter.

## Using a Script File

Another way to run Python code is by creating a script file with the Python code and executing it.

1. Open a text editor (such as Notepad, Visual Studio Code, or any code editor of your choice).

2. Copy and paste the following code into the editor:

    ```python
    # Filename: hello_world.py

    print("Hello World")
    ```

3. Save the file with a `.py` extension, for example, `hello_world.py`.

4. Open a command prompt or terminal and navigate to the directory where the script is saved.

5. Type the following command and press Enter:

    ```bash
    python hello_world.py
    ```

   You should see the output `Hello World` displayed on the screen.

Congratulations! You've just run your first Python program using both the interactive interpreter prompt and a script file.
==========================================================================================
# First Python Program in IDLE

In this section, we will explore the basic syntax of Python and run a simple program to print "Hello World" on the console using IDLE.

## Using IDLE Interactive Shell

IDLE provides an interactive shell where you can execute Python statements and see the results immediately.

1. Open IDLE by searching for "IDLE" in your system's search bar.

2. In the IDLE interactive shell, type the following command and press Enter:

    ```python
    print("Hello World")
    ```

   You should see the output `Hello World` displayed in the shell.

3. To exit the interactive shell, you can type `exit()` or close the IDLE window.

## Using a Script File in IDLE

1. Open IDLE and create a new file by selecting `File -> New File` from the menu.

2. Copy and paste the following code into the editor:

    ```python
    # Filename: hello_world.py

    print("Hello World")
    ```

3. Save the file with a `.py` extension, for example, `hello_world.py`.

4. Run the script by selecting `Run -> Run Module` from the menu, or you can press `F5`.

   You should see the output `Hello World` displayed in the IDLE Shell.

Congratulations! You've just run your first Python program using IDLE, both in the interactive shell and as a script file.

# Python Built-in Data Types

In programming, data types are crucial concepts. Variables in Python can store data of different types, and each type has its unique characteristics and uses. Here are the built-in data types in Python, categorized by their functionality:

## 1. Text Type

### String (`str`)

Represents sequences of characters, enclosed in single (`'`) or double (`"`) quotes.

## 2. Numeric Types

- **Integer (`int`):** Represents whole numbers without decimal points.
- **Float (`float`):** Represents numbers with decimal points.
- **Complex (`complex`):** Represents numbers in the form of real and imaginary parts.

## 3. Sequence Types

- **List:** An ordered collection of items.
- **Tuple:** Similar to a list but immutable (cannot be modified).
- **Range:** Represents a sequence of numbers.

## 4. Mapping Type

- **Dictionary (`dict`):** A collection of key-value pairs.

## 5. Set Types

- **Set:** An unordered collection of unique items.
- **Frozenset:** Similar to a set but immutable.

## 6. Boolean Type

- **Boolean (`bool`):** Represents the truth values `True` or `False`.

## 7. Binary Types

- **Bytes (`bytes`):** Represents a sequence of bytes.
- **Bytearray (`bytearray`):** Similar to bytes but mutable.
- **Memoryview (`memoryview`):** Represents a view of the memory.

## 8. None Type

- **NoneType (`None`):** Represents the absence of a value or a null value.

Understanding these built-in data types is essential for effective programming in Python.


# Python Data Types and Examples

In Python, the data type is set when you assign a value to a variable. Here are examples of different data types in Python:

| Example                   | Data Type    |
|---------------------------|--------------|
| `x = "Hello World"`       | `str`        |
| `x = 20`                  | `int`        |
| `x = 20.5`                | `float`      |
| `x = 1j`                  | `complex`    |
| `x = ["apple", "banana", "cherry"]`  | `list`   |
| `x = ("apple", "banana", "cherry")`  | `tuple`  |
| `x = range(6)`            | `range`      |
| `x = {"name": "John", "age": 36}`     | `dict`   |
| `x = {"apple", "banana", "cherry"}`   | `set`    |
| `x = frozenset({"apple", "banana", "cherry"})`  | `frozenset`  |
| `x = True`                | `bool`       |
| `x = b"Hello"`            | `bytes`      |
| `x = bytearray(5)`        | `bytearray`  |
| `x = memoryview(bytes(5))` | `memoryview` |
| `x = None`                | `NoneType`   |

Understanding these examples will help you recognize and work with different data types in Python effectively.




# Python Variable Naming Rules

In Python, variable names must adhere to certain rules to be considered valid. Here are the key rules to follow:

1. The variable's first character must be an underscore (`_`) or an alphabet (a-z, A-Z).

2. Subsequent characters can be letters (lowercase or uppercase), underscores, or digits (0-9).

3. White spaces and special characters (!, @, #, %, etc.) are not allowed in the identifier name. (`^`, `&`, `*`, etc.).

4. Identifiers should not match any reserved keyword in the Python language.

5. Names of identifiers are case-sensitive; for example, `my_name` and `MyName` are considered different.

## Examples of Valid Identifiers:

- `a123`
- `_n`
- `n_9`
- etc.

## Examples of Invalid Identifiers:

- `1a`
- `n%4`
- `n 9`
- etc.

Ensure that your variable names follow these rules to create valid and effective Python code.


# Python Operators

Operators in Python are special symbols or keywords used to perform operations on variables and values. Here are some commonly used operators:

## 1. Arithmetic Operators

Arithmetic operators perform mathematical operations on numeric values.

| Operator | Description   | Example    |
|----------|---------------|------------|
| `+`      | Addition      | `x = 5 + 3` |
| `-`      | Subtraction   | `y = 8 - 2` |
| `*`      | Multiplication| `z = 4 * 6` |
| `/`      | Division      | `a = 10 / 2`|
| `%`      | Modulus       | `b = 15 % 4`|
| `**`     | Exponent      | `c = 2 ** 3`|

## 2. Comparison Operators

Comparison operators compare two values and return a boolean result.

| Operator | Description        | Example       |
|----------|--------------------|---------------|
| `==`     | Equal              | `x == y`      |
| `!=`     | Not Equal          | `a != b`      |
| `<`      | Less Than          | `m < n`       |
| `>`      | Greater Than       | `p > q`       |
| `<=`     | Less Than or Equal | `r <= s`      |
| `>=`     | Greater Than or Equal | `u >= v`    |

## 3. Assignment Operators

Assignment operators assign values to variables.

| Operator | Description        | Example       |
|----------|--------------------|---------------|
| `=`      | Assign             | `x = 5`       |
| `+=`     | Add and Assign     | `y += 3`      |
| `-=`     | Subtract and Assign| `z -= 2`      |
| `*=`     | Multiply and Assign| `a *= 4`      |
| `/=`     | Divide and Assign  | `b /= 2`      |

## 4. Logical Operators

Logical operators perform logical operations on boolean values.

| Operator | Description        | Example       |
|----------|--------------------|---------------|
| `and`    | Logical AND        | `x and y`     |
| `or`     | Logical OR         | `a or b`      |
| `not`    | Logical NOT        | `not x`       |


# Python Bitwise, Membership, and Identity Operators

In addition to arithmetic, comparison, assignment, and logical operators, Python provides bitwise, membership, and identity operators. Here are examples of these operators:

## 1. Bitwise Operators

Bitwise operators perform operations on individual bits of binary numbers.

| Operator | Description         | Example       |
|----------|---------------------|---------------|
| `&`      | Bitwise AND         | `x = 5 & 3`   |
| `|`      | Bitwise OR          | `y = 8 | 2`   |
| `^`      | Bitwise XOR         | `z = 4 ^ 6`   |
| `~`      | Bitwise NOT         | `a = ~10`     |
| `<<`     | Left Shift          | `b = 15 << 2` |
| `>>`     | Right Shift         | `c = 8 >> 2`  |

## 2. Membership Operators

Membership operators test if a sequence (such as a string, list, or tuple) contains a specified value.

| Operator | Description         | Example       |
|----------|---------------------|---------------|
| `in`     | True if value is found in the sequence | `'apple' in fruits` |
| `not in` | True if value is not found in the sequence | `'orange' not in fruits` |

Example:
```python
fruits = ["apple", "banana", "cherry"]
print("banana" in fruits)  # Output: True
print("orange" not in fruits)  # Output: True
```
# Python Input from User

In Python, you can interact with the user by taking input using the `input()` function. Here's how you can use it:

## Input Function

The `input()` function allows you to prompt the user for input. It takes a string as an argument, which is displayed to the user, and returns the entered value as a string.

```python
# Example 1
user_name = input("Enter your name: ")
print("Hello, " + user_name + "!")

# Example 2
age = int(input("Enter your age: ")) # Convert the input to an integer
print("You will be " + str(age + 1) + " years old next year.")

```


# Python Conditional Statements

Conditional statements in Python allow you to make decisions in your code based on certain conditions. The primary conditional statements are `if`, `elif` (else if), and `else`. Here are examples of how to use them:

## 1. If Statement

The `if` statement is used to execute a block of code only if the specified condition is `True`.

```python
x = int(input("Enter a number : "))

if x > 5:
    print("x is greater than 5")

```

## 2. If-Else Statement

The `if-else` statement is used to execute one block of code if the specified condition is `True` and another block if it is `False`.

```python
y =int(input("Enter a number : ")) 

if y % 2 == 0:
    print("y is even")
else:
    print("y is odd")
```
---

# Python If-Else Statements - Quiz Questions

## Question 1
### Temperature Checker
Write a Python program that takes the user's input for the current temperature. If the temperature is above 30 degrees Celsius, print "It's a hot day!" Otherwise, print "It's a pleasant day."

## Question 2
### Age Classifier
Create a Python program that prompts the user to enter their age. Classify and print the age group based on the following criteria:
- 0-12: Child
- 13-19: Teenager
- 20-35: Young Adult
- 36 and above: Adult

## Question 3
### Number Comparison
Write a Python program that takes two numbers as input from the user. Compare the numbers and print:
- "Number 1 is greater" if the first number is greater,
- "Number 2 is greater" if the second number is greater, or
- "Both numbers are equal" if they are the same.

## Question 4
### Positive or Negative
Create a Python program that accepts a numeric input. Check if the number is positive, negative, or zero, and print the result accordingly.

## Question 5
### Password Validator
Design a Python program that prompts the user to enter a password. Check the strength of the password using the following rules:
- If the length is less than 8 characters, print "Weak."
- If it includes both uppercase and lowercase letters, print "Strong."
- If it includes numbers and special characters, print "Very Strong."
- Otherwise, print "Moderate."

---

## 3. If-Elif-Else Statement
The `if-elif-else` statement allows you to check multiple conditions in sequence.

```python
z = int(input("Enter a number : "))

if z > 0:
    print("z is positive")
elif z < 0:
    print("z is negative")
else:
    print("z is zero")

```

## 4. Nested If Statements
You can use nested `if` statements to handle more complex conditions.
```python
age = 25

if age > 18:
    print("You are an adult")
    if age > 21:
        print("You can purchase alcohol")
else:
    print("You are a minor")

```

# Python For Loops

A `for` loop in Python is used for iterating over a sequence, such as a list, tuple, dictionary, set, or string. It is similar to an iterator method found in other object-oriented programming languages.

## Syntax:

```python
for variable in sequence:
    # Code to be executed in each iteration
```
## Example 2: Iterating over a Range
```python
for num in range(1, 5):
    print(num)
```    
##### Output: 
#
```python
1
2
3
4
```
# Python While Loop Syntax

A `while` loop in Python is used to repeatedly execute a block of code as long as a specified condition is `True`. Here is the syntax:

```python
while condition:
    # Code to be executed while the condition is True
```

The `condition` is checked before each iteration. If the condition is `True`, the code inside the loop is executed; otherwise, the loop is terminated.

## Example
```python
# Example: Print numbers from 1 to 5 using a while loop
count = 1

while count <= 5:
    print(count)
    count += 1
```
##### Output: 
#
```python
1
2
3
4
```
## Question on loop
### for loop
* prime number
* fibo-nacci
* factor
* factorial
* sum of first 10 number
* tables `2 x 1 = 2`
#### while loop
* sum of first 10 number
* sum of digit `123 = 1 + 2 + 3 = 6 `
* reverse of Number `231 = 132`
* palindrome number `121 = 121`
* armstrong number `153 = 1^3 + 5^3 + 3^3 = 153`

# Python Collections (Arrays)
There are four collection data types in the Python programming language:
* __List__ is a collection which is ordered and changeable. Allows duplicate members.
* __Tuple__ is a collection which is ordered and unchangeable. Allows duplicate members.
* __Set__ is a collection which is unordered, unchangeable*, and unindexed. No duplicate members.
* __Dictionary__ is a collection which is ordered** and changeable. No duplicate members.

## List

A list in Python is a collection of ordered and mutable elements.
Lists are used to store multiple items in a single variable.

### Syntax:

```python
my_list = [element1, element2, element3, ...]
```
## Example: 
```python
fruits = ["apple", "banana", "cherry"]
print(fruits)
# printing the type of list  
print(type(fruits))  
 
```
#### Output:
```python
['apple', 'banana', 'cherry']
< class ' list ' >
```

---

# List Questions and Solutions

## 1. List Manipulation

Write a Python program that initializes an empty list and adds the numbers 1 to 5 to the list using a loop.
> Note: Here `append()` is build-in  function  
```python
my_list = []

for num in range(1, 6):
    my_list.append(num)

print(my_list)
```
***
User input  **approach**
```python
my_list = []
len = int(input("Enter size of list : "))
for i in range(len):
    num = int(input("Enter value: "))
    my_list.append(num)

print(my_list)
```
***
## 2. List Summation
Create a Python program that calculates the sum of all elements in a given list.
```python
numbers = [3, 7, 1, 4, 9]
list_sum =0
for i in range(len(number)):
    list_sum = list_sum + i
print("Sum:", list_sum)
```

## 3.  List Filtering
Write a Python program that takes a list of numbers and prints only the even numbers.
## 4.List **largest & smallest element**
Write a python program that takes a list of number and find largest element & Smallest from given list 
## 5. Bubble Sort Implementation
Write a Python program to implement the Bubble Sort algorithm for sorting a list of numbers. 
```python
list1 = []
len = int(input("Enter size of list : "))
for i in range(len):
    num = int(input("Enter value: "))
    my_list.append(num)
    
print("before sort : ",list1)

for i in range(n - 1):
    for j in range(0, n - i - 1):
        if list1[j] > list1[j + 1]:
            tmp = list1[j]
            list1[j] = list1[j+1]
            list1[j+1] = tmp

print("Sorted List:", list1)
```
---

# Python List Built-in Functions

Python provides several built-in functions for working with lists. Here are some commonly used ones along with examples:

# List Methods in Python

Python lists come with a set of built-in methods for various operations. Here is an overview of some common list methods:

| Method          | Description                                               |
| --------------- | --------------------------------------------------------- |
| `append(x)`     | Adds an element `x` to the end of the list.               |
| `extend(iterable)` | Extends the list by appending elements from the iterable. |
| `insert(i, x)`  | Inserts an element `x` at the specified index `i`.        |
| `remove(x)`     | Removes the first occurrence of element `x` from the list.|
| `pop(i)`        | Removes and returns the element at the specified index `i`. If no index is specified, removes and returns the last element. |
| `clear()`       | Removes all elements from the list.                       |
| `index(x, start, end)` | Returns the index of the first occurrence of element `x` (optional start and end parameters define a search range). |
| `count(x)`      | Returns the number of occurrences of element `x` in the list. |
| `sort(key=None, reverse=False)` | Sorts the elements of the list in ascending order (optional `key` and `reverse` parameters allow customization). |
| `reverse()`     | Reverses the order of the elements in the list.            |
| `copy()`        | Returns a shallow copy of the list.                       |

### Example:

```python
# Example usage of list methods
my_list = [1, 2, 3, 4, 5]

# Using list methods
my_list.append(6)
print("After append:", my_list)

my_list.extend([7, 8, 9])
print("After extend:", my_list)

my_list.insert(1, 10)
print("After insert:", my_list)

my_list.remove(3)
print("After remove:", my_list)

popped_element = my_list.pop()
print(f"Popped element: {popped_element}, List after pop:", my_list)

my_list.clear()
print("After clear:", my_list)
```
# More example

## 1. `len()`

Returns the length (number of elements) of a list.

### Example:

```python
my_list = [1, 2, 3, 4, 5]
length = len(my_list)
print("Length of the list:", length)
```
#### Output:
   Length of the list: 5
# 2. `append()`
Adds an element to the end of the list.

### Example:
```python
fruits = ["apple", "banana", "cherry"]
fruits.append("orange")
print("Updated List:", fruits)
```
#### Output:
  Updated List: ['apple', 'banana', 'cherry', 'orange'] 

# 3. `remove()`
Removes the first occurrence of a specified element from the list.

### Example:
```python
numbers = [1, 2, 3, 4, 2, 5]
numbers.remove(2)
print("List after removing 2:", numbers)
```
####  Output:
List after removing 2: [1, 3, 4, 2, 5]
# 4. `sort()`
Sorts the elements of a list in ascending order.

### Example:
``` python
scores = [85, 92, 78, 95, 88]
scores.sort()
print("Sorted Scores:", scores)
```
### Output:
Sorted Scores: [78, 85, 88, 92, 95]
# 5. `count()`
Returns the number of occurrences of a specified element in the list.

### Example:
```python
numbers = [1, 2, 3, 4, 2, 5, 2]
count_of_2 = numbers.count(2)
print("Count of 2:", count_of_2)
```
#### Output:
    Count of 2: 3


# Python Tuples

* Tuples are an immutable data type, meaning their elements cannot be changed after they are generated.
+ Each element in a tuple has a specific order that will never change because tuples are ordered sequences.

## Example:

```python
# Creating an empty tuple
empty_tuple = ()
print("Empty tuple: ", empty_tuple)

# Creating a tuple with integers
int_tuple = (4, 6, 8, 10, 12, 14)
print("Tuple with integers: ", int_tuple)

# Creating a tuple with objects of different data types
mixed_tuple = (4, "Python", 9.3)
print("Tuple with different data types: ", mixed_tuple)

# Concatenating Tuples
tuple1 = (1, 2, 3)
tuple2 = ("a", "b", "c")

tuple3 = tuple1 + tuple2
print("Concatenated Tuple:", tuple3)

#nested tuple
nested_tuple = ((1, 2, 3), ("a", "b", "c"))

print("Nested Tuple:", nested_tuple)

```
# Tuple Methods in Python

Python tuples, being immutable, have fewer methods compared to lists. Here is an overview of some common tuple methods:

| Method          | Description                                               |
| --------------- | --------------------------------------------------------- |
| `count(x)`      | Returns the number of occurrences of element `x` in the tuple. |
| `index(x, start, end)` | Returns the index of the first occurrence of element `x` (optional start and end parameters define a search range). |

### Example:

```python
# Example usage of tuple methods
my_tuple = (1, 2, 3, 4, 1, 2, 5)

# Using tuple methods
count_of_2 = my_tuple.count(2)
print("Count of 2:", count_of_2)

index_of_4 = my_tuple.index(4)
print("Index of 4:", index_of_4)
```

## Question 
###  1. Tuple Manipulation:
Write a Python program that initializes a tuple with the first five even numbers and prints the tuple.
### 2.Tuple Concatenation:
Create a program that concatenates two tuples and prints the result.
### 3.Tuple Searching:
Design a program that takes a tuple of names and checks if a given name exists in the tuple.
### 4.Tuple Nesting:
Create a program that uses nested tuples to represent a matrix and prints its elements.
### 5.Tuple Slicing:
Write a Python program that takes a tuple of numbers and prints a slice containing the middle three elements.

# Python Dictionaries

* Dictionaries in Python are used to store data values in key:value pairs. They are collections that are ordered, changeable, and do not allow duplicates.
* Dictionary items are presented in key:value pairs, and can be referred to by using the key name.

## Example:

```python
# Creating a dictionary
my_dict = {
    "name": "John",
    "age": 30,
    "city": "New York"
}

# Accessing dictionary items
print("Name:", my_dict["name"])
print("Age:", my_dict["age"])
print("City:", my_dict["city"])
```
### Output: 
```python
Name: John
Age: 30
City: New York
```
**In the provided example, we create a dictionary my_dict with keys ("name", "age", "city") and corresponding values. The dictionary allows us to access the values using the keys, providing a convenient way to organize and retrieve data.**

# Question 
## 1. Creating Dictionaries:
Create a dictionary representing information about your favorite book. Include keys such as "title," "author," and "publication_year."
## 2. Accessing Dictionary Values:

Write a program that accesses and prints the value associated with the key "population" in a dictionary representing information about a country.
## 3. Dictionary Manipulation:
Add a new key-value pair to a dictionary representing a computer, with the key as "RAM" and the value as the amount of RAM in gigabytes.

# Dictionary Methods in Python

Python dictionaries come with a set of built-in methods for various operations. Here is an overview of some common dictionary methods:

| Method        | Description                                                                           |
|---------------|--------------------------------------------------------|
| `clear()`     | Removes all the elements from the dictionary.                                          |
| `copy()`      | Returns a copy of the dictionary.                                                      |
| `fromkeys(keys, value)` | Returns a dictionary with the specified keys and a default value.             |
| `get(key, default)`      | Returns the value of the specified key. If not found, returns the specified default value. |
| `items()`     | Returns a list containing a tuple for each key-value pair in the dictionary.          |
| `keys()`      | Returns a list containing the dictionary's keys.                                      |
| `pop(key)`    | Removes the element with the specified key.                                           |
| `popitem()`   | Removes the last inserted key-value pair.                                             |
| `setdefault(key, default)` | Returns the value of the specified key. If the key does not exist, it inserts the key with the specified default value. |
| `update(dict2)` | Updates the dictionary with the specified key-value pairs from another dictionary.  |
| `values()`    | Returns a list of all the values in the dictionary.                                    |

### Example:

```python
# Example usage of dictionary methods
my_dict = {
    "name": "John",
    "age": 30,
    "city": "New York"
}

# Using dictionary methods
my_dict.clear()
print("Cleared Dictionary:", my_dict)

copy_dict = my_dict.copy()
print("Copied Dictionary:", copy_dict)

keys_list = ["name", "age", "city"]
values_dict = dict.fromkeys(keys_list, "Unknown")
print("Dictionary with Default Values:", values_dict)

age_value = my_dict.get("age", "Not Found")
print("Age Value:", age_value)

items_list = my_dict.items()
print("Items List:", items_list)

keys_list = my_dict.keys()
print("Keys List:", keys_list)

my_dict.pop("age")
print("Dictionary after 'pop' operation:", my_dict)

my_dict.setdefault("gender", "Male")
print("Dictionary after 'setdefault' operation:", my_dict)

update_dict = {"city": "Chicago", "country": "USA"}
my_dict.update(update_dict)
print("Updated Dictionary:", my_dict)

values_list = my_dict.values()
print("Values List:", values_list)
```

# String in Python

A string is a data structure in Python that represents a sequence of characters. It is an immutable data type, meaning that once you have created a string, you cannot change it. Strings are used widely in many different applications, such as storing and manipulating text data, representing names, addresses, and other types of data that can be represented as text.

## What is a String in Python?

Python does not have a character data type; a single character is simply a string with a length of 1.

### Example:

```python
"hello" 'hello' or 'h'
```

\* In Python, a string is a sequence of characters, and it is one of the fundamental data types. Strings are used to represent textual data. 

## Creating Strings

### Single and Double Quotes

```python
single_quoted = 'Hello, World!'
double_quoted = "Hello, World!"
```
### Triple Quotes (for multiline strings)
```python
multiline_string = '''This is
a multiline
string.'''
```
# Python Program to Access 
```python
# characters of String 
String1 = "Hello Oneknown"
print("Initial String: ") 
print(String1) 

# Printing First character 
print("\nFirst character of String is: ") 
print(String1[0]) 

# Printing Last character 
print("\nLast character of String is: ") 
print(String1[-1]) 
```
#### Output
```
Initial String: 
GeeksForGeeks
First character of String is: 
H
Last cha racter of String is: 
n
```
# String Slicing in Python

In Python, string slicing is performed using a colon (`:`) to access a range of characters in a string. It's important to note that the string returned after slicing includes the character at the start index but not the character at the last index.

## Example:

```python
# Original String
original_string = "Hello, World!"

# Using String Slicing
substring = original_string[3:12]

# Result: "lo, Worl"


# String Slicing in Python

# Original String
original_string = "Hello, World!"

# Using String Slicing
substring = original_string[3:12]

# Displaying the Result
print(substring)
```

# Reversing a Python String

Strings in Python can be reversed by using the string slicing method. Here's a simple example:

## Example:

```python
# Original String
original_string = "Hello, World!"

# Reversing the String
reversed_string = original_string[::-1]

# Displaying the Result
print(reversed_string)
```

# Common String Methods in Python

Here is a table summarizing some common string methods in Python:

| Method                  | Description                                       | Example                            | Output                             |
| ----------------------- | ------------------------------------------------- | ---------------------------------- | -----------------------------------|
| `capitalize()`          | Converts the first character to uppercase         | `"hello".capitalize()`             | `"Hello"`                         |
| `upper()`               | Converts all characters to uppercase              | `"hello".upper()`                  | `"HELLO"`                         |
| `lower()`               | Converts all characters to lowercase              | `"HELLO".lower()`                  | `"hello"`                         |
| `title()`               | Converts the first character of each word to uppercase | `"hello world".title()`       | `"Hello World"`                   |
| `count(substring)`      | Returns the number of occurrences of a substring   | `"hello".count("l")`               | `2`                               |
| `find(substring)`       | Returns the lowest index of a substring (or -1 if not found) | `"hello".find("l")`         | `2`                               |
| `replace(old, new)`     | Replaces occurrences of a substring with another string | `"hello".replace("l", "z")`   | `"hezzo"`                         |
| `startswith(prefix)`    | Returns `True` if the string starts with the specified prefix | `"hello".startswith("he")`  | `True`                            |
| `endswith(suffix)`      | Returns `True` if the string ends with the specified suffix | `"hello".endswith("lo")`      | `True`                            |
| `strip()`               | Removes leading and trailing whitespaces           | `"  hello  ".strip()`              | `"hello"`                        |
| `split(delimiter)`      | Splits the string into a list using the specified delimiter | `"apple,banana,orange".split(",")` | `['apple', 'banana', 'orange']` |
| `join(iterable)`        | Joins elements of an iterable into a string        | `",".join(["apple", "banana", "orange"])` | `"apple,banana,orange"`        |
| `len()`                 | Returns the length of the string                   | `len("hello")`                     | `5`                               |
---
# Question:
## 1.Concatenation:

Write a Python program that takes two strings as input from the user and concatenates them. Print the result.
## 2.Palindrome Check:

Write a function in Python to check if a given string is a palindrome.
## 3.Character Count:

Write a Python function that takes a string as input and returns a dictionary containing the count of each character in the string.
## 4.Vowel Count:

Write a Python program that takes a string as input and prints the count of vowels (a, e, i, o, u) in the string.
## 5.Reverse Words:

Write a function that reverses the order of words in a given string. For example, input: "Hello World," output: "World Hello."
## 6.String Encryption:

Write a Python program that takes a string as input and replaces each character with its ASCII value. Print the encrypted string.

## 7.Title Case:

Write a Python program that takes a sentence as input and converts it to title case (capitalize the first letter of each word).

## 8.Toggle case
Write a Python program that takes a string as input and small  into capital and capital  into small letter ( eg : PyThOn  = pYtHoN `toggle case` )

---


# Python Functions

A function in Python is a block of statements that performs a specific task. The purpose is to group commonly or repeatedly performed tasks, making the code more readable and reusable.

## Benefits of Using Functions

1. **Increase Code Readability:**
   Functions allow code to be organized into logical blocks, enhancing readability.

2. **Increase Code Reusability:**
   Code inside a function can be reused by calling the function with different inputs, reducing redundancy.

# Types of Functions in Python
##### There are mainly two types of functions in Python.
* **Built-in library function**:
    These are Standard functions in Python that are available to use.
* **User-defined function**:
    We can create our own functions based on our requirements.
## Python Function Declaration

The syntax to declare a function is:

```python
# A simple Python function 
def fun():
    # Function body
    # Perform specific tasks

#A parameterized function
def function_name(parameters):
    # Function body
    # Perform specific tasks
    
# Return type
def function_name(parameters):
    # Function body
    # Perform specific tasks
    return result
```

# Lambda Functions in Python

A lambda function is a small anonymous function in Python. It can take any number of arguments but can only have one expression.

## Syntax

The syntax for a lambda function is as follows:

```python
lambda arguments: expression
```
###  example
```python
# Using a lambda function to add 10 to a number
x = lambda a: a + 10
print(x(5))

# Python code to illustrate the cube of a number
# using lambda function
cube_v2 = lambda x : x*x*x
print(cube(7))
```
---

# Question :
### 1.Function Basics:
Write a function named greet that takes a name as an argument and prints a greeting message.
### 2.Function Parameters:

Create a function calculate_area that calculates and returns the area of a rectangle given its length and width as parameters.
### 3.Function Return Values:

Define a function is_even that takes an integer as input and returns True if it's even and False otherwise.
### 4.Function with Default Parameter:

Write a function multiply that takes two parameters, a and b, with a default value of 1 for b, and returns their product.
### 5.Variable Scope:

Explain the concept of variable scope in a function. Provide an example.

### Lambda Function:

Create a lambda function to square a given number.

---

# Python Exception handling
Exception handling in Python is a mechanism that allows you to gracefully handle runtime errors and prevent your program from crashing. The key components of exception handling include the `try`, `except`, `else`, and `finally` blocks. Here's an explanation:

#### Try-Except Block
The `try` block is used to enclose the code that might raise an exception. If an exception occurs within the `try` block, it is caught and handled by the corresponding `except` block.
```python
try:
    # Code that might raise an exception
    result = 10 / 0
except ZeroDivisionError:
    # Handle the specific exception (division by zero)
    print("Cannot divide by zero.")
except Exception as e:
    # Handle other exceptions
    print(f"An error occurred: {e}")

```
##### In this example:
* The `try` block contains code that might raise an exception (division by zero).
* The `except` block catches specific exceptions (`ZeroDivisionError`) and handles them by printing a message.
* The `except` block with `Exception as e` catches any other exceptions and prints a generic error message.

#### Else Block
The `else` block contains code to be executed if there is no exception in the `try` block.
```python
else:
    # Code to be executed if there is no exception
    print("Division successful.")
```

#### Finally Block
The `finally` block contains code that will always be executed, regardless of whether an exception occurred or not.

```python
finally:
    # Code to be executed regardless of the result
    print("This will always be executed.")
```
#### Full Example
```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero.")
except Exception as e:
    print(f"An error occurred: {e}")
else:
    print("Division successful.")
finally:
    print("This will always be executed.")
```

In this example, if a division by zero occurs, the `ZeroDivisionError` is caught and handled. If there's any other exception, it is
caught by the generic `Exception` block. The `else` block is executed if there is no exception, and the `finally` block is always executed.

| File Mode | Description                                          |
|------------|------------------------------------------------------|
| `"r"`      | Read mode. Opens the file for reading.               |
| `"w"`      | Write mode. Opens the file for writing. Truncates the file if it exists or creates a new file. |
| `"a"`      | Append mode. Opens the file for writing. Appends to the end of the file or creates a new file. |
| `"x"`      | Exclusive creation mode. Creates a new file but fails if the file already exists. |
| `"+"`      | Read and write mode. Allows both reading and writing. Used in conjunction with other modes, e.g., `"r+"`, `"w+"`. |

> **Note**: The file should exist in the same directory as the Python
script, otherwise full address of the file should be written. If the file is
> not exist, then an error is generated, that the file does not exist.

#### Example of files
##### Write mode
```python
# Open a file in write mode ("w")
file = open("example.txt", "w") 
# Write content to the file (truncates the file if it exists or creates a new file)
file.write("Hello, this is a sample text.")
file.close()
```
#### Append mode
```python
# Open a file in write mode ("a")
file = open("example.txt", "a") 
# Write content to the file (truncates the file if it exists or creates a new file)
file.write("Hello, this is a sample text.")
file.write("\nHello,User.")
file.close()
```
#### Read mode

```python
# Python program to demonstrate
# opening a file
# Open function to open the file "myfile.txt"
# (same directory) in read mode and store
# it's reference in the variable file1

file1 = open("myfile.txt")
# Reading from file
print(file1.read())
file1.close()
```
#### Read and write mode

```python
# Open a file for writing and reading
file = open('test.txt', 'w+')

# Write some data to the file
file.write('Hello, world!')

# Move the file pointer back to the beginning of the file
file.seek(0)

# Read the data from the file
data = file.read()

# Print the data to the console
print(data)

# Close the file when you're done
file.close()
```



