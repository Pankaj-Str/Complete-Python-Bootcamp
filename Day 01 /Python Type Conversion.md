# Python Type Conversion 


#### Introduction:
Welcome to CodesWithPankaj.com! In this tutorial, we'll explore the concept of type conversion in Python. Type conversion, also known as type casting, is the process of converting one data type into another. Python provides built-in functions for this purpose, allowing you to work seamlessly with different types of data. Let's dive into the world of Python type conversion!

#### Implicit vs. Explicit Type Conversion:

1. **Implicit Type Conversion (Coercion):**
   - Python automatically converts one data type to another.
   - It occurs during operations between different data types.

   ```python
   # Implicit Type Conversion
   int_number = 10
   float_number = 3.5
   
   result = int_number + float_number  # int_number is implicitly converted to float
   ```

2. **Explicit Type Conversion (Type Casting):**
   - You explicitly convert a data type using predefined functions.
   - Common functions: `int()`, `float()`, `str()`, etc.

   ```python
   # Explicit Type Conversion
   float_number = 3.5
   
   # Convert float to int
   int_number = int(float_number)
   ```

#### Common Type Conversion Functions:

1. **`int()`:** Converts a value to an integer.

   ```python
   float_number = 3.8
   int_number = int(float_number)  # Result: 3
   ```

2. **`float()`:** Converts a value to a floating-point number.

   ```python
   int_number = 5
   float_number = float(int_number)  # Result: 5.0
   ```

3. **`str()`:** Converts a value to a string.

   ```python
   numeric_value = 42
   string_value = str(numeric_value)  # Result: "42"
   ```

4. **`list()`, `tuple()`, `set()`:** Converts a sequence to a list, tuple, or set.

   ```python
   my_tuple = (1, 2, 3)
   list_version = list(my_tuple)  # Result: [1, 2, 3]
   ```

5. **`bool()`:** Converts a value to a boolean.

   ```python
   numeric_value = 0
   boolean_value = bool(numeric_value)  # Result: False
   ```

#### Example Code:

Now, let's create a Python script that demonstrates both implicit and explicit type conversion:

```python
# codeswithpankaj_type_conversion.py

# Implicit Type Conversion
int_number = 10
float_number = 3.5

result = int_number + float_number  # int_number is implicitly converted to float
print("Implicit Conversion Result:", result)

# Explicit Type Conversion
float_number = 3.8

# Convert float to int
int_number = int(float_number)
print("Explicit Conversion Result (float to int):", int_number)

# Convert int to str
numeric_value = 42
string_value = str(numeric_value)
print("Explicit Conversion Result (int to str):", string_value)

# Convert list to set
my_list = [1, 2, 3, 3, 4]
set_version = set(my_list)
print("Explicit Conversion Result (list to set):", set_version)
```

#### Conclusion:

Understanding type conversion in Python is crucial for working with diverse data types. Whether it's automatic (implicit) or manually triggered (explicit), type conversion allows you to handle data more flexibly in your programs.

For more coding tips and tutorials, visit [CodesWithPankaj.com](https://codeswithpankaj.com). Happy coding!
