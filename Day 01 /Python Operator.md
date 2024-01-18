
#### Introduction:
Welcome to CodesWithPankaj.com! In this tutorial, we'll explore the various operators in Python. Operators are symbols that perform operations on variables and values. Understanding these operators is fundamental for writing effective Python code. Let's dive into the world of Python operators!

#### Arithmetic Operators:

1. **Addition (`+`):** Adds two operands.
2. **Subtraction (`-`):** Subtracts the right operand from the left operand.
3. **Multiplication (`*`):** Multiplies two operands.
4. **Division (`/`):** Divides the left operand by the right operand.
5. **Modulus (`%`):** Returns the remainder of the division.
6. **Exponentiation (`**`):** Raises the left operand to the power of the right operand.
7. **Floor Division (`//`):** Returns the floor of the division (quotient without remainder).

```python
# Arithmetic Operators
a = 10
b = 3

addition_result = a + b
subtraction_result = a - b
multiplication_result = a * b
division_result = a / b
modulus_result = a % b
exponentiation_result = a ** b
floor_division_result = a // b

print("Addition:", addition_result)
print("Subtraction:", subtraction_result)
print("Multiplication:", multiplication_result)
print("Division:", division_result)
print("Modulus:", modulus_result)
print("Exponentiation:", exponentiation_result)
print("Floor Division:", floor_division_result)
```

#### Comparison Operators:

1. **Equal to (`==`):** True if both operands are equal.
2. **Not equal to (`!=`):** True if operands are not equal.
3. **Greater than (`>`):** True if the left operand is greater than the right operand.
4. **Less than (`<`):** True if the left operand is less than the right operand.
5. **Greater than or equal to (`>=`):** True if the left operand is greater than or equal to the right operand.
6. **Less than or equal to (`<=`):** True if the left operand is less than or equal to the right operand.

```python
# Comparison Operators
x = 5
y = 8

equal_result = x == y
not_equal_result = x != y
greater_than_result = x > y
less_than_result = x < y
greater_equal_result = x >= y
less_equal_result = x <= y

print("Equal:", equal_result)
print("Not Equal:", not_equal_result)
print("Greater Than:", greater_than_result)
print("Less Than:", less_than_result)
print("Greater Than or Equal To:", greater_equal_result)
print("Less Than or Equal To:", less_equal_result)
```

#### Logical Operators:

1. **Logical AND (`and`):** True if both operands are true.
2. **Logical OR (`or`):** True if at least one operand is true.
3. **Logical NOT (`not`):** True if the operand is false.

```python
# Logical Operators
p = True
q = False

and_result = p and q
or_result = p or q
not_result_p = not p
not_result_q = not q

print("Logical AND:", and_result)
print("Logical OR:", or_result)
print("Logical NOT (p):", not_result_p)
print("Logical NOT (q):", not_result_q)
```

#### Assignment Operators:

1. **Assignment (`=`):** Assigns the value on the right to the variable on the left.
2. **Addition Assignment (`+=`):** Adds the right operand to the left operand and assigns the result to the left operand.
3. **Subtraction Assignment (`-=`):** Subtracts the right operand from the left operand and assigns the result to the left operand.
4. **Multiplication Assignment (`*=`):** Multiplies the left operand by the right operand and assigns the result to the left operand.
5. **Division Assignment (`/=`):** Divides the left operand by the right operand and assigns the result to the left operand.
6. **Modulus Assignment (`%=`):** Computes the modulus of the left operand with the right operand and assigns the result to the left operand.
7. **Exponentiation Assignment (`**=`):** Raises the left operand to the power of the right operand and assigns the result to the left operand.
8. **Floor Division Assignment (`//=`):** Computes the floor division of the left operand by the right operand and assigns the result to the left operand.

```python
# Assignment Operators
x = 10
y = 3

# Basic assignment
a = x

# Addition assignment
x += y  # equivalent to x = x + y

# Subtraction assignment
x -= y  # equivalent to x = x - y

# Multiplication assignment
x *= y  # equivalent to x = x * y

# Division assignment
x /= y  # equivalent to x = x / y

# Modulus assignment
x %= y  # equivalent to x = x % y

# Exponentiation assignment
x **= y  # equivalent to x = x ** y

# Floor Division assignment
x //= y  # equivalent to x = x // y

print("Basic Assignment:", a)
print("Addition Assignment:", x)
```

#### Identity Operators:

1. **Identity (`is`):** True if both operands refer to the same object.
2. **Not Identity (`is not`):** True if both operands do not refer to the same object.

```python
# Identity Operators
list1 = [1, 2, 3]
list2 = [1, 2, 3]
list3 = list1

is_result = list1 is list2
is_not_result = list1 is not list3

print("Identity (is):", is_result)
print("Not Identity (is not):", is_not_result)
```

#### Membership Operators:

1. **Membership (`in`):** True if a value is found in the sequence.
2. **Not Membership (`not in`):** True if a value is not found in the sequence.

```python
# Membership Operators
numbers = [1, 2, 3, 4, 5]

in_result = 3 in numbers
not_in_result = 6 not in numbers

print("Membership (in):", in_result)
print("Not Membership (not in):", not_in_result)
```

#### Bitwise Operators:

1. **Bitwise AND (`&`):** Performs bitwise AND.
2. **Bitwise OR (`|`):** Performs bitwise OR.
3. **Bitwise XOR (`^`):** Performs bitwise XOR.
4. **Bitwise NOT (`~`):** Inverts the bits of a number.
5. **Left Shift (`<<`):** Shifts the bits to the left.
6. **Right Shift (`>>`):** Shifts the bits to the right.

```python
# Bitwise Operators
a = 5  # binary: 0101
b = 3  # binary: 001

1

bitwise_and_result = a & b  # binary: 0001 (decimal: 1)
bitwise_or_result = a | b   # binary: 0111 (decimal: 7)
bitwise_xor_result = a ^ b  # binary: 0110 (decimal: 6)
bitwise_not_result = ~a     # binary: 1010 (decimal: -6, due to two's complement representation)
left_shift_result = a << 1   # binary: 1010 (decimal: 10)
right_shift_result = a >> 1  # binary: 0010 (decimal: 2)

print("Bitwise AND:", bitwise_and_result)
print("Bitwise OR:", bitwise_or_result)
print("Bitwise XOR:", bitwise_xor_result)
print("Bitwise NOT:", bitwise_not_result)
print("Left Shift:", left_shift_result)
print("Right Shift:", right_shift_result)
```

#### Conclusion:

Understanding Python operators is crucial for performing various operations on data. By mastering these operators, you gain the ability to manipulate values, compare conditions, and perform bitwise operations in your Python programs.

For more coding tips and tutorials, visit [CodesWithPankaj.com](https://codeswithpankaj.com). Happy coding!
