# 📚 Day 01: Python Basics Quick Guide

## 🎯 Core Concepts

### 📝 Output & Variables

- **🖨️ Print**: `print("Hello, World!")` - Display text/values
- **📦 Variables**: `x = 5` - Store data in containers
- **🔤 Strings**: `x = "Hello"` - Text values
- **🔢 Numbers**: `x = 5` (int), `x = 5.5` (float)
- **✍️ Character**: `x = 'c'` - Single character string

### 🏷️ Data Types

- **🔍 Type Check**: `type(x)` - Find what type your data is
- **🔄 Type Conversion**: `int(5)`, `str("Hello")` - Convert between types

### 🧮 Math Operations

- **➕ Addition**: `x + y`
- **➖ Subtraction**: `x - y`
- **✖️ Multiplication**: `x * y`
- **➗ Division**: `x / y`
- **📊 Remainder**: `a % b`

### 📛 Naming Rules

- `myclass = 5` - Normal variable
- `_myclass = 5` - Private variable (starts with \_)
- `age`, `Age`, `AGE` - Case-sensitive (different variables!)

---

## 🔀 Control Flow

### ❓ If/Elif/Else

```python
if a > b:
    print("a is greater")
elif a == b:
    print("equal")
else:
    print("b is greater")
```

### 🔁 While Loop

```python
i = 1
while i < 6:
    print(i)
    i += 1  # Keep looping until condition is false
```

### 🔁 For Loop

```python
for letter in ['a', 'b', 'c']:  # Loop through list items
    print(letter)

for x in "banana":              # Loop through string characters
    print(x)

for x in range(1, 6):           # Loop from 1 to 5
    print(x)
```

### 🛑 Break & Continue

- **🛑 Break**: `break` - Stop loop immediately
- **⏭️ Continue**: `continue` - Skip to next iteration

### 🔄 Nested Loops

```python
for x in letters:
    for y in numbers:  # Loop inside loop
        print(x, y)
```

---

## ⚙️ Functions

### 🎯 Define & Call

```python
def myfun(fname):
    print("Hello " + fname)

myfun("Alice")  # Call function with argument
```

### 📊 Function with Multiple Operations

```python
def my_function(a, b):
    print(a + b)
    print(a - b)
    # Can return or print results
```

### 🌍 Global Scope

```python
x = "Good"
def myfunc():
    print(x)  # Access global variable inside function
```

---

## 📊 Statistics (from `statistics` module)

### 📈 Statistical Functions

```python
from statistics import mean, median, mode, stdev

data = [1, 2, 3, 4, 5]

median(data)   # 📌 Middle value
mean(data)     # 📏 Average value
mode(data)     # 🔤 Most frequent value
stdev(data)    # 📐 How spread out data is
```

---

## 🎓 Key Takeaways

| Emoji | Concept    | Example                                   |
| ----- | ---------- | ----------------------------------------- |
| 📦    | Variable   | `x = 5`                                   |
| 🔢    | Number     | `int`, `float`                            |
| 🔤    | String     | `"Hello"`                                 |
| 🧮    | Math       | `+`, `-`, `*`, `/`, `%`                   |
| ❓    | Condition  | `if`, `elif`, `else`                      |
| 🔁    | Loop       | `for`, `while`                            |
| ⚙️    | Function   | `def myfun():`                            |
| 📊    | Statistics | `mean()`, `median()`, `mode()`, `stdev()` |

---

✅ **Master these basics and you're ready for Machine Learning!**
