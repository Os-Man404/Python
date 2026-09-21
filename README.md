# 🐍 Python Basics

A simple and structured collection of Python fundamentals, practice questions, and hands-on examples.

The notebook focuses on building a clear understanding of Python syntax and basic programming concepts through short, executable examples.

---

## 📚 Contents

| #  | Topic               | Concepts                                                      |
| -- | ------------------- | ------------------------------------------------------------- |
| 01 | 🖨️ **Print**       | `print()`, `sep`, `end`                                       |
| 02 | 📦 **Variables**    | Assignment, multiple assignment, swapping                     |
| 03 | ➕ **Operations**    | Arithmetic, comparison, logical operations                    |
| 04 | 🔀 **Control Flow** | `if`, `elif`, `else`, `pass`, `match`                         |
| 05 | ⌨️ **User Input**   | `input()`, type conversion                                    |
| 06 | 💬 **Comments**     | Single-line and multi-line comments                           |
| 07 | 🔤 **Strings**      | Concatenation, slicing, case conversion, searching            |
| 08 | 🔁 **Loops**        | `for`, `while`, `break`, `continue`                           |
| 09 | 📝 **Lists**        | Accessing, modifying, `append()`, `pop()`, list comprehension |
| 10 | ⚙️ **Functions**    | Parameters, arguments, default values, return statements      |

---

## 📂 Structure

```text
Python-Basics/
│
├── basic python.ipynb
└── README.md
```

---

## 🧩 What's Included?

The notebook is organized around small programming exercises that gradually introduce the building blocks of Python.

### Variables & Operations

```python
x = y = z = 100
print(x, y, z)
```

Basic arithmetic, comparison, logical operations, and variable manipulation are explored through simple examples.

### Control Flow

```python
score = 85

if score >= 90:
    print("Excellent")
elif score >= 70:
    print("Good")
else:
    print("Needs Improvement")
```

Conditional statements are used to understand how programs make decisions based on different conditions.

### Lists

```python
squares = [x**2 for x in range(1, 6)]
print(squares)
```

The notebook introduces list operations along with useful techniques such as list comprehension.

### Functions

```python
def square(num):
    return num * num

print(square(4))
```

Functions demonstrate how reusable pieces of logic can be created using parameters and return values.

---

## 🛠️ Tools

* **Python 3**
* **Jupyter Notebook**
* **Google Colab**
* **VS Code**

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone <your-repository-url>
cd Python-Basics
```

Then open:

```text
basic python.ipynb
```

The notebook can be executed using Jupyter Notebook, JupyterLab, Google Colab, or VS Code.

---

## 🗺️ Learning Flow

```text
Print
  ↓
Variables
  ↓
Operations
  ↓
Control Flow
  ↓
User Input
  ↓
Comments
  ↓
Strings
  ↓
Loops
  ↓
Lists
  ↓
Functions
```

Each section builds on the previous concepts, making the notebook suitable for practicing Python fundamentals step by step.

---

## 💡 A Simple Way to Practice

**Read → Run → Modify → Observe → Experiment**

Try changing the values in the examples, predict the output before running the code, and then create small variations of each exercise.

---

### 📌 Note

This repository contains foundational Python practice material and is intended to serve as a reference while progressing toward more advanced Python programming and projects.
