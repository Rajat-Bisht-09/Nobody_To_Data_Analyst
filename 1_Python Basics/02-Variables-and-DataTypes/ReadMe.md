
# Variables and Data Types

This section explains how to use variables in Python and explores its fundamental data types.

## Topics Covered
1. **Variables**
   - Variables are containers for storing data values that can be referenced and manipulated during program execution.
   - Example:
     ```python
     age = 25
     name = "John"
     print(age, name)
     ```
   - Python variables don’t need explicit declaration; the type is inferred. It means based on the value, the variable implicitly inferred its data type.<br>
   
   **Rules for naming a `Variable`**

   To use variables effectively, we must follow Python’s naming rules:
   - Variable names can only contain letters, digits and underscores (_).
   - A variable name cannot start with a digit.
   - Variable names are case-sensitive (myVar and myvar are different).
   - Avoid using Python keywords (e.g., if, else, for) as variable names.


3. **Data Types**
   - **Numeric Types**: `int`, `float`, `complex`
   - **Text Type**: `str`
   - **Sequence Types**: `list`, `tuple`, `range`
   - **Mapping Type**: `dict`
   - **Set Types**: `set`, `frozenset`
   - **Boolean Type**: `bool`
   - **None Type**: `NoneType`

4. **Type Casting**
   - Explicitly convert one data type to another.
   - Example:
     ```python
     x = int("10")
     y = float("5.5")
     print(x + y)  # 15.5
     ```

5. **Dynamic Typing**
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
