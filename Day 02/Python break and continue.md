# Python break and continue 

#### Introduction:
Welcome to an exploration of the `break` and `continue` statements in Python at CodesWithPankaj.com! These statements provide control over the execution flow within loops. Understanding how to use `break` and `continue` is crucial for efficient loop management. Let's dive into the details.

#### `break` Statement:
The `break` statement is used to exit a loop prematurely, regardless of whether the loop condition is still true.

#### Example 1: Using `break` in a `for` Loop

```python
# Example 1: Using break in a for Loop
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for num in numbers:
    if num == 5:
        break  # exit the loop when num is 5
    print(num)
```

**Output:**
```
1
2
3
4
```

#### Example 2: Using `break` in a `while` Loop

```python
# Example 2: Using break in a while Loop
counter = 1

while counter <= 5:
    print(f"Count: {counter}")
    if counter == 3:
        break  # exit the loop when counter is 3
    counter += 1
```

**Output:**
```
Count: 1
Count: 2
Count: 3
```

#### `continue` Statement:
The `continue` statement is used to skip the rest of the code inside a loop for the current iteration and move on to the next iteration.

#### Example 3: Using `continue` in a `for` Loop

```python
# Example 3: Using continue in a for Loop
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for num in numbers:
    if num % 2 == 0:
        continue  # skip the rest of the code for even numbers
    print(num)
```

**Output:**
```
1
3
5
7
9
```

#### Example 4: Using `continue` in a `while` Loop

```python
# Example 4: Using continue in a while Loop
counter = 1

while counter <= 5:
    if counter == 3:
        counter += 1
        continue  # skip the rest of the code for counter equal to 3
    print(f"Count: {counter}")
    counter += 1
```

**Output:**
```
Count: 1
Count: 2
Count: 4
Count: 5
```

#### Conclusion:

The `break` and `continue` statements are powerful tools for controlling the flow of loops in Python. While `break` allows you to exit a loop prematurely, `continue` lets you skip the remaining code for the current iteration and move on to the next one. These statements contribute to writing cleaner and more efficient code.

For more coding tips and tutorials, visit [CodesWithPankaj.com](https://codeswithpankaj.com). Happy coding!
