# Variables and Data Types

## Variables

A Variable is the name given to a memory location in a program.

### Examples

```python
name = "Shriyansh"
age = 14
is_learning_python = True
```

Here, `name`, `age`, and `is_learning_python` are variables.

---

### Rules for Naming Variables

- A variable name can contain alphabets, digits, and underscores.
- A variable name can only start with an alphabet or underscore.
- A variable name cannot start with a digit.
- No whitespace is allowed inside a variable name.

### Valid Variable Names

```python
name
_name
name1
age2
_name1
```

### Invalid Variable Names

```python
1name
n@me
23
```

---

## Data Types

There are mainly 5 data types in Python:

1. Integers
2. Floating Point Numbers
3. Strings
4. Booleans
5. None

### Integers

Integers are non-decimal number values.

Example:

```python
4
5
234
```

### Floating Point Numbers

Floating point numbers are decimal values.

Example:

```python
4.45
3.14
0.5
```

### Strings

Strings are letters, words, or sentences enclosed in quotes.

Example:

```python
"Hello World"
'Python'
```

### Booleans

Booleans represent `True` or `False`.

Example:

```python
True
False
```

### None

`None` represents the absence of a value.

Example:

```python
None
```
## Operators in Python

Following are some common operators in python:

1. Arithmetic operators: +, -, *, / etc.
2. Assignment operators: =, +=, -= etc.
3. Comparison operators: ==, >, >=, <, != etc.
4. Logical operators: and, or, not.

## type() function and Typecasting

type() function is used to find the data type of a given variable in python.
### Example-
```python
a = 31
type(a) # class <int>
b = "31"
type(b) # class <str>
```
A number can be converted into a string and vice versa (if possible)
There are many functions to convert one data type into another.
### Example-
```python
str(31) # integer to string conversion
int("32") # string to integer conversion
float(32) # integer to float conversion
```
... and so on.
Here "31" is a string literal and 31 a numeric literal.