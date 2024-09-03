### Student Notes on Data Types, Input, and Output Statements

---

#### **1. Data Types in Python**

Data types in Python refer to the kind of value a variable holds. Understanding data types is crucial because it helps you know how to work with and manipulate the data.

**Common Data Types:**

1. **Integer (`int`)**: 

   - Represents whole numbers, positive or negative, without any decimal points.

   - Example:

     ```python

     age = 25  # age is an integer

     ```

2. **Floating Point (`float`)**:

   - Represents real numbers with decimal points.

   - Example:

     ```python

     temperature = 36.5  # temperature is a float

     ```

3. **String (`str`)**:

   - Represents a sequence of characters, enclosed in quotes.

   - Example:

     ```python

     name = "Alice"  # name is a string

     ```

4. **Boolean (`bool`)**:

   - Represents one of two values: `True` or `False`.

   - Example:

     ```python

     is_student = True  # is_student is a boolean

     ```

5. **List (`list`)**:

   - An ordered collection of items, which can be of different types.

   - Example:

     ```python

     fruits = ["apple", "banana", "cherry"]  # fruits is a list

     ```

6. **Tuple (`tuple`)**:

   - Similar to lists, but tuples are immutable (cannot be changed after creation).

   - Example:

     ```python

     coordinates = (10, 20)  # coordinates is a tuple

     ```

7. **Dictionary (`dict`)**:

   - An unordered collection of key-value pairs.

   - Example:

     ```python

     student = {"name": "John", "age": 20}  # student is a dictionary

     ```

**Task:**

- Create variables of each type (int, float, str, bool, list, tuple, dict) and print their values.

- Example:

  ```python

  # Example of a task

  x = 10

  print(x)

  ```

---

#### **2. Type Checking**

In Python, you can check the type of a variable using the `type()` function. This is useful to confirm what kind of data a variable holds.

**Example:**

```python

number = 5

print(type(number))  # Output: <class 'int'>

name = "Alice"

print(type(name))  # Output: <class 'str'>

```

**Task:**

- Create a variable of each type and use the `type()` function to check its type.

- Example:

  ```python

  is_active = False

  print(type(is_active))  # Output: <class 'bool'>

  ```

---

#### **3. Input Statements (`input()`)**

The `input()` function is used to take input from the user. The input received is always a string by default, even if the user enters a number.

**Example:**

```python

user_name = input("Enter your name: ")

print("Hello, " + user_name + "!")

```

**Converting Input to Other Types:**

- If you need the input to be a number, you can convert it using `int()` or `float()`.

**Example:**

```python

age = int(input("Enter your age: "))

print("You are " + str(age) + " years old.")

```

**Task:**

- Write a program that asks the user for their name and age, then prints a message using the provided information.

- Example:

  ```python

  # Task example

  name = input("Enter your name: ")

  age = int(input("Enter your age: "))

  print(f"Hello {name}, you are {age} years old.")

  ```

---

#### **4. Output Statements (`print()`)**

The `print()` function is used to display output to the screen. It can be used to show text, variables, and even results of expressions.

**Example:**

```python

print("Hello, World!")

```

**Using f-Strings for Output:**

- f-Strings provide a way to format strings that is more readable and concise.

- You can include variables directly inside curly braces `{}` within the string.

**Example:**

```python

name = "Alice"

age = 25

print(f"My name is {name} and I am {age} years old.")

```

**Task:**

- Write a program that defines two variables (like `name` and `age`) and uses f-Strings to print a formatted sentence.

- Example:

  ```python

  # Task example

  product = "laptop"

  price = 999.99

  print(f"The price of the {product} is ${price}.")

  ```

---

### **Summary Questions**

1. **Data Types:**

   - What data type would you use to store a person's age?

   - How do you define a list in Python? Give an example.

2. **Type Checking:**

   - What is the purpose of the `type()` function?

   - How would you check if a variable `height` is of type `float`?

3. **Input Statements:**

   - How does the `input()` function behave when you enter a number? What type is it?

   - Write a code snippet that asks for two numbers and prints their sum.

4. **Output Statements:**

   - What is an f-String and how is it useful?

   - How would you print a message that includes both a string and a number using `print()`?

---