# Python Basic Input and Output

#### Introduction:
Welcome to CodesWithPankaj.com! In this tutorial, we'll explore the fundamental concepts of input and output in Python. Input allows users to provide data to a program, while output enables the program to display information to the user. Let's dive into the world of basic input and output in Python!

#### Basic Output (print function):

The `print()` function is used to display output in Python.

```python
# Basic Output
print("Hello, Python!")
```

#### Formatted Output:

You can format output using the `format()` method or f-strings.

```python
# Formatted Output
name = "Pankaj"
age = 25
print("My name is {} and I am {} years old.".format(name, age))

# Using f-string (Python 3.6 and above)
print(f"My name is {name} and I am {age} years old.")
```

#### Basic Input (input function):

The `input()` function is used to take user input. It returns a string that can be converted to the desired data type.

```python
# Basic Input
user_input = input("Enter your name: ")
print("Hello, " + user_input + "!")
```

#### Converting Input to Numeric Types:

You can convert user input to numeric types (int, float) using type casting.

```python
# Converting Input to Numeric Types
age_input = input("Enter your age: ")
age = int(age_input)  # Convert the input to an integer
print("Next year, you'll be", age + 1, "years old.")
```

#### Example Code:

Now, let's create a Python script that combines basic input and output:

```python
# codeswithpankaj_input_output.py

# Basic Output
print("Welcome to CodesWithPankaj.com!")

# Formatted Output
name = input("Enter your name: ")
age = int(input("Enter your age: "))
print("Hello, {}! You are {} years old.".format(name, age))

# Basic Input
user_input = input("Enter any message: ")
print("You entered:", user_input)
```

#### Conclusion:

Understanding basic input and output is essential for creating interactive and user-friendly Python programs. By incorporating these concepts, you can build applications that respond to user input and provide meaningful output.

For more coding tips and tutorials, visit [CodesWithPankaj.com](https://codeswithpankaj.com). Happy coding!
