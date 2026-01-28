# 🛠️ Python Lab: Data Structures - Tuples

## 📝 Abstract
This module focuses on the implementation and constraints of the **Tuple**—a fundamental sequence type in Python. The experiment highlights why immutability matters in software architecture and how tuples differ from the more common List structure.

---

## 🎯 Aim & Objectives
* **Study** the syntax and structure of Python tuples.
* **Implement** indexing, slicing, and membership operations.
* **Analyze** the performance and memory benefits of using immutable sequences.

## ⚙️ Environment
* **Compiler:** Python 3.x
* **Platform:** Google Colab / Jupyter Notebook

---

## 📘 Technical Theory

### The "Immutable Sequence" Concept
A **Tuple** is an ordered collection of objects. Unlike lists, tuples are "frozen" upon creation. This makes them ideal for storing data that should not be accidentally overwritten by a program.



### 🏗️ Structure & Syntax
| Type | Representation | Example |
| :--- | :--- | :--- |
| **Empty Tuple** | `()` | `my_tuple = ()` |
| **Single Element** | `(val,)` | `point = (10,)` |
| **Multi-Element** | `(v1, v2, ...)` | `colors = ('red', 'green', 'blue')` |

### 🔍 Operation Compatibility
Since tuples are immutable, we categorize operations based on whether they "read" or "write" data:

#### ✅ Supported (Read-Only)
* **Indexing:** `tup[0]` — Fetching elements by position.
* **Slicing:** `tup[1:3]` — Extracting a sub-sequence.
* **Membership:** `'item' in tup` — Boolean existence check.
* **Meta-data:** `len(tup)` — Calculating sequence size.

#### ❌ Unsupported (Modification)
The following operations will trigger a `TypeError`:
* `.append()` / `.extend()`
* `.pop()` / `.remove()`
* `.sort()` (Use the `sorted()` function instead, which returns a *new* list).

---

## 🚀 Practical Applications & Why It Matters

### 1. Data Integrity & Security
In large-scale applications, using a tuple ensures that a function cannot maliciously or accidentally change the input data.

### 2. Geometry & Design
Tuples are the standard for fixed mathematical constants:
* **RGB Colors:** `(255, 255, 255)` for White.
* **GIS Coordinates:** `(18.5204, 73.8567)` for a specific location.

### 3. Optimization
* **Memory Efficiency:** Tuples require less overhead than lists.
* **Speed:** Iterating over a tuple is faster than iterating over a list.

---

## 💡 Key Observations & Learning
* **Iterability:** Tuples can only be created from "iterables." You cannot convert a single `int` or `float` into a tuple without putting it in a collection first.
* **Type Casting:** The `tuple()` constructor is a powerful tool for locking a list’s data.
* **Hashability:** Tuples can be used as **Dictionary Keys**, whereas lists cannot.

---

## 🏁 Final Conclusion
The experiment successfully demonstrated that while Tuples and Lists share a similar look, their internal mechanics are vastly different. Understanding **immutability** allows for writing more secure, memory-efficient, and bug-resistant Python code.
