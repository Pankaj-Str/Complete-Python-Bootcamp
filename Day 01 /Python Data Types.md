# Python Data Types

#### Introduction:
Welcome to CodesWithPankaj.com! In this tutorial, we'll explore the various data types in Python. Understanding data types is crucial for writing effective and efficient Python code. Let's dive into the world of Python data types!

#### Common Data Types:

Python supports several built-in data types. Here are some of the most common ones:

| Data Types | Classes           | Description                                |
|------------|-------------------|--------------------------------------------|
| Numeric    | int, float, complex| Holds numeric values                       |
| String     | str               | Holds a sequence of characters             |
| Sequence   | list, tuple, range | Holds a collection of items                |
| Mapping    | dict              | Holds data in key-value pair form          |
| Boolean    | bool              | Holds either True or False                 |
| Set        | set, frozenset     | Holds a collection of unique items         |

1. **Numeric Types:**
   - **int:** Integer type, e.g., `5`, `-10`.
   - **float:** Floating-point type, e.g., `3.14`, `2.0`.
   - **complex:** Complex number type, e.g., `2 + 3j`.

   ```python
   # Numeric types
   integer_number = 42
   float_number = 3.14
   complex_number = 2 + 3j
   ```

2. **Sequence Types:**
   - **str:** String type, e.g., `"Hello, Python!"`.
   - **list:** List type, e.g., `[1, 2, 3]`.
   - **tuple:** Tuple type, e.g., `(1, 2, 3)`.

   ```python
   # Sequence types
   string_data = "Hello, Python!"
   list_data = [1, 2, 3]
   tuple_data = (1, 2, 3)
   ```

3. **Boolean Type:**
   - **bool:** Boolean type, either `True` or `False`.

   ```python
   # Boolean type
   is_true = True
   is_false = False
   ```

4. **Set Types:**
   - **set:** Unordered collection of unique elements.
   - **frozenset:** Immutable set.

   ```python
   # Set types
   set_data = {1, 2, 3}
   frozen_set_data = frozenset({4, 5, 6})
   ```

5. **Mapping Type:**
   - **dict:** Dictionary type, a collection of key-value pairs.

   ```python
   # Mapping type
   dictionary_data = {"name": "John", "age": 25, "city": "New York"}
   ```

6. **None Type:**
   - **None:** Represents the absence of a value.

   ```python
   # None type
   no_value = None
   ```

#### Example Code:

Now, let's create a Python script that demonstrates the use of various data types:

```python
# codeswithpankaj_data_types.py

# Numeric types
integer_number = 42
float_number = 3.14
complex_number = 2 + 3j

# Sequence types
string_data = "Hello, Python!"
list_data = [1, 2, 3]
tuple_data = (1, 2, 3)

# Boolean type
is_true = True
is_false = False

# Set types
set_data = {1, 2, 3}
frozen_set_data = frozenset({4, 5, 6})

# Mapping type
dictionary_data = {"name": "John", "age": 25, "city": "New York"}

# None type
no_value = None

# Displaying values
print("Numeric Types:", integer_number, float_number, complex_number)
print("Sequence Types:", string_data, list_data, tuple_data)
print("Boolean Type:", is_true, is_false)
print("Set Types:", set_data, frozen_set_data)
print("Mapping Type:", dictionary_data)
print("None Type:", no_value)
```

#### Conclusion:

Understanding Python data types is crucial for writing robust and flexible code. By utilizing the appropriate data type for your variables, you can ensure efficient data manipulation and enhance the overall quality of your programs.

For more coding tips and tutorials, visit [CodesWithPankaj.com](https://codeswithpankaj.com). Happy coding!
