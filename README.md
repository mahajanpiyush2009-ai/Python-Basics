# Python Basics - Lists, Sets, and Dictionaries

## Overview

This project demonstrates the basic concepts of Python data structures. It covers how to create, access, and modify **Lists**, **Sets**, and **Dictionaries** using built-in Python methods.

---

# 1. List (`[]`)

## Definition

A **List** is an ordered and mutable (changeable) collection in Python. It can store multiple values of different data types and allows duplicate elements.

### Concepts Covered

* Creating a list
* Accessing elements using indexing
* Finding the length of a list using `len()`
* Adding elements using `append()`
* Inserting elements at a specific position using `insert()`
* Combining two lists using `extend()`

### Methods Used

| Method                 | Description                                 |
| ---------------------- | ------------------------------------------- |
| `append()`             | Adds an element to the end of the list.     |
| `insert(index, value)` | Inserts an element at the specified index.  |
| `extend(list)`         | Adds all elements of another list.          |
| `len()`                | Returns the number of elements in the list. |

---

# 2. Set (`{}`)

## Definition

A **Set** is an unordered collection of unique elements. Duplicate values are automatically removed. Sets are useful when only distinct values are required.

### Concepts Covered

* Creating a set
* Automatic removal of duplicate values
* Creating an empty set using `set()`
* Removing multiple elements using `difference_update()`

### Methods Used

| Method                | Description                                     |
| --------------------- | ----------------------------------------------- |
| `difference_update()` | Removes the elements that exist in another set. |

---

# 3. Dictionary (`{key: value}`)

## Definition

A **Dictionary** is a collection of key-value pairs. Each key is unique and is used to access its corresponding value.

### Concepts Covered

* Creating a dictionary
* Accessing values using keys
* Displaying all key-value pairs using `items()`

### Methods Used

| Method    | Description                                   |
| --------- | --------------------------------------------- |
| `items()` | Returns all key-value pairs as a view object. |

---

# Summary

This project demonstrates the following Python concepts:

* List creation and manipulation
* List indexing
* List methods (`append()`, `insert()`, `extend()`)
* Set creation
* Duplicate removal in sets
* Set operations using `difference_update()`
* Dictionary creation
* Accessing dictionary values
* Displaying dictionary items using `items()`

These concepts form the foundation of Python programming and are commonly used in data handling and application development.
