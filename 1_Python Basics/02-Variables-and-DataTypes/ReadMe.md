
# Variables and Data Types

This section explains how to use variables in Python and explores its fundamental data types.

## Topics Covered
1. **Variables**
   - Variables are containers for storing data values.
   - Example:
     ```python
     age = 25
     name = "John"
     print(age, name)
     ```
   - Python variables don’t need explicit declaration; the type is inferred.

2. **Data Types**
   - **Numeric Types**: `int`, `float`, `complex`
   - **Text Type**: `str`
   - **Sequence Types**: `list`, `tuple`, `range`
   - **Mapping Type**: `dict`
   - **Set Types**: `set`, `frozenset`
   - **Boolean Type**: `bool`
   - **None Type**: `NoneType`

3. **Type Casting**
   - Explicitly convert one data type to another.
   - Example:
     ```python
     x = int("10")
     y = float("5.5")
     print(x + y)  # 15.5
     ```

4. **Dynamic Typing**
   - A variable can change its type during runtime:
     ```python
     x = 10  # x is an integer
     x = "Python"  # Now, x is a string
     ```

## Practical Examples
1. [`variable_declaration.py`](./variable_declaration.py): Demonstrates variable declaration and usage.
2. [`data_types.py`](./data_types.py): Examples of various data types.
3. [`type_casting.py`](./type_casting.py): Shows how to convert data types.
4. [`dynamic_typing.py`](./dynamic_typing.py): Explores Python’s dynamic typing feature.
