# Python if...else Statement

### Tutorial: Python `if...else` Statement

#### Introduction:
Welcome to CodesWithPankaj.com! In this tutorial, we'll explore the `if...else` statement in Python. The `if...else` statement allows you to make decisions in your code based on conditions. It's a fundamental building block for creating flexible and responsive programs. Let's dive into the world of `if...else` in Python!

#### Basic `if...else` Structure:

The `if...else` statement has the following structure:

```python
if condition:
    # Code to execute if the condition is True
else:
    # Code to execute if the condition is False
```

#### Example 1: Simple Comparison:

```python
# Example 1: Simple Comparison
x = 10

if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")
```

#### Example 2: User Input:

```python
# Example 2: User Input
user_age = int(input("Enter your age: "))

if user_age >= 18:
    print("You are eligible to vote.")
else:
    print("You are not eligible to vote.")
```

#### Example 3: Multiple Conditions:

```python
# Example 3: Multiple Conditions
num = int(input("Enter a number: "))

if num > 0:
    print("The number is positive.")
elif num == 0:
    print("The number is zero.")
else:
    print("The number is negative.")
```

#### Example 4: Nested `if...else`:

```python
# Example 4: Nested if...else
num = int(input("Enter a number: "))

if num >= 0:
    if num == 0:
        print("The number is zero.")
    else:
        print("The number is positive.")
else:
    print("The number is negative.")
```

#### Conclusion:

The `if...else` statement is a powerful tool for controlling the flow of your Python programs based on different conditions. Whether you're making simple comparisons or handling complex scenarios with multiple conditions, mastering the `if...else` statement is essential for writing dynamic and responsive code.

For more coding tips and tutorials, visit [CodesWithPankaj.com](https://codeswithpankaj.com). Happy coding! 
