# Python Functions 

#### Introduction:
Welcome to an in-depth exploration of functions in Python at CodesWithPankaj.com! Functions are blocks of organized, reusable code designed to perform a specific task. They provide a way to structure code, promote code reusability, and enhance maintainability. Let's delve into the details of Python functions.

#### Basic Syntax:
The basic syntax of a function in Python is as follows:

```python
def function_name(parameters):
    """
    Docstring: Description of the function
    """
    # Code block
    return result  # Optional return statement
```

- `def`: Keyword indicating the start of a function definition.
- `function_name`: Name of the function.
- `parameters`: Input parameters the function takes (if any).
- `Docstring`: Optional documentation describing the function's purpose and usage.
- `return`: Optional statement to return a value from the function.

#### Example 1: Simple Function

```python
# Example 1: Simple Function
def greet(name):
    """This function greets the person passed in as a parameter."""
    print("Hello, " + name + "!")

# Function call
greet("Alice")
```

**Output:**
```
Hello, Alice!
```

#### Parameters and Arguments:

- **Parameters:** Variables that are used in a function definition.
- **Arguments:** Values passed to a function when it is called.

#### Example 2: Function with Multiple Parameters

```python
# Example 2: Function with Multiple Parameters
def add_numbers(x, y):
    """This function adds two numbers."""
    result = x + y
    return result

# Function call
sum_result = add_numbers(5, 7)
print("Sum:", sum_result)
```

**Output:**
```
Sum: 12
```

#### Default Parameters:

You can assign default values to parameters in a function.

#### Example 3: Function with Default Parameter

```python
# Example 3: Function with Default Parameter
def greet_person(name, greeting="Hello"):
    """This function greets a person with an optional custom greeting."""
    print(greeting + ", " + name + "!")

# Function calls
greet_person("Bob")
greet_person("Charlie", "Good morning")
```

**Output:**
```
Hello, Bob!
Good morning, Charlie!
```

#### Variable-Length Arguments:

You can use `*args` to pass a variable number of non-keyword arguments to a function.

#### Example 4: Function with Variable-Length Arguments

```python
# Example 4: Function with Variable-Length Arguments
def calculate_sum(*args):
    """This function calculates the sum of a variable number of arguments."""
    return sum(args)

# Function calls
result1 = calculate_sum(1, 2, 3)
result2 = calculate_sum(10, 20, 30, 40)

print("Sum 1:", result1)
print("Sum 2:", result2)
```

**Output:**
```
Sum 1: 6
Sum 2: 100
```

#### Keyword Arguments:

You can use `**kwargs` to pass a variable number of keyword arguments to a function.

#### Example 5: Function with Keyword Arguments

```python
# Example 5: Function with Keyword Arguments
def display_info(**kwargs):
    """This function displays information using keyword arguments."""
    for key, value in kwargs.items():
        print(key + ": " + value)

# Function calls
display_info(name="Alice", age="25", country="USA")
display_info(name="Bob", profession="Engineer")
```

**Output:**
```
name: Alice
age: 25
country: USA
name: Bob
profession: Engineer
```

#### Return Statement:

A function can use the `return` statement to send a result back to the caller.

#### Example 6: Function with Return Statement

```python
# Example 6: Function with Return Statement
def square(number):
    """This function calculates the square of a number."""
    return number ** 2

# Function call
result = square(4)
print("Square:", result)
```

**Output:**
```
Square: 16
```

#### Global and Local Variables:

Variables declared inside a function have local scope, while those declared outside have global scope.

#### Example 7: Global and Local Variables

```python
# Example 7: Global and Local Variables
global_variable = "I am global!"

def my_function():
    local_variable = "I am local!"
    print(global_variable)
    print(local_variable)

# Function call
my_function()

# Accessing global_variable outside the function
print("Outside function:", global_variable)

# Trying to access local_variable outside the function will result in an error
# print("Outside function:", local_variable)
```

**Output:**
```
I am global!
I am local!
Outside function: I am global!
```

#### Lambda Functions (Anonymous Functions):

Lambda functions are small, anonymous functions defined using the `lambda` keyword.

#### Example 8: Lambda Function

```python
# Example 8: Lambda Function
multiply = lambda x, y: x * y

# Function call
result = multiply(3, 4)
print("Multiplication:", result)
```

**Output:**
```
Multiplication: 12
```

#### Conclusion:

Functions in Python provide a powerful way to organize and structure code. They enhance code readability, reusability, and maintainability. With the ability to define parameters, default values, variable-length arguments, and keyword arguments, Python functions offer flexibility for various programming needs.

For more coding tips and tutorials, visit [CodesWithPankaj.com](https://codeswithpankaj.com). Happy coding!
