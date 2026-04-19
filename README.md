# Python101

Personal notes for **Introduction to Python**.

## 1) What is Python?
- High-level, readable, general-purpose programming language.
- Interpreted language (you run scripts directly, no manual compile step in most workflows).
- Great for automation, web apps, data science, scripting, and learning programming basics.

## 2) Getting Started
- Check version:
  ```bash
  python --version
  ```
- Run Python REPL:
  ```bash
  python
  ```
- Run a script:
  ```bash
  python app.py
  ```

## 3) Basic Syntax
```python
print("Hello, Python!")
name = "Ada"
age = 20
is_student = True
```

- Python uses indentation (spaces) to define code blocks.
- Common style: 4 spaces per indent level.

## 4) Core Data Types
- `int` → whole numbers (`10`)
- `float` → decimal numbers (`3.14`)
- `str` → text (`"hello"`)
- `bool` → `True` / `False`
- `list` → ordered, mutable collection (`[1, 2, 3]`)
- `tuple` → ordered, immutable collection (`(1, 2, 3)`)
- `dict` → key-value pairs (`{"name": "Ada"}`)
- `set` → unique unordered values (`{1, 2, 3}`)

## 5) Operators
- Arithmetic: `+ - * / // % **`
- Comparison: `== != > < >= <=`
- Logical: `and or not`
- Assignment: `= += -= *= /=`

## 6) Control Flow
```python
score = 85

if score >= 90:
    grade = "A"
elif score >= 80:
    grade = "B"
else:
    grade = "C"
```

## 7) Loops
```python
for i in range(5):
    print(i)

count = 0
while count < 3:
    print(count)
    count += 1
```

## 8) Functions
```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Python"))
```

- Use functions to reuse logic and improve readability.
- Functions can have default values and keyword arguments.

## 9) Collections Practice
```python
numbers = [1, 2, 3]
numbers.append(4)

person = {"name": "Ada", "age": 20}
person["city"] = "Lagos"
```

## 10) Error Handling
```python
try:
    value = int("42")
except ValueError:
    print("Invalid number")
finally:
    print("Done")
```

## 11) Modules and Imports
```python
import math
from datetime import datetime

print(math.sqrt(25))
print(datetime.now())
```

## 12) Virtual Environments (Recommended)
```bash
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
# .venv\Scripts\activate   # Windows PowerShell
```

## 13) Best Practices for Beginners
- Write small programs often.
- Use clear variable names.
- Read error messages carefully.
- Practice with real mini-projects (calculator, to-do app, file parser).
- Follow PEP 8 style conventions.

## 14) Learning Checklist
- [ ] Variables and data types
- [ ] Conditionals and loops
- [ ] Functions
- [ ] Lists, tuples, dictionaries, sets
- [ ] Error handling
- [ ] Modules and packages
- [ ] File handling
- [ ] Object-oriented programming basics
