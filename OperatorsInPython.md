### Student Notes: Python Operators

---

#### **1. Arithmetic Operators**

Arithmetic operators are used to perform basic mathematical operations. These include addition, subtraction, multiplication, division, and more.

**List of Arithmetic Operators:**

1. **Addition (`+`)**:

   - Adds two numbers together.

   - **Example:**

     ```python

     result = 5 + 3  # result is 8

     ```

2. **Subtraction (`-`)**:

   - Subtracts the right-hand operand from the left-hand operand.

   - **Example:**

     ```python

     result = 10 - 4  # result is 6

     ```

3. **Multiplication (`*`)**:

   - Multiplies two numbers.

   - **Example:**

     ```python

     result = 7 * 3  # result is 21

     ```

4. **Division (`/`)**:

   - Divides the left-hand operand by the right-hand operand.

   - **Example:**

     ```python

     result = 16 / 4  # result is 4.0

     ```

5. **Modulus (`%`)**:

   - Returns the remainder when the left-hand operand is divided by the right-hand operand.

   - **Example:**

     ```python

     result = 10 % 3  # result is 1

     ```

6. **Exponentiation (`**`)**:

   - Raises the left-hand operand to the power of the right-hand operand.

   - **Example:**

     ```python

     result = 2 ** 3  # result is 8

     ```

7. **Floor Division (`//`)**:

   - Divides and returns the largest whole number less than or equal to the result.

   - **Example:**

     ```python

     result = 10 // 3  # result is 3

     ```

**Task:**

- Write a program that calculates the area of a rectangle (length × width) and prints the result.

- Example:

  ```python

  length = 5

  width = 3

  area = length * width

  print(f"The area of the rectangle is {area}")

  ```

---

#### **2. Comparison Operators**

Comparison operators are used to compare two values. They return either `True` or `False` based on the comparison.

**List of Comparison Operators:**

1. **Equal to (`==`)**:

   - Checks if the values of two operands are equal.

   - **Example:**

     ```python

     result = (5 == 5)  # result is True

     ```

2. **Not equal to (`!=`)**:

   - Checks if the values of two operands are not equal.

   - **Example:**

     ```python

     result = (5 != 3)  # result is True

     ```

3. **Greater than (`>`)**:

   - Checks if the left-hand operand is greater than the right-hand operand.

   - **Example:**

     ```python

     result = (10 > 3)  # result is True

     ```

4. **Less than (`<`)**:

   - Checks if the left-hand operand is less than the right-hand operand.

   - **Example:**

     ```python

     result = (2 < 5)  # result is True

     ```

5. **Greater than or equal to (`>=`)**:

   - Checks if the left-hand operand is greater than or equal to the right-hand operand.

   - **Example:**

     ```python

     result = (7 >= 7)  # result is True

     ```

6. **Less than or equal to (`<=`)**:

   - Checks if the left-hand operand is less than or equal to the right-hand operand.

   - **Example:**

     ```python

     result = (4 <= 6)  # result is True

     ```

**Task:**

- Write a program that compares two numbers and prints whether the first number is greater than the second number.

- Example:

  ```python

  num1 = 10

  num2 = 8

  result = num1 > num2

  print(f"Is {num1} greater than {num2}? {result}")

  ```

---

#### **3. Logical Operators**

Logical operators are used to combine conditional statements. They return `True` or `False` based on the logic of the conditions.

**List of Logical Operators:**

1. **AND (`and`)**:

   - Returns `True` if both operands are true.

   - **Example:**

     ```python

     result = (5 > 3 and 8 > 6)  # result is True

     ```

2. **OR (`or`)**:

   - Returns `True` if at least one of the operands is true.

   - **Example:**

     ```python

     result = (5 > 3 or 2 > 4)  # result is True

     ```

3. **NOT (`not`)**:

   - Reverses the result of the operand.

   - **Example:**

     ```python

     result = not (5 > 3)  # result is False

     ```

**Task:**

- Write a program that checks if a number is positive and even.

- Example:

  ```python

  num = 8

  is_positive_and_even = (num > 0 and num % 2 == 0)

  print(f"Is the number positive and even? {is_positive_and_even}")

  ```

---

### **Summary Questions**

1. **Arithmetic Operators:**

   - What operator would you use to find the remainder of a division?

   - Write a code snippet that multiplies two numbers and prints the result.

2. **Comparison Operators:**

   - How would you check if two variables are not equal?

   - Write a program that checks if a number is less than 100.

3. **Logical Operators:**

   - What does the `and` operator do?

   - Write a program that checks if a person is eligible to vote (age should be 18 or more).

---